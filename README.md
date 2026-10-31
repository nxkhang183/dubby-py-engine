# dubby-py-engine

Release host for the self-contained Python engine runtimes (faster-whisper and friends) and the sherpa-onnx native libraries that [Dubby](https://github.com/nxkhang183/Dubby) downloads. The app reads the `latest` release (`manifest.json`, `checksums.sha256` and one archive per engine/platform); `yarn install` fetches `sherpa-libs-latest`.

The artifacts were built by [buxuku/smartsub-py-engine](https://github.com/buxuku/smartsub-py-engine). MIT licensed; see [LICENSE](LICENSE).
