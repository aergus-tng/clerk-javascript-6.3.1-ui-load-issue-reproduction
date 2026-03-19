# `clerk-js` 6.3.1 [UI load issue](https://github.com/clerk/javascript/issues/8119) reproduction

This repository reproduces the issue that the Clerk JS library in version 6.3.1 throws an error with "Clerk was not loaded with Ui components" when attempting to mount components after the Clerk object is loaded without a `ui` parameter.

In fact, it is simply the [quickstart application from Clerk docs](https://clerk.com/docs/js-frontend/getting-started/quickstart) ([archived version](https://web.archive.org/web/20260228143255/https://clerk.com/docs/js-frontend/getting-started/quickstart)).


