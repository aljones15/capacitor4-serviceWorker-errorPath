# capacitor4-serviceWorker-errorPath
Simple demo app to demonstrate that errorPath is broken when using server.url and a serviceWorker


### Steps

1. Have an existing Android emulator open in airplane mode.
2. Use `npx cap run android` and choose the existing emulator.
3. You should see a bare bones error page that matches `www/applicationError.html`
4. Turn off airplane mode
5. Resume the app and click on reload
6. Should see the angular home page
7. Close the app entirely (no resume)
8. Turn airplane mode back on
9. Reopen the app should see crash screen.
