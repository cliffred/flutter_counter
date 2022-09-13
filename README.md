# flutter_counter

A new Flutter project.

## Run integration tests on emulator

```sh
flutter pub get
cd android
./gradlew app:connectedAndroidTest -Ptarget=`pwd`/../integration_test/app_test.dart
```
