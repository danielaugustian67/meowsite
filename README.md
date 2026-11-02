# Meowshot download page

Static page for downloading the Meowshot Android app, hosted on Vercel. There is no build step.

## Update the APK

After each new build, change `destination` in `vercel.json` to the new APK link. Links to EAS builds expire, so check the date on the build page.

## Preview

```bash
npx serve .
```

The `/download` redirect only works on Vercel.
