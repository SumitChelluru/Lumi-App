BUILD THE APK WITHOUT ANDROID STUDIO (GitHub does it for you, free)
1. Create a free GitHub account and a new repository (any name).
2. Upload everything in this folder, keeping the structure: package.json, capacitor.config.json, www/index.html, .github/workflows/build.yml
   (If the uploader skips the hidden .github folder: Add file > Create new file, name it .github/workflows/build.yml and paste the contents of that file.)
3. Open the repo's Actions tab. "Build APK" runs automatically (about 5 minutes).
4. Open the finished run, scroll to Artifacts, download "lumi-apk", unzip it, install app-debug.apk on your phone.
To change the app, replace www/index.html and commit: a new APK is built.
