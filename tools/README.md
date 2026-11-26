# Tools

Each tool lives in its own folder: `tools/<tool-name>/`, lowercase and hyphenated. A tool can do one thing or many.

Every tool folder has:

- `README.md`: what it does, how to install and run it, inputs and outputs, limits, and how to cite it.
- `CHANGELOG.md`: append-only version history.
- Optional: `LICENSE` if the tool uses a different licence from the repo's MIT default.

Start from [`_template/`](_template/). Versioning and releases follow [`../docs/RELEASES.md`](../docs/RELEASES.md).

Tools here must run on public or user-supplied data. They must not bundle copyrighted corpora or private data.
