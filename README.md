Sahyadri Telemed Android Starter — cloud APK build enabled

Project branding:
- App name: Sahyadri Telemed
- Selected modern teal/green logo included in assets/logo.png
- Full selected logo included at project root
- Demo patient and doctor flows are included in the app's local HTML interface.

Build APK:
1. Upload this entire project folder's contents to a GitHub repository (the project root is this folder).
2. Open the repository's Actions tab and run “Build Sahyadri Telemed APK” (or push to main/master).
3. When the workflow completes, open its run, scroll to Artifacts, and download “Sahyadri-Telemed-debug-apk”.
4. Extract the artifact ZIP to get app-debug.apk, then transfer it to your Android phone to install.

Important limitations:
- I cannot compile or verify the APK in this current workspace because Android SDK and Gradle are not installed here.
- This project configures a cloud build workflow; an APK is produced only after you push it to GitHub and the workflow runs.
- This is a prototype only. No real OTP, secure cloud backend, payment gateway, or live video/audio consultation is connected.
- Do not enter real sensitive patient data.
