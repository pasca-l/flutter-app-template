## Format files
1. Format source codes according to [Dart formatting guidelines](https://dart.dev/effective-dart/style#formatting), using [`dart format` command](https://dart.dev/tools/dart-format).
```bash
$ dart format ./lib
```

## Sort imports
1. Automatically sort imports according to [Dart formatting guidelines](https://dart.dev/effective-dart/style#ordering), using [import_sorter](https://pub.dev/packages/import_sorter).
```bash
$ flutter pub run import_sorter:main
```
