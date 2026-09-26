# React Virtualized Instructions

Public components and tests live under `source/`; use `npm install` for the legacy dependencies and `npm start` for the Webpack development server, then run `npm test` for Standard lint plus Karma. Karma requires PhantomJS through the pinned `phantomjs-prebuilt` dependency. `npm run build` produces distribution and demo assets when a source change affects them.

When `CI` is set, `posttest` uploads coverage to CodeCov. Do not use CI for a local instruction check or treat that upload as local validation. `npm run deploy` and `postpublish` publish demo assets, so completion for a behavior change is the focused suite and relevant build, with deployment evidence separate.
