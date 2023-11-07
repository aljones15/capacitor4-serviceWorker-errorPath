# capacitor4-serviceWorker-errorPath
Simple demo app to demonstrate that errorPath is broken when using server.url and a serviceWorker


### Steps

1. Have an existing Android emulator open in airplane mode.
2. Use `npx cap run android` and choose the existing emulator.
3. You should see a bare bones error page that matches `www/applicationError.html`
![Bare Bones Error Page](https://github.com/aljones15/capacitor4-serviceWorker-errorPath/blob/main/images/Step1.png)
4. Turn off airplane mode
5. Resume the app and click on reload
6. Should see the angular home page
![Angular HomePage](https://github.com/aljones15/capacitor4-serviceWorker-errorPath/blob/main/images/Step2.png)
7. Close the app entirely (no resume)
8. Turn airplane mode back on
9. Reopen the app should see crash screen.
![Crash Screen](https://github.com/aljones15/capacitor4-serviceWorker-errorPath/blob/main/images/Step3.png)
