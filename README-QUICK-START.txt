ABDUU LIFE OS — FREE HOSTING + APK BUILD

FIRST — EXTRACT THE PACKAGE
1. Download and extract ABDUU_Life_OS_App_Package.zip on your computer.
2. Open the extracted abduu_life_os_package folder. You should see docs, android-project, .github, and README files.
3. On Windows, turn on File Explorer > View > Show > Hidden items so you can see the .github folder.

PART A — HOST THE IPHONE WEB APP FOR FREE WITH GITHUB PAGES
1. Sign in or create a free GitHub account: https://github.com
2. Click + (top right) > New repository.
3. Name it abduu-life-os. Choose Public, then Create repository.
4. In the new repository, choose Add file > Upload files.
5. Upload ALL CONTENTS inside abduu_life_os_package, including the docs folder, android-project folder, and hidden .github folder. Keep the folder structure. Do not upload only the outer abduu_life_os_package folder.
6. Click Commit changes.
7. Open repository Settings > Pages.
8. Under Build and deployment, set Source to Deploy from a branch.
9. Choose branch main and folder /docs, then Save.
10. Wait for deployment. The address will be https://YOUR-GITHUB-USERNAME.github.io/abduu-life-os/
11. On iPhone, open that address in Safari > Share > Add to Home Screen > Add.

PART B — BUILD APK AUTOMATICALLY FOR FREE WITH GITHUB ACTIONS
1. The same upload in Part A should include android-project/ and .github/workflows/build-android-apk.yml.
2. Open the repository's Actions tab.
3. Select "Build ABDUU Life OS APK" from the left side.
4. Click Run workflow > Run workflow.
5. Wait for the run to finish successfully (green tick).
6. Open the completed run. Under Artifacts, download ABDUU-Life-OS-debug-APK.
7. Extract the downloaded ZIP. Inside is app-debug.apk. Transfer it to your Android phone and tap it to install. If Android asks, allow installation from that source.

IMPORTANT
- GitHub Pages sites are public. Do not store private data or secrets in this repository.
- This APK is a debug build for personal testing/installation, not a Play Store release.
- The app stores its data locally on the device/browser; it does not sync data between iPhone and Android.
- GitHub Pages may take a few minutes to publish.
