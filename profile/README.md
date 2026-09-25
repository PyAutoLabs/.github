# PyAutoLabs

**Open-source software for Bayesian inference, galaxy morphology and strong gravitational lensing.**

PyAutoLabs develops scientific libraries, example workspaces and tutorial courses
for model fitting and astronomy, from general-purpose probabilistic programming
to galaxy structure and strong-lens modeling.

## Community

Questions, help with your code or your analysis, and ideas: the
[PyAutoLabs Discussions](https://github.com/orgs/PyAutoLabs/discussions).
Bug reports with a reproducer (a snippet, the traceback, your versions):
an issue on the library's tracker. The Slack is for collaborators, by
invitation.

The software is organised as three families, each a library plus the repositories
a working scientist needs around it.

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
| [autolens_inference](https://github.com/PyAutoLabs/autolens_inference) | The proving ground — which searches find the right lens model fastest, on CPU and A100. |

## PyAutoGalaxy

Multi-wavelength modeling of galaxy light, mass and morphology (`pip install autogalaxy`).

| Repo | Role |
|---|---|
| [**PyAutoGalaxy**](https://github.com/PyAutoLabs/PyAutoGalaxy) | The instrument — the galaxy structure and morphology library itself. |
| [autogalaxy_workspace](https://github.com/PyAutoLabs/autogalaxy_workspace) | Where the galaxy scientist works — example scripts, pipelines and datasets. |
| [HowToGalaxy](https://github.com/PyAutoLabs/HowToGalaxy) | The classroom — narrative lectures teaching galaxy modeling from first principles. |
| [autogalaxy_workspace_test](https://github.com/PyAutoLabs/autogalaxy_workspace_test) | The referee — regression checks that every result still reproduces. |
| [autogalaxy_assistant](https://github.com/PyAutoLabs/autogalaxy_assistant) | The AI research assistant — point Claude or ChatGPT at it and ask. |

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
>
> Nightingale, J. W. et al. (2021). *PyAutoFit: A Classy Probabilistic Programming Language for Model Composition and Fitting.* JOSS, 6(58), 2550.
>
> Nightingale, J. W. et al. (2023). *PyAutoGalaxy: Open-Source Multiwavelength Galaxy Structure & Morphology.* JOSS, 8(81), 4475.

## License

All PyAutoLabs packages are released under the [MIT License](https://opensource.org/licenses/MIT).

## PyAutoScientist

[**PyAutoScientist**](https://github.com/PyAutoLabs/PyAutoScientist) is
Jammy2211's experimental, vibe-coded AI software development ecosystem. Visitors
are welcome to explore the [documentation](https://pyautoscientist.readthedocs.io)
and the repositories below, but contributors are not currently expected to use
it. Jammy2211 hopes to make it software that others can easily use one day.

<!-- repos_sync:organs:begin -->
| Organ | Repo | Role |
|---|---|---|
| Brain | [**PyAutoBrain**](https://github.com/PyAutoLabs/PyAutoBrain) | Works out *how*: classifies, plans and routes work through specialist reasoning and coding agents. |
| Mind | [**PyAutoMind**](https://github.com/PyAutoLabs/PyAutoMind) | Captures intent: every piece of work begins as a plain-English description of *what* should change and is tracked from the initial idea to its completed implementation. |
| Cortex | [**PyAutoCortex**](https://github.com/PyAutoLabs/PyAutoCortex) | Holds the science body map and one ledger per science project — the runs on the cluster and a dated log of what was set off, seen and learned — so a project is picked up where it was left, apart from software development. |
| Memory | [**PyAutoMemory**](https://github.com/PyAutoLabs/PyAutoMemory) | Provides long-term scientific knowledge through cross-linked literature wikis, concepts and verifiable citations. |
| Heart | [**PyAutoHeart**](https://github.com/PyAutoLabs/PyAutoHeart) | Monitors repository health and supplies the authoritative GREEN/YELLOW/RED release-readiness verdict. |
| Hands | [**PyAutoHands**](https://github.com/PyAutoLabs/PyAutoHands) | Executes builds and releases: packages libraries, generates notebooks, creates tags and publishes releases to PyPI. |
| Nerves | [**PyAutoNerves**](https://github.com/PyAutoLabs/PyAutoNerves) | Provides the configuration and serialization layer connecting shared conventions across the scientific libraries and workspaces. |
| Gut | [**PyAutoGut**](https://github.com/PyAutoLabs/PyAutoGut) | Holds stale branches, dead code and other condemned material as recoverable Git references before it is permanently removed. |
| Eyes | [**PyAutoEyes**](https://github.com/PyAutoLabs/PyAutoEyes) | Holds the rendered gallery of every figure each PyAuto library draws, on realistic data, so what the software shows can be seen, judged and improved in one place. |
<!-- repos_sync:organs:end -->
