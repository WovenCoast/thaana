# Thaana

Thaana utilities for Flutter

## Installation

1. Add the latest version of package to your pubspec.yaml (and run`dart pub get`):

```yaml
dependencies:
  thaana: ^0.0.1
```

2. Import the package and use it in your Flutter App.

```dart
import 'package:thaana/thaana.dart';
```

## Examples

- Convert latin to thaana

```dart
String hello = "dhuniye";

hello.convertLatinToThaana() // ދުނިޔެ
```

- Add thaana typing capabilities to a text field

```dart
ThaanaTextField(
    controller: myTextEditingController,
    style: TextStyle(...),
);
```
