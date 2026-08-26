# SPUTRA

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22115029.svg)]
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](../../releases)

**Monte Carlo simulation software for magnetron sputter deposition. **

SPUTRA couples an SRIM-type target-emission stage with a SIMTRA-type
gas-phase transport stage in a single integrated environment. It models the
sputtered-particle chain from emission at the target, through elastic
scattering in the working gas, to deposition on the substrate, and provides
built-in visualization, parametric sweeps, and results export.

The software is distributed as a self-contained Windows executable; no Python
installation is required to run it.

## Physics

* Sputtering yield (SRIM-type / Yamamura-Tawara analytic yields)
* Sigmund-Thompson emission-energy distribution
* Cosine (Lambert) angular emission
* Kinetic-theory mean free path with an energy-dependent correction
* Hard-sphere binary-collision energy transfer (mass-dependent mean
fractional loss per collision)
* Isotropic post-collision direction sampling
* Three-channel particle-fate accounting (deposited / wall-lost /
thermalized), exactly conserved

## Features

* Coupled emission and transport in a single run
* Reactive-gas support
* Two-dimensional deposition heatmaps
* Radial thickness profiles
* Three-dimensional trajectory visualization
* Automated pressure sweeps
* Integrated verification and validation
* Export of numerical results and figures (CSV / JSON / PNG)

## Download and run (Windows)

1. Open the [Releases](../../releases) page.
2. Download `SPUTRA.exe`.
3. Double-click to launch.

> The executable is unsigned. On first launch, Windows SmartScreen may show a
> warning; choose **More info -> Run anyway**.

## Citing this software

If you use SPUTRA in your research, please cite it as:

> Bouazza, A. (2026). *SPUTRA: Monte Carlo simulation software for
> magnetron sputter deposition* (Version 1.0.0) [Software]. Zenodo.
> <!-- DOI to be added once the Zenodo deposit is published -->

A machine-readable citation is provided in [`CITATION.cff`](CITATION.cff).

## License

Released under the MIT License. See [`LICENSE`](LICENSE).

## Author

**Abdelkader Bouazza**
[ORCID: 0000-0002-9979-8977](https://orcid.org/0000-0002-9979-8977)
L2GEGI Laboratory, University of Tiaret, Algeria
