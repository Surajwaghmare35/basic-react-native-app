fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## Android

### android test

```sh
[bundle exec] fastlane android test
```

Runs all the tests

### android clean

```sh
[bundle exec] fastlane android clean
```

Delete any existing assemble/bundle build directory

### android release

```sh
[bundle exec] fastlane android release
```

Submit new 'assemble=apk' & 'bundle=aab' Release Build

### android build

```sh
[bundle exec] fastlane android build
```

<<<<<<< HEAD
Runs all lane's
=======
Runs all the tests

### android deploy

```sh
[bundle exec] fastlane android deploy
```

Deploy a new version to the Google Play
>>>>>>> d30e35237e48312b9352d7c07fa62f2e9d4f03f2

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
