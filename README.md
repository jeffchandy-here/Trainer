# Trainer

MMA & gym tracker. Ticks and notes are saved on the phone and stay after closing the app.

## Build with GitHub (no install needed)
1. Create a new GitHub repo and upload everything in this folder (including the hidden `.github` folder).
2. Open the Actions tab > "Build APK" and wait for the green tick (~3-5 min).
3. Download `Trainer-apk` from that run, unzip, copy `app-debug.apk` to your phone and install it
   (allow "install unknown apps" when asked).

## Build with Android Studio
Open this folder, let it sync, then Build > Build App Bundle(s) / APK(s) > Build APK(s).

## Updating
A fixed signing key is included (`app/trainer.jks`), so a new build installs over the old one
and keeps your history. Uninstalling the app deletes the history.
