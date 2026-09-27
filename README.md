# GalShelf releases

Windows builds of GalShelf and the metadata the in-app updater reads.

- Latest release: see [Releases](https://github.com/Harihi86/galshelf-releases/releases/latest).
- `stable/latest.json` is the signed update manifest of the stable channel, `stable/latest.json.sig`
  its detached Ed25519 signature. `releases/v<version>/` keeps the manifest, checksums and notes
  of every published version.
- Every Windows package is listed with its SHA-256. The updater installs a package only when the
  manifest signature, size and SHA-256 all match.
- Update manifests are signed with this public key (Ed25519, base64):

```
galshelf-update-2026-09: II1VyOQWGZphhHvY0bcjvqpuYkb1UjBmzb75h+VfuQc=
```
