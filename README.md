# cmds
./gradlew signingReport








keytool -list -v -keystore ~/.android/debug.keystore -alias androiddebugkey -storepass android -keypass android
{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "vhub devlopment",
      "request": "launch",
      "type": "dart",
      "program": "lib/main_development.dart",
      "args": [
        "--flavor",
        "development",
        "--target",
        "lib/main_development.dart"
      ]
    },
    {
      "name": "vhub production",
      "request": "launch",
      "type": "dart",
      "program": "lib/main_production.dart",
      "args": ["--flavor", "production", "--target", "lib/main_production.dart"]
    }
  ]
}
