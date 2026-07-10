# PyAutoLabs

**Open-source astronomy software, developed by an AI scientist.**

PyAutoLabs is two things: a suite of Python libraries for Bayesian model-fitting, galaxy morphology and strong gravitational lensing — and **PyAutoScientist**, the AI-agent "organism" that plans, implements, tests and releases that software every day, with a human checkpointing the judgment calls.

## PyAutoScientist

[**PyAutoScientist**](https://pyautoscientist.readthedocs.io) is a working reference implementation of an AI-agent development organism: a set of repositories that together run a multi-repo software project end-to-end. It is not a framework you install — it is the live system that develops everything below, documented so you can fork it and run your own.

| Organ | Repo | Role |
|---|---|---|
| Mind | [**PyAutoMind**](https://github.com/PyAutoLabs/PyAutoMind) | Every piece of work starts here as a plain-English markdown file saying *what* to do. |
| Brain | [**PyAutoBrain**](https://github.com/PyAutoLabs/PyAutoBrain) | The reasoning layer that decides *how* — classifying, planning and routing each task through specialist agents. |
| Heart | [**PyAutoHeart**](https://github.com/PyAutoLabs/PyAutoHeart) | The health monitor whose GREEN/YELLOW/RED verdict is the authoritative "is it safe to release?" gate. |
| Hands | [**PyAutoBuild**](https://github.com/PyAutoLabs/PyAutoBuild) | The executor that packages, tags and releases the libraries to PyPI, nightly. |
| Memory | [**PyAutoMemory**](https://github.com/PyAutoLabs/PyAutoMemory) | Long-term scientific knowledge — cross-linked literature wikis the agents consult. |
| Nerves | [**PyAutoConf**](https://github.com/PyAutoLabs/PyAutoConf) | The configuration and serialization layer (`autoconf`) connecting the organism's conventions to every library. |

## The science stack

The software the organism builds — used by researchers worldwide for reproducible, automated astronomical data analysis:

| Package | Role | Install |
|---|---|---|
| [**PyAutoFit**](https://github.com/PyAutoLabs/PyAutoFit) | Probabilistic programming: model composition, non-linear search and Bayesian inference. | `pip install autofit` |
| [**PyAutoGalaxy**](https://github.com/PyAutoLabs/PyAutoGalaxy) | Multi-wavelength modeling of galaxy light, mass and morphology. | `pip install autogalaxy` |
| [**PyAutoLens**](https://github.com/PyAutoLabs/PyAutoLens) | Strong gravitational lens modeling, from Hubble to Euclid and JWST. | `pip install autolens` |
| [**PyAutoReduce**](https://github.com/PyAutoLabs/PyAutoReduce) | Reduces archival telescope imaging into modeling-ready datasets for the stack above. | — |

Under the hood sits [**PyAutoArray**](https://github.com/PyAutoLabs/PyAutoArray) (data structures, grids and inversions).

Each library has a companion workspace of examples and tutorials — start with [autolens_workspace](https://github.com/PyAutoLabs/autolens_workspace) — or point an AI assistant (Claude, ChatGPT) at [autolens_assistant](https://github.com/PyAutoLabs/autolens_assistant) and just ask.

## Getting started

```bash
pip install autolens
git clone https://github.com/PyAutoLabs/autolens_workspace
cd autolens_workspace
python welcome.py
```

Documentation for every project is collected at [**pyautolabs.github.io**](https://pyautolabs.github.io).

## Citation

If you use PyAutoLabs software in your research, please cite:

> Nightingale, J. W. et al. (2021). *PyAutoLens: Open-Source Strong Gravitational Lensing.* JOSS, 6(58), 2825.

## License

All PyAutoLabs packages are released under the [MIT License](https://opensource.org/licenses/MIT).
