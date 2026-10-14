# JABREF

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-academia_rd-lightgrey)

> Anticloud-hardened packaging of the upstream project `JABREF` in category **ACADEMIA RD**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ACADEMIA RD · **Upstream:** https://github.com/JabRef/jabref · **Upstream pin:** `f8448240b8fe7c95087db4de7327e855e048f943` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# JabRef Bibliography Management [![APIdia](https://apidia.net/java/JabRef/main/badge.svg)](https://apidia.net/java/JabRef/main)

JabRef is an open-source, cross-platform citation and reference management tool.

Stay on top of your literature: JabRef helps you to collect and organize sources, find the paper you need and discover the latest research.

![main table](docs/images/jabref-mainscreen.png)

## Features

JabRef is available free of charge and is actively developed.
It supports you in every step of your research work.

### Collect

- Search across many online scientific catalogues like CrossRef, Google Scholar, IEEEXplore, INSPIRE-HEP, Medline PubMed, MathSciNet, Springer, arXiv, and zbMATH
- Import options for over 15 reference formats
- Easily retrieve and link full-text articles
- Fetch complete bibliographic information based on ISBN, DOI, PubMed-ID and arXiv-ID
- Extract metadata from PDFs
- Import new references directly from the browser with one click using the [official browser extension](https://github.com/JabRef/JabRef-Browser-Extension) for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/jabref/?src=external-github),  [Chrome](https://chrome.google.com/webstore/detail/jabref-browser-extension/bifehkofibaamoeaopjglfkddgkijdlh), [Edge](https://microsoftedge.microsoft.com/addons/detail/pgkajmkfgbehiomipedjhoddkejohfna), and [Vivaldi](https://chrome.google.com/webstore/detail/jabref-browser-extension/bifehkofibaamoeaopjglfkddgkijdlh)

### Organize

- Group your research into hierarchical collections and organize research items based on keywords/tags, search terms, or your manual assignments
- Advanced search and filter features
- Complete and fix bibliographic data by comparing with curated online catalogs such as Google Scholar, Springer, or MathSciNet
- Customizable citation key generator
- Customize and add new metadata fields or reference types
- Find and merge duplicates
- Attach related documents: 20 different kinds of documents supported out of the box, completely customizable and extendable
- Automatically rename and move associated documents according to customizable rules
- Keep track of what you read: ranking, priority, printed, quality-assured

### Cite

- Native BibTeX and BibLaTeX support
- Cite-as-you-write functionality for external applications such as Emacs, Kile, LyX, Texmaker, TeXstudio, Vim and WinEdt.
- Format references using one of thousands of built-in citation styles or create your own style
- Support for Word and LibreOffice/OpenOffice for inserting and formatting citations

### Share

- Many built-in export options or create your export format
- Library is saved as a simple text file, and thus it is easy to share with others via Dropbox and is version-control friendly
- Work in a team: sync the contents of your library via a SQL database

## Installation

Fresh development builds are available at [builds.jabref.org](https://builds.jabref.org/main/).
The [latest stable release is available at GitHub](https://downloads.jabref.org/).

Please see our [Installation Guide](https://docs.jabref.org/installation).

## JabKit

JabRef offers a CLI application.

You can run it using JBang.
We provide details at [`.jbang/README.md`](.jbang/README.md).

You can also run JabKit using docker:

```terminal
docker run ghcr.io/jabref/jabkit:edge --help
```

## Bug Reports, Suggestions, Other Feedback

[![Donation](https://img.shields.io/badge/donate%20to-jabref-orange.svg)](https://donations.jabref.org)
[![PayPal Donate](https://img.shields.io/badge/donate-paypal-00457c.svg?logo=paypal&style=flat-square)](https://paypal.me/JabRef)

We are thankful for any bug reports or other feedback.
If you have ideas for new features you want to be included in JabRef, tell us in [the feature section](http://discourse.jabref.org/c/features) of our forum!
If you need support in using JabRef, please read the [user documentation](https://docs.jabref.org/), especially the [frequently asked questions (FAQ)](https://docs.jabref.org/faq) and also take a look at our [community forum](https://discourse.jabref.org/c/help/7).
You can use our [GitHub issue tracker](https://github.com/JabRef/jabref/issues) to file bug reports.

An explanation of donation possibilities and usage of donations is available at our [donations page](https://donations.jabref.org).

## Contributing

Want to be part of a free and open-source project that tens of thousands of researchers use every day?
Please take a look at our [guidelines for contributing](CONTRIBUTING.md).

## Building from Source

Please see [Building from source](https://docs.jabref.org/installation#building-from-source) for instructions on how to build JabRef from sources.

## Research and Education

JabRef welcomes research applied to it.
The current list of papers where JabRef helped to enhance science is maintained at <https://github.com/JabRef/jabref/wiki/JabRef-in-the-Media>.

The JabRef team also fosters to use JabRef in Software Engineering training.
We offer guidelines for this at <https://devdocs.jabref.org/teaching.html>.

When citing JabRef, please use the following citation:

```bibtex
@Article{jabref,
  author  = {Oliver Kopp and Carl Christian Snethlage and Christoph Schwentker},
  title   = {JabRef: BibTeX-based literature management software},
  journal = {TUGboat},
  volume  = {44},
  number  = {3},
  pages   = {441--447},
  doi     = {10.47397/tb/44-3/tb138kopp-jabref},
  issn    = {0896-3207},
  issue   = {138},
  year    = {2023},
}
```

DOI (also includes [full text](https://tug.org/TUGboat/tb44-3/tb138kopp-jabref.pdf)): [10.47397/tb/44-3/tb138kopp-jabref](https://doi.org/10.47397/tb/44-3/tb138kopp-jabref).

## Sponsoring

JabRef development is powered by YourKit Java Profiler  
[![YourKit Java Profiler](https://www.yourkit.com/images/yk_logo.svg)](https://www.yourkit.com/java/profiler/)

<!-- markdownlint-disable-file MD060 -->

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, package-lock.json; scanned in UPSTREAM_CLONE)
- Top-level source layout: `build-logic/`, `build-support/`, `config/`, `flatpak/`, `gradle/`, `jabgui/`, `jabkit/`, `jablib/`, `jablib-examples/`, `jabls/`, `jabls-cli/`, `jabsrv/`
- Upstream commit pinned for this packaging: `f8448240b8fe7c95087db4de7327e855e048f943`

---

## Installation

Fresh development builds are available at [builds.jabref.org](https://builds.jabref.org/main/).
The [latest stable release is available at GitHub](https://downloads.jabref.org/).

Please see our [Installation Guide](https://docs.jabref.org/installation).

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

An explanation of donation possibilities and usage of donations is available at our [donations page](https://donations.jabref.org).

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

JabRef is an open-source, cross-platform citation and reference management tool.

Stay on top of your literature: JabRef helps you to collect and organize sources, find the paper you need and discover the latest research.

![main table](docs/images/jabref-mainscreen.png)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, package-lock.json |
| Files in snapshot | not captured in this benchmark snapshot |
| Lines of code | not captured in this benchmark snapshot |
| Dependency references | not captured in this benchmark snapshot |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

- Easily retrieve and link full-text articles
- Fetch complete bibliographic information based on ISBN, DOI, PubMed-ID and arXiv-ID
- Extract metadata from PDFs
- Import new references directly from the browser with one click using the [official browser extension](https://github.com/JabRef/JabRef-Browser-Extension) for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/jabref/?src=external-github),  [Chrome](https://chrome.google.com/webstore/detail/jabref-browser-extension/bifehkofibaamoeaopjglfkddgkijdlh), [Edge](https://microsoftedge.microsoft.com/addons/detail/pgkajmkfgbehiomipedjhoddkejohfna), and [Vivaldi](https://chrome.google.com/webstore/detail/jabref-browser-extension/bifehkofibaamoeaopjglfkddgkijdlh)

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing

We welcome contributions to JabRef and encourage you to follow the [GitHub workflow](https://docs.github.com/en/get-started/using-github/github-flow).
You can also check out the explanation of [Feature Branch Workflow](https://atlassian.com/git/tutorials/comparing-workflows#feature-branch-workflow) for the idea behind this kind of development.

JabRef regards its contributors as **[software engineers, not just programmers](https://www.phoenix.edu/blog/programmer-vs-software-engineer-key-differences.html)**.
As one consequence, for non-basic issues, you will have to work on the requirements side, too.

> [!TIP]
> If you are a newcomer, the two most helpful sections to navigate through are the [guidelines for setting up a local workspace](https://devdocs.jabref.org/getting-into-the-code/guidelines-for-setting-up-a-local-workspace/) (to get JabRef's source code into your local machine and get the development version running), and [frequently asked questions](https://devdocs.jabref.org/code-howtos/faq) - where you will find solutions to issues that are most commonly faced by new contributors.
<!-- markdownlint-disable-next-line MD028 -->
> [!NOTE]
> For non-programmers, a general overview on contributing is available at <https://docs.jabref.org/contributing>.

## Table of Contents

* [Choosing a task](#choosing-a-task-)
* [Getting a task assigned](#getting-a-task-assigned)
* [Pull Request Process](#pull-request-process)
  * [Requirements on the pull request and code](#requirements-on-the-pull-request-and-code)
  * [After submission of a pull request](#after-submission-of-a-pull-request)
  * [Development hints](#development-hints)

## Choosing a task [![Join the chat at https://gitter.im/JabRef/jabref](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/JabRef/jabref)

In general, we offer small issues perfect for aspiring developers.
These tasks provide an opportunity to learn how to set up your local workspace, create your first pull request on GitHub, and contribute towards solving minor problems or making small enhancements in JabRef.

It is essential to note that JabRef's issues vary in difficulty.
Some are simpler, while others are more complex. Our primary aim is to guide you through the code, ensuring that the understanding scope remains manageable. Sometimes, grasping the code might demand more effort than actually writing lines of code.

### I am a student (or a beginner to Open Source)

* Select an issue to work on from the [

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright © 2003-2026 JabRef Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `JABREF` (category: ACADEMIA RD)
- **Upstream URL:** https://github.com/JabRef/jabref
- **Pinned commit (SHA):** `f8448240b8fe7c95087db4de7327e855e048f943`
- **Branch:** main
- **Pin provenance:** GitHub API commits/<branch> (response quoted in report). The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`ffe38f7d15a215b56e83b5eab4d390e75bc6cb4e1c9ee9dcc02795bd48a83120`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

