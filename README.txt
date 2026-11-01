ABDUU LIFE OS — APP PACKAGE

WHAT IS INCLUDED
1) web/ — installable Progressive Web App (PWA), suitable for iPhone Home Screen and Android browser install.
2) docs/ — same PWA files arranged for simple GitHub Pages hosting from the repository root.
3) android-project/ — Android Studio WebView wrapper source project.
4) .github/workflows/build-android-apk.yml — GitHub Actions workflow to build a debug APK in the cloud.
5) README-QUICK-START.txt — step-by-step free hosting and APK build instructions.

IPHONE
Host the contents of docs/ on a static HTTPS host. Then open the HTTPS address in Safari on iPhone and choose Share -> Add to Home Screen. Enable Open as Web App if shown.

ANDROID APK
Upload android-project/ and .github/ to a GitHub repository. Run the "Build ABDUU Life OS APK" workflow from the Actions tab. Download the APK artifact from the completed run.

NOTES
- GitHub Pages sites are public; do not publish private information.
- App data uses local storage and remains on that device/browser.
- The PWA requires HTTPS hosting for service worker/offline install features.
