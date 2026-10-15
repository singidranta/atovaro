# atovaro

Public file host for [AtomCode](https://atomcode-ai.web.app/), an AI coding agent for Windows.

This repository holds no source code. It exists for two reasons:

- the site at <https://atomcode-ai.web.app/> is the product page; every download button there resolves to the assets of this repository's [latest release](https://github.com/singidranta/atovaro/releases/latest);
- the Windows installer is served over GitHub's HTTPS CDN instead of the project's own server.

## Download

Stable link (always the newest build):

```
https://github.com/singidranta/atovaro/releases/latest/download/AtomCode-Setup-latest.exe
```

Each release also carries `latest.yml` and the `.blockmap` used by the in-app updater, and its SHA-512 and size are published on the site's release page.

The build is unsigned, so Windows shows "Unknown publisher" on the first run — choose "More info → Run anyway".
