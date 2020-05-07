# rn

Flutter rename project. Re-developed on [rename](https://pub.dev/packages/rename) package.

## A few words

The [flutter-boilerplate](https://github.com/fatihmert/Flutter---Boilerplate) I created recently was embedded in my project. Since the codes are dynamic, I needed to create a separate package.

Because the [rename](https://pub.dev/packages/rename) package did not support operations such as manipulating android bundleId with a folder. Based on this package, the deficiencies were eliminated and the variables were removed from the CLI and moved to the _build.env_ file.

## Getting Started

Create `build.env` file on your project root directory.

Copy following codes to build.env file;

```dotenv
# pubspec.yaml -> name
FLUTTER_PACKAGE_NAME=flutterarch

# App name appearing on the device
APPLICATION_NAME=Flutter Arch

# pubspec.yaml -> description
APPLICATON_DESCRIPTION=A new Flutter architecture.

# Package name; com.google.flutter etc.
DOMAIN_NAME=fatihmert.dev.flutterarch
```

Replace as desired, then run command;

```
pub global run rn
```

or

```
rn
```
