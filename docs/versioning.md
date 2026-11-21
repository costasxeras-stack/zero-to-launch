# Versioning

- MAJOR: a rebuild, or a change in how the app is used.
- MINOR: a new feature or visible improvement, for example a new method or dataset.
- PATCH: a bug fix or wording change.

The version must match in `package.json`, the top of `CHANGELOG.md`, the **Current version** line in `README.md` and the version badge in `index.html`.

Releases are published automatically. When a push to `main` has a version in `package.json` with no GitHub release yet, `.github/workflows/release.yml` creates one. The notes come from the matching `## [x.y.z]` section of `CHANGELOG.md`. If the commit subject starts with the version (for example `v0.2.0: add X`), it becomes the release title.
