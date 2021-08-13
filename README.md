### Dura XV Release Instructions

Example #1: Release ALO Mobile Android Version 1.7.0

1.  Copy, commit and push the .apk from the alo-mobile directory to the releases folder. 
```
  cp ../alo-mobile/platforms/android/app/build/outputs/apk/release/app-release.apk releases/1.7.0.apk
  git add .
  git commit -m 'release: version 1.7.0'
  git push origin main
```

2. In ALO (staging or production), go to Admin and create a new APK release with the value `1.7.0`

3. After creating a new production version you should update lastest.apk to match the latest version.



