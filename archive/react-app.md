
## Deployed 2021-11-17
```
~/r/twilio-video-app-react master ⇡1 *1 ❯ npm run deploy:twilio-cli              3m 41s Node system

> twilio-video-app-react@0.6.0 deploy:twilio-cli
> cross-env REACT_APP_SET_AUTH=passcode npm run build && twilio rtc:apps:video:deploy --authentication=passcode --app-directory ./build


> twilio-video-app-react@0.6.0 build
> node ./scripts/build.js

Creating an optimized production build...
Compiled successfully.

File sizes after gzip:

  779.99 KB  build/static/js/2.9c6126fb.chunk.js
  110.04 KB  build/static/js/main.562d82aa.chunk.js
  785 B      build/static/js/runtime-main.b702b074.js

The project was built assuming it is hosted at /.
You can control this with the homepage field in your package.json.

  https://cra.link/deployment
deploying app... done
Web App URL: https://video-app-9248-9797-dev.twil.io?passcode=43796892489797
Passcode: 437 968 9248 9797
Expires: Wed Nov 24 2021 10:37:27 GMT-0500
Room Type: group
Edit your token server at: https://www.twilio.com/console/functions/editor/ZSa506182aa1bc69d2c920404cba5975ba/environment/ZE55982f68f254a1e0a78b7f0048bd3538/function/ZHdb19a22dd7962365b3fbfc7f988de353
```
## Testing Redeployment (Token Reset)
```
~/r/twilio-video-app-react master ⇡1 *1 ❯ npm run deploy:twilio-cli -- --override    6s Node system

> twilio-video-app-react@0.6.0 deploy:twilio-cli
> cross-env REACT_APP_SET_AUTH=passcode npm run build && twilio rtc:apps:video:deploy --authentication=passcode --app-directory ./build "--override"


> twilio-video-app-react@0.6.0 build
> node ./scripts/build.js

Creating an optimized production build...
Compiled successfully.

File sizes after gzip:

  779.99 KB  build/static/js/2.9c6126fb.chunk.js
  110.04 KB  build/static/js/main.562d82aa.chunk.js
  785 B      build/static/js/runtime-main.b702b074.js

  https://cra.link/deployment

deploying app... done
Web App URL: https://video-app-9248-9797-dev.twil.io?passcode=10120092489797
Passcode: 101 200 9248 9797
Expires: Thu Nov 25 2021 09:15:39 GMT-0500
Room Type: group
Edit your token server at: https://www.twilio.com/console/functions/editor/ZSa506182aa1bc69d2c920404cba5975ba/environment/ZE55982f68f254a1e0a78b7f0048bd3538/function/ZHdb19a22dd7962365b3fbfc7f988de353
```
