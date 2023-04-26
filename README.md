# HIG-22-007 physics briefing

https://twiki.cern.ch/twiki/bin/viewauth/CMS/PhysicsCommunication  

## Setup

For ease of checking the [GitHub actions config file](.github/workflows/cd.yml), install and use [ActionLint](https://github.com/rhysd/actionlint).

```
brew install actionlint
```

## Workflow

To call ActionLint:
```
actionlint .github/workflows/cd.yml
```