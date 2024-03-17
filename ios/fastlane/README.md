fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios clean

```sh
[bundle exec] fastlane ios clean
```

Cleanup Workspace

### ios setup_certificates

```sh
[bundle exec] fastlane ios setup_certificates
```

Setup Certificates

### ios generate_certificates

```sh
[bundle exec] fastlane ios generate_certificates
```

Generate New Certificates

### ios test

```sh
[bundle exec] fastlane ios test
```

Run Unit Tests

### ios internal

```sh
[bundle exec] fastlane ios internal
```

Deploy to TestFlight (Internal)

### ios production

```sh
[bundle exec] fastlane ios production
```

Deploy to TestFlight (Production)

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
