cd into the app directory and run

```
npm install
npm run build
npx cap add android
npx cap add ios
npx cap sync
```

To open in android and ios respectively run

```
npx cap open android
npx cap open ios
```

If building in IOS, the above command will open xcode. You can follow the workflow to generate a .ipa as detailed at https://stackoverflow.com/questions/5499125/how-to-create-ipa-file-using-xcode.
