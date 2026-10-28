WinGo Tracker - Android WebView project

CURRENT FEATURES
- Wraps the local WinGo statistics demo in an Android app shell.
- Statistics and next-guess calculations are based on manually entered history.
- It is not a guaranteed prediction tool.

IMPORTANT LIMITATION
- Automatic live result collection from Shree.Win is NOT implemented. A verified, permitted and stable data source/API must be identified first. Do not assume that website access means an API is available.
- This project does not ask for Shree.Win login details, passwords, OTPs, or payment details.

BUILD APK USING A MOBILE PHONE (GitHub Actions)
1. Extract this ZIP on your phone.
2. Create a repository on GitHub using Chrome, then upload the contents of the WinGoTrackerAndroid folder (including the hidden .github folder). Alternatively, upload the ZIP to a new repository and extract it in the repository so the project files and .github/workflows/build-apk.yml are at the repository root.
3. Open the repository's Actions tab and run "Build WinGo Tracker APK" (or push to the main branch).
4. When the workflow finishes successfully, open that run and download the "WinGoTracker-debug-apk" artifact.
5. Extract the artifact ZIP to get app-debug.apk. Install only if you trust the source and Android does not show a security warning.

The project is configured for Android SDK 35 and Java 17. This is a debug APK for testing, not a Play Store release.
