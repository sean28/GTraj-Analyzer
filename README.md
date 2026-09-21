# GTraj Analyzer

**GTraj Analyzer** is a cross platform framework for GROMACS based molecular dynamics trajectory analysis with an extensible AI Agent module.

The software is designed for server deployment on macOS and Linux. Conventional trajectory analyses are executed through predefined GROMACS based workflows, while the optional AI Agent module assists with natural language task configuration and structured parameter generation.

## Project status

This repository is being prepared for the public release of **GTraj Analyzer v1.0**.

Source code, the complete software package, example data, and the downloadable runtime environment will be added during the formal software release.

## Planned analysis modules

RMSD, RMSF, radius of gyration, SASA, conformational clustering, distance analysis, hydrogen bond analysis, PCA, and additional extensible analysis modules.

The AI Agent is an optional component and is not required for conventional trajectory analysis.

## Repository structure

```text
GTraj-Analyzer/
├── gtraj/                 Main program source
│   ├── script/            GROMACS analysis modules
│   └── templates/         Web interface templates
├── docs/                  Documentation
│   └── screenshots/       Interface screenshots
├── examples/              Minimal test data and examples
├── tests/                 Test files
├── environment/           Runtime environment download information
├── releases/              Release notes and package information
└── .github/               GitHub issue templates
```

## Platform

Supported platforms:

* macOS
* Linux

Main external dependency:

* GROMACS

The complete preconfigured environment will be distributed separately because of its file size.

## Downloads

### Software package

The complete **GTraj Analyzer v1.0** package will be provided through GitHub Releases.

### Preconfigured environment

A public Google Drive download link for the preconfigured runtime environment will be added to:

`environment/README.md`

## Documentation

Installation instructions and user documentation will be available in the `docs/` directory.

## Citation

The accompanying manuscript is currently in preparation. Citation information will be added after publication.

## Contact

Issues and software feedback can be submitted through the GitHub Issues page.
