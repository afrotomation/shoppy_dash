## 1.0.0 (2026-05-18)

### Features

* add codenalytics telemetry tracking ([926521e](https://git.afrotomation.com/afrotomation/shoppydash/commit/926521ec05e18a6a1aa8afb1bb1a010e62273a26))
* add Umami analytics tracking ([0ac65ef](https://git.afrotomation.com/afrotomation/shoppydash/commit/0ac65ef13aaa06a30f90e15d565c04a19b8b43d8))
* Coolify deployment setup ([4016e50](https://git.afrotomation.com/afrotomation/shoppydash/commit/4016e5096d795033704007c5de45f6bce7d6e3be))

### Bug Fixes

* **build:** switch to craco, drop ajv overrides that broke fork-ts-checker ([54fd5e3](https://git.afrotomation.com/afrotomation/shoppydash/commit/54fd5e3374ed1cf4302b6a49a593c97aacc95384))
* **docker:** swap public.ecr.aws -> mirror.gcr.io for base image ([6cd6bbb](https://git.afrotomation.com/afrotomation/shoppydash/commit/6cd6bbb83cb90fe52395a0d65d0436c37196e0a4))
* **docker:** Switch base images to public.ecr.aws (no Docker Hub rate limit) ([edacd84](https://git.afrotomation.com/afrotomation/shoppydash/commit/edacd84d446d62abe5ed9dfcc44a45e7ff0a5561))
* pin ajv 8 to resolve react-scripts schema-utils build error ([cbf0b00](https://git.afrotomation.com/afrotomation/shoppydash/commit/cbf0b000e00d0e7743e48f06dd98cfadbbd54753))
* set per-project analytics API key for codenalytics telemetry ([a1d76ee](https://git.afrotomation.com/afrotomation/shoppydash/commit/a1d76ee3371861af7a3d0f2e127bae814d555971))
* **styling:** production Tailwind bundle dropped to 1.3KB / 0 utilities ([9464583](https://git.afrotomation.com/afrotomation/shoppydash/commit/9464583beae7e58e38450187efa08a0c0036250d))
* upgrade schema-utils to v4 to resolve ajv-keywords mismatch ([9c5f79f](https://git.afrotomation.com/afrotomation/shoppydash/commit/9c5f79f45d495370712a4a4e6dfe1a5f652c25b1))
* use pnpm (strict resolution fixes ajv-keywords hoist) + add ej2-base dep ([0e8aa38](https://git.afrotomation.com/afrotomation/shoppydash/commit/0e8aa386781f3601308283aff3dc47a7fdbc0dc5))
