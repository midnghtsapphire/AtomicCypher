# Releases and versioning

Everything here stays on free GitHub features. There are no hosted Actions runners, no Git LFS, and no paid add-ons.

## Version numbers

Each tool is versioned on its own with [Semantic Versioning](https://semver.org/): `MAJOR.MINOR.PATCH`.

- **MAJOR**: a change that breaks how people use the tool (inputs, outputs, commands).
- **MINOR**: a new feature that does not break existing use.
- **PATCH**: a fix that changes nothing else.
- Before `1.0.0`, the tool is still settling, and a minor bump may break things. The CHANGELOG says so when it does.

## Tags

Tag format: `<tool-name>-vMAJOR.MINOR.PATCH`, for example `example-tool-v0.1.0`. A tag is never moved or deleted once it is pushed. A mistake is fixed with a new patch release.

## Making a release

1. Update `tools/<tool-name>/CHANGELOG.md` with the new version and today's date (America/Denver).
2. Update the version and the "Latest version" column in the top-level README.
3. Run the tool's tests locally and record the command and result in the PR.
4. Merge the release PR.
5. Build the release files locally and record their checksums: `sha256sum <files> > SHA256SUMS`.
6. Create the tag and GitHub Release from your own machine:

   ```bash
   git tag -a example-tool-v0.1.0 -m "example-tool v0.1.0"
   git push origin example-tool-v0.1.0
   gh release create example-tool-v0.1.0 dist/* SHA256SUMS \
     --title "example-tool v0.1.0" --notes-file release-notes.md
   ```

7. Release notes list what changed, how to install, the checksums, and known limits.

## Large files

Release assets can be up to 2 GB each. Split anything larger into parts under 2 GB and list each part's checksum. Large files never go in the git history.

## DOIs for tools (optional)

A tool release can get its own DOI by depositing the release on Zenodo by hand. Add the DOI to the tool's README and the top-level table.
