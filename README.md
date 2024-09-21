# `zcashd`

Zcash for Dart.  A command-line interface and library.

## Getting started
Run the command-line interface:
```sh
dart pub activate zcashd
pgp
```

or use the library as in:
```dart
dart pub add zcashd
```
<!--
```dart
import 'package:zcashd/zcashd.dart';

void main() {
    final zcashd = Zcash();
    final keyPair = zcashd.generateKeyPair();
    final publicKey = keyPair.publicKey;
}
```
