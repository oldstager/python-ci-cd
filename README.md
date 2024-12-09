# python-ci-cd

Example of CI/CD pipelines in Python using Github Actions.

![Build status](https://github.com/oldstager/python-ci-cd/actions/workflows/python-app.yml/badge.svg)

## Preparation

1.  Install [Micromamba](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html)
2.  Create environment with Python 3.13 as its default Python: `micromamba create -n py313-ci-cd python=3.13`
3.  Activate the environment: `micromamba activate py313-ci-cd`
4.  Install packages: `pip install hypercorn fastapi[standard] flake8 pytest`

## Run

```bash
$ hypercorn server:app
```

## Test

```bash
$ pytest
```

