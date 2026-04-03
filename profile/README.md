# PyAutoLabs

**Open-source scientific software for automated astronomical data analysis.**

PyAutoLabs develops and maintains a suite of interconnected Python libraries for Bayesian inference, galaxy morphology modeling, and strong gravitational lensing. Our tools are used by researchers worldwide to model complex astrophysical systems with reproducible, automated pipelines.

---

## Core Libraries

| Package | Description | Install |
|---|---|---|
| [**PyAutoFit**](https://github.com/rhayes-ceu/PyAutoFit) | Probabilistic programming & model fitting | `pip install autofit` |
| [**PyAutoArray**](https://github.com/PyAutoLabs/PyAutoArray) | Array, grid & data structure manipulation | `pip install autoarray` |
| [**PyAutoGalaxy**](https://github.com/PyAutoLabs/PyAutoGalaxy) | Multi-wavelength galaxy structure & morphology | `pip install autogalaxy` |
| [**PyAutoLens**](https://github.com/PyAutoLabs/PyAutoLens) | Strong gravitational lens modeling | `pip install autolens` |

## Workspaces (Examples & Tutorials)

Each core library has a companion workspace with example scripts, configuration files, and datasets:

- [autolens_workspace](https://github.com/PyAutoLabs/autolens_workspace) -- PyAutoLens examples, tutorials & datasets
- [autofit_workspace](https://github.com/PyAutoLabs/autofit_workspace) -- PyAutoFit examples & HowToFit lectures
- [autogalaxy_workspace](https://github.com/PyAutoLabs/autogalaxy_workspace) -- PyAutoGalaxy examples & tutorials

## Getting Started

```bash
pip install autolens
git clone https://github.com/PyAutoLabs/autolens_workspace
cd autolens_workspace
python welcome.py
```

Check out the [PyAutoLens documentation](https://pyautolens.readthedocs.io/) for comprehensive guides, API references, and scientific background.

## Contributing

We welcome contributions from the community! See our [Contributing Guidelines](https://github.com/PyAutoLabs/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/PyAutoLabs/.github/blob/main/CODE_OF_CONDUCT.md).

## Citation

If you use PyAutoLabs software in your research, please cite:

> Nightingale, J. W. et al. (2021). *PyAutoLens: Open-Source Strong Gravitational Lensing.* JOSS, 6(58), 2825.

## License

All PyAutoLabs packages are released under the [MIT License](https://opensource.org/licenses/MIT).
