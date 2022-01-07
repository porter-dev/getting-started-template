# Overview

This repo was made to generate static templates for Porter's `getting-started` repositories. It uses `docusaurus` to maintain consistency with the core Porter docs.

# Building for Runtimes

You can target a runtime with `npm run build-$RUNTIME`, for example:

```
npm run build-golang
npm run build-nodejs
```

The resulting files in the `/build` directory should then be placed in the corresponding repo. This will eventually be replaced by a Github action that does this automatically.
