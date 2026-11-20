# addict-indexes

The data releases of [Addict](https://github.com/doqhu/addict): the prebuilt
dictionary indexes the app downloads, one release per index format
(`indexes-v<format>`), with their manifests, licenses and credits on each
release page.

The workflow `.github/workflows/indexes.yml` builds the indexes once a month
with the builder of `doqhu/addict` and replaces the assets of the current
release. Releases here are mutable on purpose; the app's own releases in
`doqhu/addict` are immutable. The contract between these releases and the
app is
[docs/index-release.md](https://github.com/doqhu/addict/blob/main/docs/index-release.md).

This repository holds no code of its own. Each index keeps the license of its
source, which its release notes name.
