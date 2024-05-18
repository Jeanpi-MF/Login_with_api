A new Flutter project for user authentication.

## Estructura del Proyecto

```plaintext
/lib
  ├── main.dart
  ├── login_screen.dart
  ├── home_screen.dart
  └── services
      └── user_service.dart


--------------------------
-------pubspec.yaml-------
--------------------------
name: login_with_api
description: "A new Flutter project."
publish_to: 'none'
version: 0.1.0

environment:
  sdk: '>=3.1.3 <4.0.0'

dependencies:
  flutter:
    sdk: flutter
  http: ^1.1.0
  local_auth: ^2.1.7
  shared_preferences: ^2.2.2
  sqflite: ^2.3.0

dev_dependencies:
  flutter_lints: ^2.0.0
  flutter_test:
    sdk: flutter

flutter:
  uses-material-design: true
