# AtomicCypher

Public home for the computational epigraphy work of **Audrey Walter-Evans** (Audrey Evans): tools people can use, versioned releases, and links to published papers. Everything public lives here, in one place.

The research asks a narrow question: what can be tested about undeciphered scripts such as **Linear A** and the **Tărtăria** tablets, and how do we tell a real signal from a convincing story? The approach is falsification-first. Hypotheses are written down as explicit models, run against pre-registered criteria and permuted controls, and calibrated on a known script (Linear B) before they are applied to an unknown one.

- ORCID: [0009-0005-0663-7832](https://orcid.org/0009-0005-0663-7832)
- Website: [oaudrey.com](https://oaudrey.com)
- Zenodo: papers below, each with a DOI

## What is here

| Folder | What it holds |
| --- | --- |
| [`tools/`](tools/) | Tools and apps, one folder each, with its own README and CHANGELOG. A tool can do one thing or many. |
| [`papers/`](papers/) | Paper metadata and DOI links. The papers themselves live on Zenodo. |
| [`docs/`](docs/) | Write-ups, methods notes and how-to guides. |
| [`Library/`](Library/) | The public reference list this repo relies on, one line per item. |

## Tools and versions

| Tool | What it does | Latest version | Status |
| --- | --- | --- | --- |
| _None released yet_ | The first tool will be listed here when it ships. | — | — |

How versions work is in [`docs/RELEASES.md`](docs/RELEASES.md). In short: each tool uses Semantic Versioning, each release gets a git tag named `<tool>-vMAJOR.MINOR.PATCH` and a GitHub Release with notes and checksums.

## Papers

All are open-access preprints on Zenodo under CC BY 4.0.

| Date | Title | Topic | DOI (this version) | Concept DOI |
| --- | --- | --- | --- | --- |
| 2026-11-25 | Twelve Quadrupeds on Ivory: A Pre-Registered Falsification Protocol for the Knossos "Scepter" Inscription (KN Zg 57/58), the Longest Known Linear A Text | Linear A | [10.5281/zenodo.24519270](https://doi.org/10.5281/zenodo.24519270) | [all versions](https://doi.org/10.5281/zenodo.24519269) |
| 2026-11-23 | The Codex Holds Structure, Not Language: Computational Tests of the Rohonc Codex | Rohonc Codex | [10.5281/zenodo.24488531](https://doi.org/10.5281/zenodo.24488531) | [all versions](https://doi.org/10.5281/zenodo.24488530) |
| 2026-11-23 | The Rosetta Instrument | Decipherment method | [10.5281/zenodo.24488081](https://doi.org/10.5281/zenodo.24488081) | [all versions](https://doi.org/10.5281/zenodo.24484286) |
| 2026-11-23 | Deciphering Linear A with Zombies: A Falsification Protocol for Undead Decipherment Hypotheses, and the Problem of the Philosopher's Decipherment | Linear A | [10.5281/zenodo.24488074](https://doi.org/10.5281/zenodo.24488074) | [all versions](https://doi.org/10.5281/zenodo.24481161) |
| 2026-11-23 | The Ledger Holds, the Language Does Not: Computational Tests of Linear A Structure and Anatolian Affiliation | Linear A | [10.5281/zenodo.24488044](https://doi.org/10.5281/zenodo.24488044) | [all versions](https://doi.org/10.5281/zenodo.24487487) |
| 2026-02-20 | Ocean-2 V2: Scaling Deep-Ocean Wave Energy through Integrated Overtopping and Green Hydrogen Conversion | Energy (outside epigraphy) | [10.5281/zenodo.18713383](https://doi.org/10.5281/zenodo.18713383) | [all versions](https://doi.org/10.5281/zenodo.18713382) |

Details are in [`papers/README.md`](papers/README.md).

## Using a tool

1. Open the tool's folder under [`tools/`](tools/) and read its README.
2. Download a tagged release from [Releases](../../releases), or clone the repo and check out the tag.
3. Verify the download against the SHA-256 checksum in the release notes.

## What is not here

This is a public repository, so it holds no copyrighted source material (edition scans, corpus files under restrictive licences, purchased books), no private research data, and no credentials. Those stay in private repositories. Nothing here tracks you: there is no analytics, telemetry, pixel, or affiliate code.

## Citing

Cite the paper's DOI from the table above. To cite a tool, use the tag and the GitHub Release URL, or the tool's DOI once it has one. See [`CITATION.cff`](CITATION.cff).

## Licence

Code is under the [MIT Licence](LICENSE). Text, documentation and paper metadata are under [CC BY 4.0](LICENSE-docs). A tool folder may state its own licence, and that one applies to it.

## Contributing

See [`CONTRIBUTING.md`](CONTRIBUTING.md). Every claim is fact-checked, including the author's own.
