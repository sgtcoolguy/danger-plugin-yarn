# 1.0.0 (2020-10-05)


### Bug Fixes

* Don't refer to code that doesnt exist ([c0acc38](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/c0acc387e870c45763552ae4f743807811c57d8c))
* Try handle [@types](https://github.com/types) better ([bca7e92](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/bca7e923c4a581f73924e3961d9c2b475d1de1fc))
* vbump ([dbe1ea7](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/dbe1ea7b5603e5080bb60ea7f4da4c383104484f))


### Features

* npm5 compat ([5b7a9e4](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/5b7a9e4b87d18d39cc2b523864f893d2be393c69))
* Prepare for a new release ([ee1cba4](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/ee1cba47a55229df30e22c2270505e90a592c5ff))
* Refines the messaging ([1af1b43](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/1af1b43abeeb8f4df960ed0af9989f465273bb4f))
* Some cleanup ([3aaac06](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/3aaac0667be846ad2f83fc5adea2ac5d2d206146))
* Support for private packages ([92439ac](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/92439acf3b6444f777ef04c6f69053f0d360606c))
* support npm or yarn as package manager ([7e2dbe9](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/7e2dbe9d9ac23d1db240ef78fc1d1ec3f59d286e))
* vbump ([e3546d9](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/e3546d9dcc87309fe287e3e32e653070f498efc5))
* vbumph ([0ae68dc](https://github.com/sgtcoolguy/danger-plugin-dependencies/commit/0ae68dcce14f0a950b9854316f06982144899026))


### BREAKING CHANGES

* attempts to detect usage of npm vs yarn by sniffing lockfiles on disk. type must be
specified if there are no lockfiles or running on Peril.

type option must be specified if running on Peril or lockfiles are not on disk
