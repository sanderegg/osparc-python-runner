# osparc-python-runner

oSparc Python Runner
![Github-CI](https://github.com/ITISFoundation/osparc-python-runner/workflows/Github-CI%20Push/PR%20osparc-python-runner/badge.svg)

## Description

oSparc service that allows running any python-based script either as simple script of complex python application inside a zip file (with or without requirements.txt file)


## Development

```console
make help

make devenv
source .venv/bin/activate
make build
make info-build
make tests
```

## CI/CD Integration

### Github-Actions

[github-ci.yml](https://github.com/ITISFoundation/osparc-python-runner/blob/master/.github/workflows/github-ci.yml)
