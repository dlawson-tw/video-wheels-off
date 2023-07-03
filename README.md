# video-wheels-off

## 2023 Update

- History for repo has the old files for reference
- non-archived files are the current work (see [archive](./archive) folder)

## Quickstart

[Quickstart Examples](js-qs-examples/js-qs-examples.md)

## React App

### For M1 Mac, Puppeteer will fail the Chromium install. Fix:

[How to fix M1 Mac Puppeteer chromium arm64 bug](https://linguinecode.com/post/how-to-fix-m1-mac-puppeteer-chromium-arm64-bug)

- `brew install chromium --no-quarantine` (to allow through OSX)
- Test with `which chromium` (should show `/opt/homebrew/bin/chromium`)
- Run Chromium once to verify install
- Add the following lines to `~/.zshrc`
```
export PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true
export PUPPETEER_EXECUTABLE_PATH=`which chromium`
```

- Run `source ~/.zshrc` (or exit and restart the terminal)
- Run `npm install` from the `twilio-video-app-react` directory


