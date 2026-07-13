# PyAutoLabs

**An agentic AI ecosystem for human-led, natural-language software development.**

You describe what you want in plain English; an organism of AI agents plans, builds, tests and releases it — with you making every judgment call. PyAutoLabs is where that ecosystem, **PyAutoScientist**, develops open-source astronomy software for Bayesian model-fitting, galaxy morphology and strong gravitational lensing, every day.

## PyAutoScientist

[**PyAutoScientist**](https://github.com/PyAutoLabs/PyAutoScientist) is a working reference implementation of a human-led AI development organism: a set of repositories through which plain-English intent becomes tested, released software, with a human directing the work and checkpointing every decision that matters. It is not a framework you install — it is the live system that develops everything below, documented so you can fork it and lead your own. Read the [docs](https://pyautoscientist.readthedocs.io).

| Organ | Repo | Role |
|---|---|---|
| Mind | [**PyAutoMind**](https://github.com/PyAutoLabs/PyAutoMind) | Where you lead: every piece of work starts here as a plain-English markdown file saying *what* to do. |
| Brain | [**PyAutoBrain**](https://github.com/PyAutoLabs/PyAutoBrain) | The reasoning layer that works out *how* — classifying, planning and routing each task through specialist agents. |
| Heart | [**PyAutoHeart**](https://github.com/PyAutoLabs/PyAutoHeart) | The health monitor whose GREEN/YELLOW/RED verdict is the authoritative "is it safe to release?" gate. |
| Hands | [**PyAutoBuild**](https://github.com/PyAutoLabs/PyAutoBuild) | The executor that packages, tags and releases the libraries to PyPI, nightly. |
| Memory | [**PyAutoMemory**](https://github.com/PyAutoLabs/PyAutoMemory) | Long-term scientific knowledge — cross-linked literature wikis the agents consult. |
| Nerves | [**PyAutoConf**](https://github.com/PyAutoLabs/PyAutoConf) | The configuration and serialization layer (`autoconf`) connecting the organism's conventions to every library. |

The software the organism develops is organised as three families, each a library plus the repos a working scientist needs around it.

## PyAutoFit

Probabilistic programming: model composition, non-linear search and Bayesian inference (`pip install autofit`).

| Repo | Role |
|---|---|
| [**PyAutoFit**](https://github.com/PyAutoLabs/PyAutoFit) | The instrument — the model-fitting and statistical inference library itself. |
| [autofit_workspace](https://github.com/PyAutoLabs/autofit_workspace) | Where the scientist works — example scripts, pipelines and configuration. |
| [HowToFit](https://github.com/PyAutoLabs/HowToFit) | The classroom — narrative lectures teaching model fitting from first principles. |
| [autofit_assistant](https://github.com/PyAutoLabs/autofit_assistant) | The AI research assistant — point Claude or ChatGPT at it and ask. |
| [autofit_workspace_test](https://github.com/PyAutoLabs/autofit_workspace_test) | The referee — regression checks that every result still reproduces. |

## PyAutoLens

Strong gravitational lens modeling, from Hubble to Euclid and JWST (`pip install autolens`).

| Repo | Role |
|---|---|
| [**PyAutoLens**](https://github.com/PyAutoLabs/PyAutoLens) | The instrument — the strong-lens modeling library itself. |
| [autolens_workspace](https://github.com/PyAutoLabs/autolens_workspace) | Where the lensing scientist works — example scripts, pipelines and datasets. |
| [HowToLens](https://github.com/PyAutoLabs/HowToLens) | The classroom — narrative lectures teaching lens modeling from first principles. |
| [autolens_assistant](https://github.com/PyAutoLabs/autolens_assistant) | The AI research assistant — point Claude or ChatGPT at it and ask. |
| [autolens_workspace_test](https://github.com/PyAutoLabs/autolens_workspace_test) | The referee — regression checks that every result still reproduces. |
| [autolens_workspace_developer](https://github.com/PyAutoLabs/autolens_workspace_developer) | The back-room workbench — developer scripts and experiments. |
| [autolens_profiling](https://github.com/PyAutoLabs/autolens_profiling) | The stopwatch — JAX likelihood performance runs and results. |

## PyAutoGalaxy

Multi-wavelength modeling of galaxy light, mass and morphology (`pip install autogalaxy`).

| Repo | Role |
|---|---|
| [**PyAutoGalaxy**](https://github.com/PyAutoLabs/PyAutoGalaxy) | The instrument — the galaxy structure and morphology library itself. |
| [autogalaxy_workspace](https://github.com/PyAutoLabs/autogalaxy_workspace) | Where the galaxy scientist works — example scripts, pipelines and datasets. |
| [HowToGalaxy](https://github.com/PyAutoLabs/HowToGalaxy) | The classroom — narrative lectures teaching galaxy modeling from first principles. |
| [autogalaxy_workspace_test](https://github.com/PyAutoLabs/autogalaxy_workspace_test) | The referee — regression checks that every result still reproduces. |

*(An autogalaxy_assistant is on the way.)*

Under the hood sit [**PyAutoArray**](https://github.com/PyAutoLabs/PyAutoArray) (data structures, grids and inversions) and [**PyAutoReduce**](https://github.com/PyAutoLabs/PyAutoReduce) (reducing archival telescope imaging into modeling-ready datasets).

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
