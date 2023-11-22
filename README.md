# Monstarlab Flutter Lints [![pub version][pub-version-img]][pub-version-url]

[Flutter](https://flutter.dev) lint rules used by [Monstarlab](https://monstar-lab.com/global). Built on top of the [officially recommended](https://pub.dev/packages/flutter_lints) Flutter rules.

- All the existing Flutter lint rules are listed on [this page](https://dart.dev/tools/linter-rules).
- Check out our [Flutter template](https://github.com/monstar-lab-oss/flutter-template).

## Usage

### Install

```bash
dart pub add dev:monstarlab_lints
# or
flutter pub add dev:monstarlab_lints
```

Or add it to the `pubspec.yaml` yourself:

```yaml
dev_dependencies:
  monstarlab_lints: ^1.0.2
```

### Configure analysis options

Modify your [`analysis_options.yaml`](https://dart.dev/tools/analysis#the-analysis-options-file):

```yaml
include: package:monstarlab_lints/analysis_options.yaml
```

## Maintaining

To publish a new version to pub.dev, create a new tag with required version used as a title. For example, creating a tag `1.0.3` will result in pushing the package to pub.dev with version `1.0.3`.


<!-- References -->
[pub-version-img]: https://img.shields.io/badge/pub-v1.0.2-0175c2?logo=flutter
[pub-version-url]: https://pub.dev/packages/monstarlab_lints