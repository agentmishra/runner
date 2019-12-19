# GitHub Actions Runner

<p align="center">
  <img src="docs/res/github-graph.png">
</p>

[![Actions Status](https://github.com/actions/runner/workflows/Runner%20CI/badge.svg)](https://github.com/actions/runner/actions)

## Get Started

The runner is the application that runs a job from a GitHub Actions workflow.  The runner can run on the [hosted machine pools](https://github.com/actions/virtual-environments) or run on [self-hosted environments](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/about-self-hosted-runners).

For more information about installing and using self-hosted runners, see [Adding self-hosted runners](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/adding-self-hosted-runners) and [Using self-hosted runners in a workflow](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/using-self-hosted-runners-in-a-workflow)

Runner releases:

![win](docs/res/win_sm.png) [Pre-reqs](docs/start/envwin.md) | [Download](https://github.com/actions/runner/releases)  

![macOS](docs/res/apple_sm.png)  [Pre-reqs](docs/start/envosx.md) | [Download](https://github.com/actions/runner/releases)  

![linux](docs/res/linux_sm.png)  [Pre-reqs](docs/start/envlinux.md) | [Download](https://github.com/actions/runner/releases)

**Configure:**

*MacOS and Linux*
```bash
./config.sh
```

*Windows*
```bash
config.cmd
```

## Contribute

We accept contributions in the form of issues and pull requests.  [Read more here](docs/contribute.md) before contributing.
