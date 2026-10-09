# PYCROSCOPY

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-scientific_lab-lightgrey)

> Anticloud-hardened packaging of the upstream project `PYCROSCOPY` in category **SCIENTIFIC LAB**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SCIENTIFIC LAB · **Upstream:** https://github.com/pycroscopy/pycroscopy · **Upstream pin:** `90e2d232acc9da634131c1793f082a70a04a3297` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# pycroscopy

![Downloads](http://pepy.tech/badge/pycroscopy)
[![GitHub Actions](https://github.com/pycroscopy/pycroscopy/workflows/build/badge.svg?branch=main)](https://github.com/pycroscopy/pycroscopy/actions?query=workflow%3Abuild)
[![PyPI](https://img.shields.io/pypi/v/pycroscopy.svg)](https://pypi.org/project/pyCroscopy/)
[![Coverage](https://codecov.io/gh/pycroscopy/pycroscopy/branch/main/graph/badge.svg?token=HXGZMKzJqb)](https://codecov.io/gh/pycroscopy/pycroscopy)
[![Conda Forge](https://img.shields.io/conda/vn/conda-forge/pycroscopy.svg)](https://github.com/conda-forge/pycroscopy-feedstock)
[![License](https://img.shields.io/pypi/l/pycroscopy.svg)](https://pypi.org/project/pyCroscopy/)
[![DOI](https://zenodo.org/badge/61456133.svg)](https://zenodo.org/badge/latestdoi/61456133)

**pycroscopy** is a [Python](http://www.python.org/) package for generic (domain-agnostic) microscopy data analysis. More specialized or domain-specific analysis routines are contained within some of the other packages within the pycroscopy ecosystem.

Please visit our [homepage](https://pycroscopy.github.io/pycroscopy/about.html) for more information and installation instructions.

If you use pycroscopy for research, we would appreciate if you could cite our [Arxiv paper](https://arxiv.org/abs/1903.09515) titled *"USID and Pycroscopy - Open frameworks for storing and analyzing spectroscopic and imaging data".*

## Examples:
1. **Intro to pycroscopy** - [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pycroscopy/pycroscopy/blob/main/jupyter_notebooks/Intro_to_Pycroscopy.ipynb)

2. **Image inpainting** - [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pycroscopy/pycroscopy/blob/main/jupyter_notebooks/Inpainting_example.ipynb)

3. **Denoising with Autoencoders** - [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pycroscopy/pycroscopy/blob/main/jupyter_notebooks/PycroscopyDenosingAutoencoder.ipynb)

## More examples in the [jupyter_notebooks](jupyter_notebooks/) folder.
## List of Workshops Held

### 2024
- **[Machine Learning in Scanning Transmission Electron Microscopy Workshop 2024, University of Tennessee, Knoville, TN](https://github.com/gduscher/MLSTEM2024)**

### 2023
- **[ML-ElectronMicroscopy-school-2023](https://github.com/SergeiVKalinin/ML-ElectronMicroscopy-2023)**

- **[AutomatedExperiment_Summer2023](https://github.com/SergeiVKalinin/AutomatedExperiment_Summer2023)**

### 2022
- **[FerroSchool Winter 2022 in Calgary](https://github.com/pycroscopy/ferroschool)**

### 2021
- **[Notebooks for MRS2021 tutorial](https://github.com/pycroscopy/MRS2021)**
- **[SPM_ML_School_2021](https://github.com/pycroscopy/SPM_ML_School_2021)**

### 2020  
- **[AISTEM Workshop 2020](https://github.com/pycroscopy/AISTEM_WORKSHOP_2020)**

### 2019  
- **[CNMS ML in MS Workshop 2019](https://github.com/pycroscopy/CNMS_ML_in_MS_Workshop_2019)** 

### 2018  
- **[CNMS ML in MS Workshop 2018](https://github.com/pycroscopy/CNMS_ML_in_MS_Workshop_2018)** 

- **[MM 2018 Workshop](https://github.com/pycroscopy/MM_2018_Workshop)**

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `jupyter_notebooks/`, `pycroscopy/`, `sample_data/`, `tests/`
- Snapshot size: **55 files**, **4270 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (25), `.ipynb` (9), `.txt` (6), `.jpg` (5), `.yml` (2), `(none)` (1)
- Upstream commit pinned for this packaging: `90e2d232acc9da634131c1793f082a70a04a3297`

---

## Installation

[![PyPI](https://img.shields.io/pypi/v/pycroscopy.svg)](https://pypi.org/project/pyCroscopy/)
[![Coverage](https://codecov.io/gh/pycroscopy/pycroscopy/branch/main/graph/badge.svg?token=HXGZMKzJqb)](https://codecov.io/gh/pycroscopy/pycroscopy)
[![Conda Forge](https://img.shields.io/conda/vn/conda-forge/pycroscopy.svg)](https://github.com/conda-forge/pycroscopy-feedstock)
[![License](https://img.shields.io/pypi/l/pycroscopy.svg)](https://pypi.org/project/pyCroscopy/)
[![DOI](https://zenodo.org/badge/61456133.svg)](https://zenodo.org/badge/latestdoi/61456133)

**pycroscopy** is a [Python](http://www.python.org/) package for generic (domain-agnostic) microscopy data analysis. More specialized or domain-specific analysis routines are contained within some of the other packages within the pycroscopy ecosystem.

Please visit our [homepage](https://pycroscopy.github.io/pycroscopy/about.html) for more information and installation instructions.

If you use pycroscopy for research, we would appreciate if you could cite our [Arxiv paper](https://arxiv.org/abs/1903.09515) titled *"USID and Pycroscopy - Open frameworks for storing and analyzing spectroscopic and imaging data".*

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
python -m pycroscopy    # module entry point, when the package layout matches
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `PYCROSCOPY` source tree vendored in `UPSTREAM_CLONE/` (Python ecosystem). Public entry points:

- Source modules: `jupyter_notebooks/`, `pycroscopy/`, `sample_data/`, `tests/`
- The snapshot declares 16 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml |
| Files in snapshot | 55 |
| Lines of code | 4270 |
| Dependency references | 16 |
| Dependencies by ecosystem | pypi: 16 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| pypi | numpy | - | pyproject.toml |
| pypi | scipy | - | pyproject.toml |
| pypi | scikit-image | - | pyproject.toml |
| pypi | scikit-learn | - | pyproject.toml |
| pypi | matplotlib | - | pyproject.toml |
| pypi | torch | - | pyproject.toml |
| pypi | tensorly | - | pyproject.toml |
| pypi | tqdm | - | pyproject.toml |
| pypi | ipywidgets | - | pyproject.toml |
| pypi | ipython | - | pyproject.toml |
| pypi | simpleitk | - | pyproject.toml |
| pypi | sidpy | - | pyproject.toml |
| pypi | pysptools | - | pyproject.toml |
| pypi | cvxopt | - | pyproject.toml |
| pypi | SciFiReaders | - | pyproject.toml |
| ... | (1 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `pyproject.toml`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `PYCROSCOPY` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2016 Suhas Somnath, Christopher R. Smith, Stephen Jesse and Nouamane Laanait.

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

- **Project:** `PYCROSCOPY` (category: SCIENTIFIC LAB)
- **Upstream URL:** https://github.com/pycroscopy/pycroscopy
- **Pinned commit (SHA):** `90e2d232acc9da634131c1793f082a70a04a3297`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`bbc28363ca73cc6bf0fc6c42222308a1b9926795a7cd5794b72e24405097b9f1`.

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
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

