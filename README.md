# Suuria Dalamud plugin repository

This repository hosts the downloadable artifacts and repository index for Suuria's
Dalamud plugins.

Add this URL as a custom plugin repository in Dalamud:

```text
https://suuria.github.io/pluginmaster.json
```

Published packages are stored below `plugins/<InternalName>/`. `latest.zip` is the
stable download used by Dalamud; versioned ZIP files are retained so releases remain
traceable.

GitHub Pages must use **GitHub Actions** as its build and deployment source. A push to
`master` then deploys the repository contents automatically.
