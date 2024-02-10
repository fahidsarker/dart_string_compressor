# String Compressor

A Dart package for compressing and decompressing strings using GZip and Base64 encoding.

## Features

- Compress and decompress strings synchronously in the same isolate.
- Compress and decompress strings asynchronously in a separate isolate.

## Usage

```dart
// Import the package
import 'package:string_compressor/string_compressor.dart';

// Compress a string
String compressedString = compressSync("your string");

// Decompress a string
String decompressedString = decompressSync(compressedString);

// Compress a string in a separate isolate
String compressedString = await compress("your string");

// Decompress a string in a separate isolate
String decompressedString = await decompress(compressedString);
```

## Installation
```yaml
dependencies:
  string_compressor: ^1.0.3
```
Then install it by running flutter pub get in your terminal.