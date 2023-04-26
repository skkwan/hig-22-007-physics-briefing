# HIG-22-007 physics briefing

https://twiki.cern.ch/twiki/bin/viewauth/CMS/PhysicsCommunication  

## Setup


(Optional) For ease of checking the [GitHub actions config file](.github/workflows/cd.yml), install and use [ActionLint](https://github.com/rhysd/actionlint).

```
brew install actionlint
```

## Workflow

To build the file into a `.pdf` locally,
```
pdflatex main.tex
```

Each commit should also trigger the GitHub action which builds a `.pdf` and uploads it to the Actions page.

(Optional) To call ActionLint:
```
actionlint .github/workflows/cd.yml
```