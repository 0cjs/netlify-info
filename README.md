netlify-info
============

Display some information about the [Netlify](https://www.netlify.com/)
build and deployment environment.

Currently this shows the following:

* <http://netlify-info.netlify.com/env.txt> - the process environment
  set up during the build. In particular, this may show that
  `WEBHOOK_URL` and `WEBHOOK_BODY` variables are set if you used
  a [webhook](https://www.netlify.com/docs/webhooks) to trigger the
  build.
