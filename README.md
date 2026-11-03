# Meowshot download page

Static page for downloading the Meowshot Android app, hosted on Vercel. There is no build step.

## Update the APK

After each new release, change `destination` in `vercel.json` to the APK attached to the new GitHub release of `meowshot-mobile`, and the version in `index.html`.

## Preview

```bash
npx serve .
```

The `/download` redirect only works on Vercel.
