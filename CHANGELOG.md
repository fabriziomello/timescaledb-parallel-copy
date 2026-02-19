# Changelog

## [0.13.0](https://github.com/fabriziomello/timescaledb-parallel-copy/compare/v0.12.0...v0.13.0) (2026-02-19)


### Features

* add WithQueueSize option to csvcopy.NewCopier ([8beb8c5](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/8beb8c5e088cecc4d23815cfee87afe21ab34278))
* column mapping and auto column mapping ([fb931ee](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/fb931ee0a11947d836d2a9cbd2a8cf3257b85c7f))
* extra info in duplicate database columns in mapping ([c33a859](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/c33a859b9d3fe883f3146bb4baeca619992ed189))
* extra info in duplicate database columns in mapping ([8ab274a](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/8ab274ad27a863d2243b9f6f200013c2f817553d))
* handle Windows-1252 encoded CSV data for UTF-8 targets ([#136](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/136)) ([78a24cd](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/78a24cd1ad8be8b43f22f17e6b9027896bf6c978))
* implement rewind buffer ([54d6359](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/54d6359e7c960c07d26b9e8a72281a5f6b76969b))
* retry when encountering recoverable errors ([#135](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/135)) ([e0ff4d8](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/e0ff4d8445e00f6bc0486d9d901b4d26e923a2e9))
* skip lines and not headers ([7fef706](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/7fef706047f727749986832a7fbc7cd918eecb5e))
* use 4 MiB default buffer batch size ([#130](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/130)) ([61edda4](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/61edda489aaab7986222ce59dbc3b72952c455c0))
* use pre-allocated buffer pool for batching ([#129](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/129)) ([bc9e722](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/bc9e722bbca200447a2a9d755e7848d9a68c7917))


### Bug Fixes

* add buffer size to 'buffer too small' error ([#133](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/133)) ([eccb04d](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/eccb04d6cd71c889df67aee253f3748d8cda9992))
* correct disable-direct-compress logic ([#142](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/142)) ([387bfc2](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/387bfc26f74895890f6c431b594d7efb7c8b37dc))
* make sure reports are sent since the start of the Copy function ([1089367](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/10893677b8628d58a5ce64c625fae45170d25188))
* make sure reports are sent since the start of the Copy function ([782e637](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/782e637f2f79356f43deed5ab6cdc89c1a74d208))
* properly implement flags ([6c15df0](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/6c15df0f9432eadd48e4507c2f256309a58cb106))
* redundant index on transactions table ([#126](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/126)) ([69d6d80](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/69d6d802b120f4bb6039edb045f24b650f9df639))
* s/temporal/temporary/ ([4370b80](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/4370b80a94bfc05ef75e4ea1043772888dd2a679))
* treat query cancelled as recoverable error ([#148](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/148)) ([4c6e069](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/4c6e069d5e33e9b9039b0e91232c84f110bc7515))
* typos in 'probably' ([6bdf7e3](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/6bdf7e30257179a2a841eaf3ef919feac49d2a4f))
* wrap db connect error ([#127](https://github.com/fabriziomello/timescaledb-parallel-copy/issues/127)) ([aacb29f](https://github.com/fabriziomello/timescaledb-parallel-copy/commit/aacb29f1bf1067b79b6842629d844c1f8419b978))
