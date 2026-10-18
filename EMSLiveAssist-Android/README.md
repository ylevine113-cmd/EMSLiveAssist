# EMSLiveAssist Android starter

Android WebView shell for https://ylevine113-cmd.github.io/EMSLiveAssist/

This is an installable Android wrapper project, not a built APK. It requires internet, and website updates appear without rebuilding the APK. GitHub Actions builds an unsigned-for-production debug APK on main. The debug APK is for personal testing only, not Play Store distribution.

## Build with Android Studio
Open this directory as a project, allow Gradle sync, then choose Build > Build Bundle(s) / APK(s) > Build APK(s). The APK will be at app/build/outputs/apk/debug/app-debug.apk.

## Build with GitHub Actions
Copy the files from this ZIP into the root of the existing GitHub EMSLiveAssist repository (preserve its index.html), commit to main, and open Actions > Build Android APK > Run workflow. Download the artifact from the successful workflow run. Artifacts are zipped, so extract the APK before installing.

## Important
Not approved for actual medical decision-making. The source website explicitly describes itself as a concept demo based on historical protocols. Verify all clinical logic, security, privacy, reliability, and authorization before any operational use. Recording, download and Android back navigation need device testing.
