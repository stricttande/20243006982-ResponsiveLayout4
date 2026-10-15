# GitConflictDemo-Xiezheng

Practical 4 collaboration exercise for **Xiezheng (20243006982)**. The Android project demonstrates two developers changing the same button-colour lines on separate branches and then resolving the resulting merge conflict.

## Branch workflow

- `master` starts with the neutral button colour and the working Android application.
- `feature-red-button` changes both buttons to red.
- `feature-green-button` changes the same XML lines to green.
- The red feature is merged into `master` first. The green feature is then merged with the conflict resolved intentionally.

The final application keeps the green-button implementation after the conflict is reviewed and resolved. The repository history retains both feature commits, the conflict-resolution commit, and the final merge.

## Build

Open the project in Android Studio and run the `app` configuration on an Android emulator. From a terminal with the Android SDK configured, `gradlew.bat assembleDebug` builds the debug APK.
