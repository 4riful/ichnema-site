# Ichnema — Security Research Studio

Public landing page: **https://4riful.github.io/ichnema-site/**

This repository contains only the reviewed static introduction and approved
display assets. It is not the core application or the future Studio frontend.
Ichnema is in development; the current foundation is offline-only.

`public/` is the complete deployable site. The workflow publishes only that
directory using GitHub Pages. There are no trackers, remote fonts, forms,
application workers, investigation data or credentials.

To preview locally:

```bash
python3 -m http.server --directory public 8000
```

Open http://localhost:8000. The site works without JavaScript. A font license is
included in `public/assets/OFL.txt`; no software or artwork license beyond that
font license is implied. Changes are maintained in the private development
monorepo and deliberately exported here; this repository is not a core-source mirror.
