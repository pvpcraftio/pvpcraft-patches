# pvpcraft-patches

Release destination for the PvPcraft patch. This repository holds no source — it only receives built MPQ releases.

Releases here are published automatically by the **Build and Release Patch** GitHub Actions workflow in [pvpcraft-patch-development](https://github.com/pvpcraftio/pvpcraft-patch-development), which is triggered manually. Each release is named `v<version>` and has the built `.mpq` attached as an asset.

Don't push patch content directly to this repo — make changes in `pvpcraft-patch-development` under `src/` and cut a release from there.
