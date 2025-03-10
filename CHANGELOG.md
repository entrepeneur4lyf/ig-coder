# Changelog

All notable changes to this project will be documented in this file.

## [0.1.5](https://github.com/inference-gateway/coder/compare/0.1.4...0.1.5) (2025-02-28)

### 🐛 Bug Fixes

* **release:** Correct string concatenation for destination tagging in release workflow ([5e0c4fd](https://github.com/inference-gateway/coder/commit/5e0c4fdd1817351d6e43c6053cf0abb56ae22c1e))

## [0.1.4](https://github.com/inference-gateway/coder/compare/0.1.3...0.1.4) (2025-02-28)

### 🐛 Bug Fixes

* **docker-compose:** Update coder service image version to 0.1.3 with alpine base image ([c2d26b0](https://github.com/inference-gateway/coder/commit/c2d26b0af2a1c29fbcb616baa0162d5efc2e2662))
* **docker:** Add git and curl to the container image for enhanced functionality ([b21b49b](https://github.com/inference-gateway/coder/commit/b21b49bf98497fe52729bb6f834d9bf1cd44596f))

### 📦 Miscellaneous

* Refactor CI CD ([#25](https://github.com/inference-gateway/coder/issues/25)) ([7b35e33](https://github.com/inference-gateway/coder/commit/7b35e331f8095723e788f7a80f32d0973ef3103c))

## [0.1.4-rc.57](https://github.com/inference-gateway/coder/compare/0.1.4-rc.56...0.1.4-rc.57) (2025-02-28)

### 📦 Miscellaneous

* Add checkout step to release workflow for improved repository access ([a0841e4](https://github.com/inference-gateway/coder/commit/a0841e49b22621daaec46a0848e960f906091319))

## [0.1.4-rc.56](https://github.com/inference-gateway/coder/compare/0.1.4-rc.55...0.1.4-rc.56) (2025-02-28)

### 📦 Miscellaneous

* Add Trivy installation and Zsh completion support in devcontainer ([a6f614f](https://github.com/inference-gateway/coder/commit/a6f614f82287324886f3e3be75b008105c928081))
* Change vulnerability scan output format from template to SARIF - this is the recommended way, the other was is deprecated ([4dd728f](https://github.com/inference-gateway/coder/commit/4dd728f677a5f1983d43cd3eac0cdbbff5d76a80))
* Fix variable expansion for DESTINATIONS in release workflow ([93ed655](https://github.com/inference-gateway/coder/commit/93ed655cad9465fbbee8ecf027901a63847bd141))
* Remove upload step for vulnerability scan results in release workflow ([874aed3](https://github.com/inference-gateway/coder/commit/874aed3a27eb6741dcb8f2a75b97fcbc38f03647))
* Update permissions in release workflow to include contents and actions ([442a52e](https://github.com/inference-gateway/coder/commit/442a52ed2adf1261dd90c5bd0c343115f1ed9b65))
* Update release workflow to handle version tagging for release candidates and stable versions ([63ec837](https://github.com/inference-gateway/coder/commit/63ec837017392c52dd6fe100ac11ee4aead43d0f))
* Update vulnerability scan output format to use template ([ce7ef35](https://github.com/inference-gateway/coder/commit/ce7ef3563ff28d9860dc3a508b8f25f2cf3a91f0))

## [0.1.4-rc.55](https://github.com/inference-gateway/coder/compare/0.1.4-rc.54...0.1.4-rc.55) (2025-02-28)

### 📦 Miscellaneous

* Small fix - Update image reference format in vulnerability scanning workflow ([69f78b1](https://github.com/inference-gateway/coder/commit/69f78b17d2f905252b5a1c38145d899d26cd8f8a))

## [0.1.4-rc.54](https://github.com/inference-gateway/coder/compare/0.1.4-rc.53...0.1.4-rc.54) (2025-02-28)

### 📦 Miscellaneous

* Add container image vulnerability scanning to release workflow ([f5b0679](https://github.com/inference-gateway/coder/commit/f5b0679b5aed31404274b8140821822e6cda9cc0))
* Restore entrypoint in docker-compose.yml for service configuration ([334949a](https://github.com/inference-gateway/coder/commit/334949a2e528f936a8c8f3a3b4a54f7127bf032d))
* Update coder image and configure git user settings in docker-compose ([d0373d9](https://github.com/inference-gateway/coder/commit/d0373d990668d732197f381284641b75380bf04c))

## [0.1.4-rc.53](https://github.com/inference-gateway/coder/compare/0.1.4-rc.52...0.1.4-rc.53) (2025-02-27)

### 📦 Miscellaneous

* Try something - it's seems that they put it in public preview ([6611ad3](https://github.com/inference-gateway/coder/commit/6611ad35efea24baee66d470571512497068cbde))

## [0.1.4-rc.52](https://github.com/inference-gateway/coder/compare/0.1.4-rc.51...0.1.4-rc.52) (2025-02-27)

### 📦 Miscellaneous

* Add platform specification for multi-architecture OCI images in release workflow ([28a3a50](https://github.com/inference-gateway/coder/commit/28a3a500f31b453c36b4932e803b81ba176d19f0))
* Try to reuse the same cache entry ([eab1f71](https://github.com/inference-gateway/coder/commit/eab1f71f6b47d4eb489c0d3b72e011d8f459e496))

## [0.1.4-rc.51](https://github.com/inference-gateway/coder/compare/0.1.4-rc.50...0.1.4-rc.51) (2025-02-27)

### 📦 Miscellaneous

* Add tag aliases for image targets in release workflow ([edf8367](https://github.com/inference-gateway/coder/commit/edf836730a5010f8c721c05067b959acd2195479))
* Update Dockerfile to set USER just for installing extra dependencies and switch back to coder user ([13d7368](https://github.com/inference-gateway/coder/commit/13d7368ba3129f5eb2455fa1acb95cb9de209b3e))

## [0.1.4-rc.50](https://github.com/inference-gateway/coder/compare/0.1.4-rc.49...0.1.4-rc.50) (2025-02-27)

### 📦 Miscellaneous

* Add additional destination tag for container image in release workflow ([32fa45b](https://github.com/inference-gateway/coder/commit/32fa45b33c6bc46e554a6cf1c202a3d13572d6f2))
* Refactor release workflow to support multiple image targets and streamline image building process ([62e0931](https://github.com/inference-gateway/coder/commit/62e09315b8a343820e1477244125ef029f72f82d))
* Remove 'is_latest' flag for now, I'll build it later ([fa694d3](https://github.com/inference-gateway/coder/commit/fa694d3b0754a3306fd5cbcbf6c74fe8ffcecc73))
* Simplify container options in release workflow by removing unnecessary resource limits ([afd72be](https://github.com/inference-gateway/coder/commit/afd72be568ac73929b91236b8999250589ff45e2))

## [0.1.4-rc.49](https://github.com/inference-gateway/coder/compare/0.1.4-rc.48...0.1.4-rc.49) (2025-02-27)

### 📦 Miscellaneous

* Add dependency on build_binaries job for container image signing and building ([fa0b9d5](https://github.com/inference-gateway/coder/commit/fa0b9d5e76dacbd76e045cf8c5ed2206e90f20d3))

## [0.1.4-rc.48](https://github.com/inference-gateway/coder/compare/0.1.4-rc.47...0.1.4-rc.48) (2025-02-27)

### 🔧 Miscellaneous

* Allow specifying a version for installation, default to latest ([ca0c708](https://github.com/inference-gateway/coder/commit/ca0c7085d1e4ad255c3ae367ab0800710bdc889e))
* Allow to specify the installation version, default to latest ([be84a02](https://github.com/inference-gateway/coder/commit/be84a0219e74f87d639c96df709cd4c2ad39f35f))

### 📦 Miscellaneous

* Add Dockerfile for building release containers from GitHub binaries ([fd53df6](https://github.com/inference-gateway/coder/commit/fd53df6d3434f82db4dc81a261da7b999d7da78e))
* Add Python environment setup in Dockerfile for additional tooling ([2fdb15a](https://github.com/inference-gateway/coder/commit/2fdb15aaab98b898db16aa2abaab35db8cf74062))
* Add VERSION build argument to release workflow ([d7e768f](https://github.com/inference-gateway/coder/commit/d7e768f2a66c09debf5228a0351ec3addfaad949))
* Enhance release workflow to build and push multiple coder images for different language specific environments ([2b19a86](https://github.com/inference-gateway/coder/commit/2b19a862e134db28fd9ffd5f603d49a359570555))
* Remove commented-out configurations from release workflow ([68e4779](https://github.com/inference-gateway/coder/commit/68e4779dfc7bd2ff02dcc6994cbb5c4074a1591d))
* Remove some optimization flags, since we're just copying the binary there is no need to trade binary quality over speed, it will be fast enough ([8022d64](https://github.com/inference-gateway/coder/commit/8022d642fbcb08fb3ac8cb59cc917d50a5fdffe9))

## [0.1.4-rc.47](https://github.com/inference-gateway/coder/compare/0.1.4-rc.46...0.1.4-rc.47) (2025-02-27)

### 📦 Miscellaneous

* Add custom linkers for cross-compilation targets ([16035ec](https://github.com/inference-gateway/coder/commit/16035ec4495a02593c43466f5c6b4eaa83aaeab7))

## [0.1.4-rc.46](https://github.com/inference-gateway/coder/compare/0.1.4-rc.45...0.1.4-rc.46) (2025-02-27)

### 📦 Miscellaneous

* Comment out build and sign container jobs in release workflow - temporarily ([9d5b246](https://github.com/inference-gateway/coder/commit/9d5b24613646ef678dccdd9279a4739a520e5109))
* Go back to cross-compilation option ([2061666](https://github.com/inference-gateway/coder/commit/2061666ad40a9393fd92f1070c651ae764c1dfab))

## [0.1.4-rc.45](https://github.com/inference-gateway/coder/compare/0.1.4-rc.44...0.1.4-rc.45) (2025-02-27)

### 📦 Miscellaneous

* Bring back dependencies ([e921954](https://github.com/inference-gateway/coder/commit/e92195461950e5bef6376e8e969c611a2489bc0b))
* Rename job from 'B&P Containers' to 'Build Containers' for clarity ([822c8b2](https://github.com/inference-gateway/coder/commit/822c8b2b1584ea3edc43ecdfb49498dddd11ee95))

## [0.1.4-rc.44](https://github.com/inference-gateway/coder/compare/0.1.4-rc.43...0.1.4-rc.44) (2025-02-27)

### 📦 Miscellaneous

* I think I found the issue, those cache entries came from this action ([e55c37f](https://github.com/inference-gateway/coder/commit/e55c37f5379a8f344ad996c1e69ac413b98d7493))

## [0.1.4-rc.43](https://github.com/inference-gateway/coder/compare/0.1.4-rc.42...0.1.4-rc.43) (2025-02-27)

### 📦 Miscellaneous

* Ensure using the latest version of the this action ([8ff0605](https://github.com/inference-gateway/coder/commit/8ff0605eca4668dc04416117ad9cf35d0fbb03ff))

## [0.1.4-rc.42](https://github.com/inference-gateway/coder/compare/0.1.4-rc.41...0.1.4-rc.42) (2025-02-27)

### 📦 Miscellaneous

* Attempt to fix cache conflict ([4583568](https://github.com/inference-gateway/coder/commit/4583568de71b0e767a53f5ca0b96786a72df83e0))
* Update cache key format in release workflow for consistency ([57a55cc](https://github.com/inference-gateway/coder/commit/57a55ccf07b5cd8dd3b07f174b8c425c0a7f40f1))

## [0.1.4-rc.41](https://github.com/inference-gateway/coder/compare/0.1.4-rc.40...0.1.4-rc.41) (2025-02-27)

### 📦 Miscellaneous

* Adjust cache key format in release workflow for improved consistency ([2b8be73](https://github.com/inference-gateway/coder/commit/2b8be7302ab7c5a5682e55db8d2a1c4e6f0cd331))

## [0.1.4-rc.40](https://github.com/inference-gateway/coder/compare/0.1.4-rc.39...0.1.4-rc.40) (2025-02-27)

### 📦 Miscellaneous

* Comment out self-hosted runners for now - I want to make sure it works on the regular github ones first ([ddb31d6](https://github.com/inference-gateway/coder/commit/ddb31d6fa88f1329cf90bb9b44fb319a86fd7305))
* This is default for the sake of consistency with release workflow add it explicitly ([c226efd](https://github.com/inference-gateway/coder/commit/c226efd0f85e3a6d7045778496a32a37f7f6899a))
* Uncomment and enable static binary build steps in CI workflow ([b53889f](https://github.com/inference-gateway/coder/commit/b53889fa8267fd3a79da4690969553715c8618fa))
* Update Rust toolchain setup action to version 1.11.0 ([79d3237](https://github.com/inference-gateway/coder/commit/79d3237c78dc82abb07196b9c6cdf5fd2b5acdaa))

## [0.1.4-rc.39](https://github.com/inference-gateway/coder/compare/0.1.4-rc.38...0.1.4-rc.39) (2025-02-27)

### 📦 Miscellaneous

* Add image pulling step before signing container images in release workflow ([d3068ec](https://github.com/inference-gateway/coder/commit/d3068ecd8b119bc734f1a61127bfbe8fd637f72c))
* Add Rust toolchain setup and update checkout step in CI workflow ([8698c7f](https://github.com/inference-gateway/coder/commit/8698c7faec6b8f4d147e9ea1c7ef77ebd454b726))
* Update uuid dependency to version 1.15.1 ([3b5cc33](https://github.com/inference-gateway/coder/commit/3b5cc33f2a02cedb6e0dd2836bbb49b9be148307))

## [0.1.4-rc.38](https://github.com/inference-gateway/coder/compare/0.1.4-rc.37...0.1.4-rc.38) (2025-02-27)

### 📦 Miscellaneous

* Enhance GitHub Actions workflow for container signing and caching ([0aa9428](https://github.com/inference-gateway/coder/commit/0aa9428edbf477024e042919abe2fee4ceb7d130))
* Iterate faster on the release workflow - temporarily ([7615d06](https://github.com/inference-gateway/coder/commit/7615d061283f1f1e50e8788ccb9371a0d9af68ce))

## [0.1.4-rc.37](https://github.com/inference-gateway/coder/compare/0.1.4-rc.36...0.1.4-rc.37) (2025-02-26)

### 📦 Miscellaneous

* Add workflow step to sign container images with GitHub OIDC ([a8f6296](https://github.com/inference-gateway/coder/commit/a8f629609bbec47e645db0ac47a6acde1483ebc6))
* Import CommandFactory for optional completions feature ([05ce42a](https://github.com/inference-gateway/coder/commit/05ce42ae118873bd8ff47d470c145595cbb58ca1))
* Increase timeout for B&P Containers job in release workflow ([bbee100](https://github.com/inference-gateway/coder/commit/bbee100d993d2aab9353f16ce1b063cf2e26210c))
* Remove unnecessary image creation label from release workflow - it revalidating the cache on each run ([3abdba0](https://github.com/inference-gateway/coder/commit/3abdba05e967435573662996bf7c7c6ff7601703))
* Simplify Dockerfile by removing cache mounts from cargo commands ([72a5c91](https://github.com/inference-gateway/coder/commit/72a5c91dc2b47de06f48d1b469a6e4b39082d7aa))
* Update release workflow and Taskfile for improved cached container build process ([c78b91c](https://github.com/inference-gateway/coder/commit/c78b91c1053e9de07fa6d334c7b30384d9ba7b3b))
* Use consistent style ([f0aa8e8](https://github.com/inference-gateway/coder/commit/f0aa8e8f8c75949503715b9017786242a075b0cc))

## [0.1.4-rc.36](https://github.com/inference-gateway/coder/compare/0.1.4-rc.35...0.1.4-rc.36) (2025-02-26)

### 📦 Miscellaneous

* Add optional shell completions feature using clap_complete ([0fcaca0](https://github.com/inference-gateway/coder/commit/0fcaca0d92a1c76f0416645546ddcbfeba34d423))
* Update uuid dependency to version 1.15.0 ([5d61147](https://github.com/inference-gateway/coder/commit/5d6114772a32f70b6058915be72dc70be3e4607c))

## [0.1.4-rc.35](https://github.com/inference-gateway/coder/compare/0.1.4-rc.34...0.1.4-rc.35) (2025-02-26)

### ⚡️ Improvements

* Add release task for local Docker container execution so I can test the release ([8a00250](https://github.com/inference-gateway/coder/commit/8a00250416affd07daf5380970a09df3617b5138))

### 🔧 Miscellaneous

* Update dependencies to latest versions and optimize release profile settings ([97b7009](https://github.com/inference-gateway/coder/commit/97b700900a38c8589118e44524c39b4223749aa0))

### 📦 Miscellaneous

* Add missing flags, not sure yet why kaniko is not saving into the local cache ([cca01e2](https://github.com/inference-gateway/coder/commit/cca01e22eefa535785962d63325eb751e8637ff6))
* Attempt to fix caching ([572d0f9](https://github.com/inference-gateway/coder/commit/572d0f9237e037445ef511fc8d118c1c38275ce7))
* Create /app directory in Dockerfile for application workspace ([82d6449](https://github.com/inference-gateway/coder/commit/82d64497755b2afd478c0498e04e31ed4adf7e15))
* Enhance caching strategy in release workflow and Taskfile with compressed caching and snapshot mode ([59857fd](https://github.com/inference-gateway/coder/commit/59857fdd133597b8b86e9aefbe0006da62c39f66))
* Import TARGET_ARCH argument to the chef layer in the Dockerfile ([24463ec](https://github.com/inference-gateway/coder/commit/24463ec09d37fd5341b9b8edda0fb8c63e616a26))
* Increase verbosity of cargo build command in Dockerfile ([dcd030c](https://github.com/inference-gateway/coder/commit/dcd030c6857f947125081b209c26cafcbf417e19))
* Install Dive to better analyse caching layers ([a19249c](https://github.com/inference-gateway/coder/commit/a19249ca0aa98755dd0b31cd0db73a88be0e04d6))
* Optimize cargo build command to utilize all available jobs for improved performance,  I think it's default behaviour but I'm not entirely sure ([fd4f9f4](https://github.com/inference-gateway/coder/commit/fd4f9f48740a05e0094511847814d8c080b66ff3))
* Optimize Dockerfile by adding cache mounts for improved build performance ([22d8196](https://github.com/inference-gateway/coder/commit/22d81962209fe3008ec91f55512cd2e6c2b557c8))
* Remove redundant cache cleanup commands from Dockerfile because --no-cache is already in use ([f05cd51](https://github.com/inference-gateway/coder/commit/f05cd511a514cfe21686e6ab8637979d551f00c9))
* Remove unnecessary target-specific rustflags for aarch64 ([dd3bc44](https://github.com/inference-gateway/coder/commit/dd3bc44fd00d06430feb047577bb99ffbd65fa5e))
* Update Kaniko context to local directory for improved build process ([e447ca3](https://github.com/inference-gateway/coder/commit/e447ca3b70717a3d5854b57841b15cfbfb6ef699))
* Update Zsh configuration to include additional right prompt elements like execution time etc ([bceb4b4](https://github.com/inference-gateway/coder/commit/bceb4b48314d54c7b888bd43fb999edf40e70530))

## [0.1.4-rc.34](https://github.com/inference-gateway/coder/compare/0.1.4-rc.33...0.1.4-rc.34) (2025-02-24)

### ♻️ Improvements

* Ensure caching in a separate layer ([04f3efb](https://github.com/inference-gateway/coder/commit/04f3efbb40040cf1faca92f8f1102bd1d4dc135d))

## [0.1.4-rc.33](https://github.com/inference-gateway/coder/compare/0.1.4-rc.32...0.1.4-rc.33) (2025-02-23)

### 👷 CI

* Update codegen units in Cargo.toml for improved optimization ([9c5a5d0](https://github.com/inference-gateway/coder/commit/9c5a5d01b511b2d73cb3b417239290d445e89911))

## [0.1.4-rc.32](https://github.com/inference-gateway/coder/compare/0.1.4-rc.31...0.1.4-rc.32) (2025-02-23)

### 👷 CI

* Update cache repository path and TTL in release workflow and reduce build jobs to 3 cores ([393aa75](https://github.com/inference-gateway/coder/commit/393aa751727f2d628a525887c38adac9ad9692b7))

## [0.1.4-rc.31](https://github.com/inference-gateway/coder/compare/0.1.4-rc.30...0.1.4-rc.31) (2025-02-23)

### 👷 CI

* Increase timeout for B&P Containers job to 45 minutes - temporarily ([165ea13](https://github.com/inference-gateway/coder/commit/165ea13371f7952bcd3e6ec7aa07c96bb76f14d8))
* Update Kaniko executor options for resource allocation and adjust Rust codegen units ([2878a6d](https://github.com/inference-gateway/coder/commit/2878a6dba5643ba71163aeab39cf08293c3feb56))

## [0.1.4-rc.30](https://github.com/inference-gateway/coder/compare/0.1.4-rc.29...0.1.4-rc.30) (2025-02-23)

### 👷 CI

* Remove commented out old workflow ([6dd043f](https://github.com/inference-gateway/coder/commit/6dd043f7e0702b40969601a1ff4fb93c8af86089))
* Remove metadata fetching step and add image labels manually ([7a3aeea](https://github.com/inference-gateway/coder/commit/7a3aeea25dafcc2712374438b4e8bcad65fc66d9))

### 🔧 Miscellaneous

* update dependencies to latest versions ([13a56b8](https://github.com/inference-gateway/coder/commit/13a56b8456ece9de4ea3af3a079ed76e21597e78))

## [0.1.4-rc.29](https://github.com/inference-gateway/coder/compare/0.1.4-rc.28...0.1.4-rc.29) (2025-02-20)

### 👷 CI

* Comment out metadata fetching step in release workflow ([9ee3a7a](https://github.com/inference-gateway/coder/commit/9ee3a7a851ce20d1acfb0a5f7d385a345029974c))

## [0.1.4-rc.28](https://github.com/inference-gateway/coder/compare/0.1.4-rc.27...0.1.4-rc.28) (2025-02-20)

### 👷 CI

* Interesting, so I guess it was the debug tag that I need, it contains the tail utility and some other basic ones, will keep it like that then ([7eb50ad](https://github.com/inference-gateway/coder/commit/7eb50ad4bf5ee49fa0f1b9b859d4f75750fb41a1))

## [0.1.4-rc.27](https://github.com/inference-gateway/coder/compare/0.1.4-rc.26...0.1.4-rc.27) (2025-02-20)

### 👷 CI

* Ok doesn't seems to like it ([bab6254](https://github.com/inference-gateway/coder/commit/bab62548407fb69c58c3910a7de3719a9dedc360))

## [0.1.4-rc.26](https://github.com/inference-gateway/coder/compare/0.1.4-rc.25...0.1.4-rc.26) (2025-02-20)

### 👷 CI

* Add metadata fetching step for container build in release workflow ([ff6cb52](https://github.com/inference-gateway/coder/commit/ff6cb5268920bfc08bc2142cc742eb77e2dd3a44))
* Enable Ubuntu 24.04 with x86_64 target in release workflow ([206598b](https://github.com/inference-gateway/coder/commit/206598bf22bfecf68dfb74971ab4c724e99a81a1))
* Increase timeout for B&P Containers job in release workflow ([ada0abd](https://github.com/inference-gateway/coder/commit/ada0abd2a1c6eaf3d9ba76b51f4ba57415b20ee9))
* Refactor Dockerfile to optimize build process with cargo-chef and add Python based coder environment ([30f17d1](https://github.com/inference-gateway/coder/commit/30f17d185266c91a0fbe44926a78c2fc37067bb2))
* Update Kaniko executor image to v1.23.2 in release workflow, remove debug ([6dc165c](https://github.com/inference-gateway/coder/commit/6dc165ccdd03879c676738d7199710a88b792ba5))

### 🔧 Miscellaneous

* **dockerfile:** Format Dockerfile for improved readability and consistency ([aa5bf99](https://github.com/inference-gateway/coder/commit/aa5bf99dd500a411c0acb71de34ccd186b9c5801))
* Ensure proper newline at end of Dockerfile for consistency ([20d85ba](https://github.com/inference-gateway/coder/commit/20d85bad1101577ea463347a210f81104ae89575))

## [0.1.4-rc.25](https://github.com/inference-gateway/coder/compare/0.1.4-rc.24...0.1.4-rc.25) (2025-02-19)

### 👷 CI

* Small fix - forgot the $ sign ([420e3e4](https://github.com/inference-gateway/coder/commit/420e3e4108ac73a06da79a15edc17e2630b2fabe))

## [0.1.4-rc.24](https://github.com/inference-gateway/coder/compare/0.1.4-rc.23...0.1.4-rc.24) (2025-02-19)

### 👷 CI

* Clean up release workflow by removing commented-out steps and simplifying context for Kaniko build - always take the latest of the ref ([9d50606](https://github.com/inference-gateway/coder/commit/9d5060645016547e9019097341e5634661c41a54))
* Refactor Kaniko build step and Dockerfile for improved environment variable usage and caching ([c3c5296](https://github.com/inference-gateway/coder/commit/c3c5296cdba356ef8661fe072d34811fc0946337))

## [0.1.4-rc.23](https://github.com/inference-gateway/coder/compare/0.1.4-rc.22...0.1.4-rc.23) (2025-02-19)

### 👷 CI

* Simplify Dockerfile path in Kaniko executor configuration - it's at the root of the repo ([9739fc2](https://github.com/inference-gateway/coder/commit/9739fc2773a34e3279ff71c0cd1ea8a1247df610))

## [0.1.4-rc.22](https://github.com/inference-gateway/coder/compare/0.1.4-rc.21...0.1.4-rc.22) (2025-02-19)

### 👷 CI

* Test something - kaniko suppose to fetch the repo and build ([7e65385](https://github.com/inference-gateway/coder/commit/7e653852461f7de06485efb3d28a6cb8f7fd5b86))

## [0.1.4-rc.21](https://github.com/inference-gateway/coder/compare/0.1.4-rc.20...0.1.4-rc.21) (2025-02-19)

### 👷 CI

* Remove explicit verbosity, use default ([5028cff](https://github.com/inference-gateway/coder/commit/5028cffb5049826ef1a873297a80c166e614ae73))
* Update Kaniko executor image to use debug version for troubleshooting ([fee3e2d](https://github.com/inference-gateway/coder/commit/fee3e2db285a48f3deb87ee3a46ef36726ca2daf))

## [0.1.4-rc.20](https://github.com/inference-gateway/coder/compare/0.1.4-rc.19...0.1.4-rc.20) (2025-02-19)

### 👷 CI

* Update container image in release workflow to use Kaniko executor ([d10ac77](https://github.com/inference-gateway/coder/commit/d10ac77fb4f62e04cfcda03aa98b69bea71bbf01))
* Use directly the container image kaniko and execute the kaniko binary to build an OCI and push it to the container registry ([68e6474](https://github.com/inference-gateway/coder/commit/68e64745475a57fa85e44699470a1ea7b1310086))

## [0.1.4-rc.19](https://github.com/inference-gateway/coder/compare/0.1.4-rc.18...0.1.4-rc.19) (2025-02-19)

### 👷 CI

* Reduce the reliance on docker ([1a1ee02](https://github.com/inference-gateway/coder/commit/1a1ee029516eefdda4b6d39d233483b9b4df0d56))

## [0.1.4-rc.18](https://github.com/inference-gateway/coder/compare/0.1.4-rc.17...0.1.4-rc.18) (2025-02-19)

### 👷 CI

* Small fix - update container syntax in release workflow to use proper image format ([5c44837](https://github.com/inference-gateway/coder/commit/5c448376d45b35f080345c5ac26dcafc665aa407))

## [0.1.4-rc.17](https://github.com/inference-gateway/coder/compare/0.1.4-rc.16...0.1.4-rc.17) (2025-02-19)

### 👷 CI

* Update release workflow to use Ubuntu 24.04 container and adjust matrix configuration ([20ffe22](https://github.com/inference-gateway/coder/commit/20ffe2257497873935f8e685515cb0ec54f869dd))

## [0.1.4-rc.16](https://github.com/inference-gateway/coder/compare/0.1.4-rc.15...0.1.4-rc.16) (2025-02-19)

### 👷 CI

* Test the same job in Kubernetes ([ac38ae3](https://github.com/inference-gateway/coder/commit/ac38ae3e1cfe8e903be8da82e88599cf38d86dea))

### 🔧 Miscellaneous

* **cleanup:** Cleanup, those labels are redundant because they now fetched from action metadata directly from github repo ([1c2415f](https://github.com/inference-gateway/coder/commit/1c2415fca8ce03b30b1cbf2909147839fdd0f417))

## [0.1.4-rc.15](https://github.com/inference-gateway/coder/compare/0.1.4-rc.14...0.1.4-rc.15) (2025-02-19)

### 👷 CI

* Update release workflow to use a different action also for kaniko, maybe this one is better maintained ([829616f](https://github.com/inference-gateway/coder/commit/829616fe0619a66f13b5dbeb7db5bf48d63373b3))

## [0.1.4-rc.14](https://github.com/inference-gateway/coder/compare/0.1.4-rc.13...0.1.4-rc.14) (2025-02-19)

### 👷 CI

* Fix syntax for build-arg in release workflow ([0dd8dbf](https://github.com/inference-gateway/coder/commit/0dd8dbf095386cd2da1374af0e3e2b13348965b9))

## [0.1.4-rc.13](https://github.com/inference-gateway/coder/compare/0.1.4-rc.12...0.1.4-rc.13) (2025-02-19)

### 👷 CI

* Fix it was targeting the wrong architecture, the option build-args doesn't seems to be available in this Github Action ([b236b67](https://github.com/inference-gateway/coder/commit/b236b6757f17fb368e463deb4b394c2b55b94e3d))

### 🔧 Miscellaneous

* Add GitHub Actions extension to devcontainer configuration ([68eb13b](https://github.com/inference-gateway/coder/commit/68eb13bf3ca6f05128585ac4ab4285404df64d17))

## [0.1.4-rc.12](https://github.com/inference-gateway/coder/compare/0.1.4-rc.11...0.1.4-rc.12) (2025-02-19)

### 👷 CI

* Update release workflow to use Kaniko action for building and pushing images ([0a9787b](https://github.com/inference-gateway/coder/commit/0a9787bbdb5f1bc3ff50ee071d791a2b9bd3cd21))

### 🔧 Miscellaneous

* Resort dev containers dependencies ([af95d59](https://github.com/inference-gateway/coder/commit/af95d592f219eae690f065723f2e56f0a8039c5b))

## [0.1.4-rc.11](https://github.com/inference-gateway/coder/compare/0.1.4-rc.10...0.1.4-rc.11) (2025-02-19)

### 👷 CI

* Comment out temporarily the other runner, just to see if it works as expected ([a01a790](https://github.com/inference-gateway/coder/commit/a01a790fa3152e29cfd67075bd3ac01439ebd077))
* Update release workflow to use Kaniko for building and pushing OCI images ([6a2b930](https://github.com/inference-gateway/coder/commit/6a2b930918b30b353f552e63c75c8424d5e2cef6))

## [0.1.4-rc.10](https://github.com/inference-gateway/coder/compare/0.1.4-rc.9...0.1.4-rc.10) (2025-02-19)

### 👷 CI

* Optimize Dockerfile by removing redundant apk update commands ([3756ab1](https://github.com/inference-gateway/coder/commit/3756ab1cb406fb901662bfad70a121660e9eaa0b))

## [0.1.4-rc.9](https://github.com/inference-gateway/coder/compare/0.1.4-rc.8...0.1.4-rc.9) (2025-02-19)

### 👷 CI

* Update Dockerfile to use rust:alpine as base image and streamline build process ([8f02226](https://github.com/inference-gateway/coder/commit/8f022262d03d8e677f451e239056314e26b6cd5c))

## [0.1.4-rc.8](https://github.com/inference-gateway/coder/compare/0.1.4-rc.7...0.1.4-rc.8) (2025-02-19)

### 👷 CI

* Increase timeout for B&P Containers job in release workflow ([8568c67](https://github.com/inference-gateway/coder/commit/8568c6744340b52f46543298a973c04e0f945e26))

## [0.1.4-rc.7](https://github.com/inference-gateway/coder/compare/0.1.4-rc.6...0.1.4-rc.7) (2025-02-19)

### 👷 CI

* Add k8s to the list of OS options in release workflow ([3422a9f](https://github.com/inference-gateway/coder/commit/3422a9fcb82382aa578395006e443a6aa57a5fe6))

## [0.1.4-rc.6](https://github.com/inference-gateway/coder/compare/0.1.4-rc.5...0.1.4-rc.6) (2025-02-17)

### 👷 CI

* Comment out QEMU setup step in release workflow ([4a09c1a](https://github.com/inference-gateway/coder/commit/4a09c1a2d5c3a7d441c65d2ba7bff8ecc184a0ce))
* Comment out temporarily build_binaries job in release workflow to speed things up ([4d00ad3](https://github.com/inference-gateway/coder/commit/4d00ad3ecd9644b57a2218030681c99a87b3c416))
* Remove conditional check for minimal variant in B&P Minimal Container job ([ca6f85f](https://github.com/inference-gateway/coder/commit/ca6f85fc5ba7d85c13f113c15709b832ded25615))
* Rename build_container job to build_containers and update commented job name ([1bdf885](https://github.com/inference-gateway/coder/commit/1bdf885cd539045a0cdf816d5672b021bb575c3b))
* Split language specific containers with tools to a separate job and comment it out ([fd20e5b](https://github.com/inference-gateway/coder/commit/fd20e5b0c5e6781706222b59bd99c268ea441a35))

## [0.1.4-rc.5](https://github.com/inference-gateway/coder/compare/0.1.4-rc.4...0.1.4-rc.5) (2025-02-17)

### 👷 CI

* Comment out Build and Push Rust Container job in release workflow ([8e8af76](https://github.com/inference-gateway/coder/commit/8e8af765f3d6506891a4482eafbef0bd557e419b))

## [0.1.4-rc.4](https://github.com/inference-gateway/coder/compare/0.1.4-rc.3...0.1.4-rc.4) (2025-02-17)

### 👷 CI

* Update release workflow to handle macOS builds separately ([d242dce](https://github.com/inference-gateway/coder/commit/d242dce5f5032754271e85fa9f487a4efe7b8037))
* Update release workflow to include ubuntu-22.04-arm64 in self-hosted jobs ([74429be](https://github.com/inference-gateway/coder/commit/74429be18ee3401e6e23920c70c985d388ff9a7e))

## [0.1.4-rc.3](https://github.com/inference-gateway/coder/compare/0.1.4-rc.2...0.1.4-rc.3) (2025-02-17)

### 👷 CI

* Change ARM64 jobs to use self-hosted runners in release workflow ([274d375](https://github.com/inference-gateway/coder/commit/274d375bdb2d888de200706001e50986600e4919))

## [0.1.4-rc.2](https://github.com/inference-gateway/coder/compare/0.1.4-rc.1...0.1.4-rc.2) (2025-02-16)

### ♻️ Improvements

* Update Dockerfile and CI workflow to use clang and llvm for cross-compilation ([c0cf8d3](https://github.com/inference-gateway/coder/commit/c0cf8d3fa99a87f09758232f7b99c094f95e3abb))

### 👷 CI

* Increase timeout for B&P Containers job to 65 minutes ([c90a1f4](https://github.com/inference-gateway/coder/commit/c90a1f46005328045e6020237969608bf3cc04de))
* Make the Build and Push job name shorter ([a41ed31](https://github.com/inference-gateway/coder/commit/a41ed31b16c3848082859127c1f1f955442120d8))
* Reduce timeout for B&P Containers job from 65 to 15 minutes ([f610944](https://github.com/inference-gateway/coder/commit/f6109443895e59249226061aa62ea5645b99677c))
* Update Ubuntu version in release workflow to 24.04 and add arm64 runner ([41e2c5f](https://github.com/inference-gateway/coder/commit/41e2c5fa2baa3eb4042697cd036a302d07fa3f84))

## [0.1.4-rc.1](https://github.com/inference-gateway/coder/compare/0.1.3...0.1.4-rc.1) (2025-02-16)

### ♻️ Improvements

* **docker:** Simplify Dockerfile and update build process with Alpine base image ([ccf6275](https://github.com/inference-gateway/coder/commit/ccf627589983850cd1937ba33266b742fff41afa))

### 🐛 Bug Fixes

* **docker-compose:** Update coder service image version to 0.1.3 with alpine base image ([c2d26b0](https://github.com/inference-gateway/coder/commit/c2d26b0af2a1c29fbcb616baa0162d5efc2e2662))
* **docker:** Add git and curl to the container image for enhanced functionality ([b21b49b](https://github.com/inference-gateway/coder/commit/b21b49bf98497fe52729bb6f834d9bf1cd44596f))

### 👷 CI

* Enhance GitHub Actions workflow for building and pushing Docker containers with Rust tools support and minimal ones ([3a50346](https://github.com/inference-gateway/coder/commit/3a5034662619017c5bb7a3fa9419b23ae4081320))

## [0.1.3](https://github.com/inference-gateway/coder/compare/0.1.2...0.1.3) (2025-02-15)

### 🐛 Bug Fixes

* **docker-compose:** Clean up entrypoint and update service names in docker-compose.yml ([8c3fa07](https://github.com/inference-gateway/coder/commit/8c3fa070698ffc36a96033c12c0a7116f00aa38a))
* **docker:** Replace distroless final base image with Alpine and update user permissions ([123c932](https://github.com/inference-gateway/coder/commit/123c932afd5fbf416d583dbc37b42e2ac99e3893))

### 📚 Documentation

* Create example for docker compose ([#22](https://github.com/inference-gateway/coder/issues/22)) ([f3466c9](https://github.com/inference-gateway/coder/commit/f3466c9ca96f5fd2c50643be0ac36aff99e4e497))

### 🔧 Miscellaneous

* **docker-compose:** Resort the services - put the important ones at the top ([a6338c0](https://github.com/inference-gateway/coder/commit/a6338c0205e884955a8b801f5ff663ee02469a80))
* **docker-compose:** Update inference gateway URL and adjust user permissions in docker-compose ([e356343](https://github.com/inference-gateway/coder/commit/e356343add4dc19c3b2f6f869e3b2579630174e1))
* **docker:** Add TODOs for base image replacement and rethink distroless choice ([91b9fe3](https://github.com/inference-gateway/coder/commit/91b9fe346fab2bf06974c49d24f65e0ca9b1d7bf))

## [0.1.2](https://github.com/inference-gateway/coder/compare/0.1.1...0.1.2) (2025-02-14)

### 📚 Documentation

* Add Docker section to table of contents in README.md ([67195c1](https://github.com/inference-gateway/coder/commit/67195c1528c19967ef8c99507bb5ea1fc0213d0a))
* Add Docker usage instructions and update configuration section in README.md ([102e371](https://github.com/inference-gateway/coder/commit/102e371fb15e6f7d6a7a4cc28611f376a7f444c4))
* Add example configuration for AI Coder in README.md ([1725372](https://github.com/inference-gateway/coder/commit/1725372119214c50e30ae58006a2797b844ebeba))
* Correct container weight description in README.md ([ce68686](https://github.com/inference-gateway/coder/commit/ce68686860bb69c3151a3bacd01e1369b970b644))
* Simplify configuration section in README.md for clarity and consistency ([8b834ba](https://github.com/inference-gateway/coder/commit/8b834baee410ce0d0cfb1ccb9160f14cf8a9c4c9))

### 🔧 Miscellaneous

* Add environment variables ([#20](https://github.com/inference-gateway/coder/issues/20)) ([ef292f1](https://github.com/inference-gateway/coder/commit/ef292f1f33d06eb0cc3fdcf8d2daa56d0c61929a))
* Add version information to CLI command ([#21](https://github.com/inference-gateway/coder/issues/21)) ([f86f0cc](https://github.com/inference-gateway/coder/commit/f86f0cc5bc38db1534ae1435cf4418da5af6ce77))

### ✅ Miscellaneous

* Add serial test attribute to ensure test execution order ([c6ac947](https://github.com/inference-gateway/coder/commit/c6ac947f08a61732e6e29bf812e8083247d9566f))

## [0.1.1](https://github.com/inference-gateway/coder/compare/0.1.0...0.1.1) (2025-02-14)

### 🐛 Bug Fixes

* Small fix ([fcede59](https://github.com/inference-gateway/coder/commit/fcede59f85a351e4baf6b23a32163c80e4766629))

### 👷 CI

* Add architecture platform support for Docker builds in release workflow ([7fe71aa](https://github.com/inference-gateway/coder/commit/7fe71aa1c5b4fa14c8bde6d8d0df730138e5c5f6))
* Add Cargo configuration for musl targets with static linking ([6b647e9](https://github.com/inference-gateway/coder/commit/6b647e9c3989dde9b27f2571df0fcc4396d82e95))
* Add conditional setup for QEMU and Docker Buildx only for Ubuntu ([6d29255](https://github.com/inference-gateway/coder/commit/6d292551d0b9eafeb30b812d383f93c025e70004))
* Adjust timeouts for cross-compilation jobs in release workflow ([4f5d9c8](https://github.com/inference-gateway/coder/commit/4f5d9c87405ffd081096d392fdbca2bfa1646770))
* Construct cache key to include with target in release workflow ([f74ac8f](https://github.com/inference-gateway/coder/commit/f74ac8f8d031b62bc747558a08106eb1f7ec8c8f))
* Improve release process publish binaries and containers for all common platforms ([1c7637b](https://github.com/inference-gateway/coder/commit/1c7637be91bfe2f4704971af0777b9fc2e1d3cdc))
* Increase timeout for Build and Upload Artifacts job to 25 minutes ([0b328b6](https://github.com/inference-gateway/coder/commit/0b328b6b9b7d1eb8ebf6f2690e50b0d64fcd7671))
* Ok this setup works if I try to cross compile from macos arm64 to x86 so it supposed to also work the other way from the runner ([c7d05cc](https://github.com/inference-gateway/coder/commit/c7d05cc6f2313f2a6e327fe68e699cd657da43c0))
* Remove commented-out debug flag from release workflow ([d9c9605](https://github.com/inference-gateway/coder/commit/d9c9605bc8d348849a78538145b0c36303293b2e))
* Set timeout for Build and Upload Artifacts job to 15 minutes ([5623c32](https://github.com/inference-gateway/coder/commit/5623c321d88ad6d6ac303e577d054cd0f22a0685))
* Set up QEMU and Docker Buildx for using emulations ([96b9815](https://github.com/inference-gateway/coder/commit/96b981537cc71866197163efc9e5eb21a1439d02))
* Simplify it cache the current pwd and enter it after download ([919427d](https://github.com/inference-gateway/coder/commit/919427dec879990e705f8da8b6f05cfbeb323856))
* Some cleanups ([6fdb00f](https://github.com/inference-gateway/coder/commit/6fdb00f817207588679376a029bb4590646e8dba))
* Try to specify explicitly buildx ([91b4ee9](https://github.com/inference-gateway/coder/commit/91b4ee92f589c1773844956b52ca00ea71227216))
* Update cross-compilation setup for musl targets and improve build tools installation ([2ea56e4](https://github.com/inference-gateway/coder/commit/2ea56e45db9e06713049d10d7d4f00d9d4cd5996))
* Update docker/build-push-action to version 6 in release workflow ([50e2c81](https://github.com/inference-gateway/coder/commit/50e2c8125973e1327b9e13558621d63b1c6c3ec8))
* Update Dockerfile to use Ubuntu base and install necessary dependencies for Rust cross-compilation ([969aab0](https://github.com/inference-gateway/coder/commit/969aab0a1c3b4e8517a4e01b831508cb908e94c8))
* Update PATH for cross-compilation to include necessary binaries ([a43b632](https://github.com/inference-gateway/coder/commit/a43b632d11eb30e7a10644bfca1cf08689cac6f0))
* Update release workflow to use docker/build-push-action for building and pushing containers ([091c454](https://github.com/inference-gateway/coder/commit/091c454f1491afc5f1636f45cfdcf9ed968a242c))
* Update target from x86_64-unknown-linux-gnu to x86_64-unknown-linux-musl in release workflow ([f351ce2](https://github.com/inference-gateway/coder/commit/f351ce27a0a617837032cc2d22c247016950519f))
* Use sudo for apt-get commands in release workflow for musl target ([904f418](https://github.com/inference-gateway/coder/commit/904f418fb8c701e298f92d483060609acd5fa4bd))
* Use sudo for cleanup and moving musl cross-compilation tools in release workflow ([3dd974f](https://github.com/inference-gateway/coder/commit/3dd974fb8f33f13baecb79dbd7d145a10532d74d))

### 🔧 Miscellaneous

* **release:** 🔖 0.1.1-rc.1 [skip ci] ([c19ec65](https://github.com/inference-gateway/coder/commit/c19ec657aa74d9cf80938fe36c10fe7f24d0cf0a))
* **release:** 🔖 0.1.1-rc.10 [skip ci] ([fda3dd3](https://github.com/inference-gateway/coder/commit/fda3dd305d7ee37e0a673289ae4fa7f7767d3605))
* **release:** 🔖 0.1.1-rc.11 [skip ci] ([71b52d9](https://github.com/inference-gateway/coder/commit/71b52d9b9dc09bf8274c62ee854b81645ce47054))
* **release:** 🔖 0.1.1-rc.12 [skip ci] ([3064dad](https://github.com/inference-gateway/coder/commit/3064dad729aef94219b5558c9455ca439c0e11de))
* **release:** 🔖 0.1.1-rc.13 [skip ci] ([0821ce5](https://github.com/inference-gateway/coder/commit/0821ce5cda3318050ea9225215e10be8b6c611ff))
* **release:** 🔖 0.1.1-rc.14 [skip ci] ([1a840a0](https://github.com/inference-gateway/coder/commit/1a840a07c47181e3d4a886ccd184125791569e19))
* **release:** 🔖 0.1.1-rc.15 [skip ci] ([eae8ff3](https://github.com/inference-gateway/coder/commit/eae8ff33249740bd752abc67a7b6cf4a59969209))
* **release:** 🔖 0.1.1-rc.16 [skip ci] ([876c48d](https://github.com/inference-gateway/coder/commit/876c48dbfb1b69d45bc769c81ad817152a54cd58))
* **release:** 🔖 0.1.1-rc.2 [skip ci] ([d749cac](https://github.com/inference-gateway/coder/commit/d749cac352feb0d78695acd6da562c2ac6d0a92c))
* **release:** 🔖 0.1.1-rc.3 [skip ci] ([2de1fca](https://github.com/inference-gateway/coder/commit/2de1fcaa425e50730882c2914cb475b78d4b73ae))
* **release:** 🔖 0.1.1-rc.4 [skip ci] ([3a17396](https://github.com/inference-gateway/coder/commit/3a173960f2b85da8d4299b5b6e8ac7bc4a03b058))
* **release:** 🔖 0.1.1-rc.5 [skip ci] ([7b4821b](https://github.com/inference-gateway/coder/commit/7b4821ba6a9d488227d30beaa6bf81707f83b8c1))
* **release:** 🔖 0.1.1-rc.6 [skip ci] ([2370f0f](https://github.com/inference-gateway/coder/commit/2370f0f95cab7ebfa17b38114db5feaded673a77))
* **release:** 🔖 0.1.1-rc.7 [skip ci] ([33948a3](https://github.com/inference-gateway/coder/commit/33948a35c69315f9709c3d70a89a9339455d5cdd))
* **release:** 🔖 0.1.1-rc.8 [skip ci] ([31598f4](https://github.com/inference-gateway/coder/commit/31598f414828479efc323046cccff3fd6a8d1dda))
* **release:** 🔖 0.1.1-rc.9 [skip ci] ([df458d9](https://github.com/inference-gateway/coder/commit/df458d9b14dff528f7d45306b2d14dd299a591fb))
* Use a separate command for cargo to ensure workspace directory is restored ([22234d6](https://github.com/inference-gateway/coder/commit/22234d6a89d89bcc153bdb00c3632f6fe2873dc0))

## [0.1.1-rc.16](https://github.com/inference-gateway/coder/compare/0.1.1-rc.15...0.1.1-rc.16) (2025-02-14)

### 👷 CI

* Adjust timeouts for cross-compilation jobs in release workflow ([4f5d9c8](https://github.com/inference-gateway/coder/commit/4f5d9c87405ffd081096d392fdbca2bfa1646770))

## [0.1.1-rc.15](https://github.com/inference-gateway/coder/compare/0.1.1-rc.14...0.1.1-rc.15) (2025-02-14)

### 👷 CI

* Add Cargo configuration for musl targets with static linking ([6b647e9](https://github.com/inference-gateway/coder/commit/6b647e9c3989dde9b27f2571df0fcc4396d82e95))

## [0.1.1-rc.14](https://github.com/inference-gateway/coder/compare/0.1.1-rc.13...0.1.1-rc.14) (2025-02-13)

### 👷 CI

* Use sudo for cleanup and moving musl cross-compilation tools in release workflow ([3dd974f](https://github.com/inference-gateway/coder/commit/3dd974fb8f33f13baecb79dbd7d145a10532d74d))

## [0.1.1-rc.13](https://github.com/inference-gateway/coder/compare/0.1.1-rc.12...0.1.1-rc.13) (2025-02-13)

### 👷 CI

* Use sudo for apt-get commands in release workflow for musl target ([904f418](https://github.com/inference-gateway/coder/commit/904f418fb8c701e298f92d483060609acd5fa4bd))

## [0.1.1-rc.12](https://github.com/inference-gateway/coder/compare/0.1.1-rc.11...0.1.1-rc.12) (2025-02-13)

### 👷 CI

* Ok this setup works if I try to cross compile from macos arm64 to x86 so it supposed to also work the other way from the runner ([c7d05cc](https://github.com/inference-gateway/coder/commit/c7d05cc6f2313f2a6e327fe68e699cd657da43c0))
* Update cross-compilation setup for musl targets and improve build tools installation ([2ea56e4](https://github.com/inference-gateway/coder/commit/2ea56e45db9e06713049d10d7d4f00d9d4cd5996))
* Update PATH for cross-compilation to include necessary binaries ([a43b632](https://github.com/inference-gateway/coder/commit/a43b632d11eb30e7a10644bfca1cf08689cac6f0))
* Update target from x86_64-unknown-linux-gnu to x86_64-unknown-linux-musl in release workflow ([f351ce2](https://github.com/inference-gateway/coder/commit/f351ce27a0a617837032cc2d22c247016950519f))

## [0.1.1-rc.11](https://github.com/inference-gateway/coder/compare/0.1.1-rc.10...0.1.1-rc.11) (2025-02-13)

### 👷 CI

* Increase timeout for Build and Upload Artifacts job to 25 minutes ([0b328b6](https://github.com/inference-gateway/coder/commit/0b328b6b9b7d1eb8ebf6f2690e50b0d64fcd7671))

## [0.1.1-rc.10](https://github.com/inference-gateway/coder/compare/0.1.1-rc.9...0.1.1-rc.10) (2025-02-13)

### 👷 CI

* Some cleanups ([6fdb00f](https://github.com/inference-gateway/coder/commit/6fdb00f817207588679376a029bb4590646e8dba))
* Update docker/build-push-action to version 6 in release workflow ([50e2c81](https://github.com/inference-gateway/coder/commit/50e2c8125973e1327b9e13558621d63b1c6c3ec8))

## [0.1.1-rc.9](https://github.com/inference-gateway/coder/compare/0.1.1-rc.8...0.1.1-rc.9) (2025-02-13)

### 👷 CI

* Set timeout for Build and Upload Artifacts job to 15 minutes ([5623c32](https://github.com/inference-gateway/coder/commit/5623c321d88ad6d6ac303e577d054cd0f22a0685))
* Update release workflow to use docker/build-push-action for building and pushing containers ([091c454](https://github.com/inference-gateway/coder/commit/091c454f1491afc5f1636f45cfdcf9ed968a242c))

## [0.1.1-rc.8](https://github.com/inference-gateway/coder/compare/0.1.1-rc.7...0.1.1-rc.8) (2025-02-13)

### 🐛 Bug Fixes

* Small fix ([fcede59](https://github.com/inference-gateway/coder/commit/fcede59f85a351e4baf6b23a32163c80e4766629))

## [0.1.1-rc.7](https://github.com/inference-gateway/coder/compare/0.1.1-rc.6...0.1.1-rc.7) (2025-02-13)

### 👷 CI

* Construct cache key to include with target in release workflow ([f74ac8f](https://github.com/inference-gateway/coder/commit/f74ac8f8d031b62bc747558a08106eb1f7ec8c8f))
* Try to specify explicitly buildx ([91b4ee9](https://github.com/inference-gateway/coder/commit/91b4ee92f589c1773844956b52ca00ea71227216))

## [0.1.1-rc.6](https://github.com/inference-gateway/coder/compare/0.1.1-rc.5...0.1.1-rc.6) (2025-02-13)

### 👷 CI

* Add conditional setup for QEMU and Docker Buildx only for Ubuntu ([6d29255](https://github.com/inference-gateway/coder/commit/6d292551d0b9eafeb30b812d383f93c025e70004))

## [0.1.1-rc.5](https://github.com/inference-gateway/coder/compare/0.1.1-rc.4...0.1.1-rc.5) (2025-02-13)

### 👷 CI

* Set up QEMU and Docker Buildx for using emulations ([96b9815](https://github.com/inference-gateway/coder/commit/96b981537cc71866197163efc9e5eb21a1439d02))

## [0.1.1-rc.4](https://github.com/inference-gateway/coder/compare/0.1.1-rc.3...0.1.1-rc.4) (2025-02-13)

### 👷 CI

* Add architecture platform support for Docker builds in release workflow ([7fe71aa](https://github.com/inference-gateway/coder/commit/7fe71aa1c5b4fa14c8bde6d8d0df730138e5c5f6))

## [0.1.1-rc.3](https://github.com/inference-gateway/coder/compare/0.1.1-rc.2...0.1.1-rc.3) (2025-02-13)

### 👷 CI

* Update Dockerfile to use Ubuntu base and install necessary dependencies for Rust cross-compilation ([969aab0](https://github.com/inference-gateway/coder/commit/969aab0a1c3b4e8517a4e01b831508cb908e94c8))

## [0.1.1-rc.2](https://github.com/inference-gateway/coder/compare/0.1.1-rc.1...0.1.1-rc.2) (2025-02-13)

### 👷 CI

* Simplify it cache the current pwd and enter it after download ([919427d](https://github.com/inference-gateway/coder/commit/919427dec879990e705f8da8b6f05cfbeb323856))

### 🔧 Miscellaneous

* Use a separate command for cargo to ensure workspace directory is restored ([22234d6](https://github.com/inference-gateway/coder/commit/22234d6a89d89bcc153bdb00c3632f6fe2873dc0))

## [0.1.1-rc.1](https://github.com/inference-gateway/coder/compare/0.1.0...0.1.1-rc.1) (2025-02-13)

### 👷 CI

* Remove commented-out debug flag from release workflow ([d9c9605](https://github.com/inference-gateway/coder/commit/d9c9605bc8d348849a78538145b0c36303293b2e))
