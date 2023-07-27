# Large Language Model for performing CRUD Operations in Database
---
## Dependencies (MacOS - (Intel or M1))
> Install homebrew natively with the following command.
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
> Install anaconda with the following command.
```bash
brew install --cask anaconda
```
Add anaconda to Path
```bash
export PATH="/usr/local/anaconda3/bin:$PATH"
```
or
```bash
export PATH="/opt/homebrew/anaconda3/bin:$PATH"
```
depending on where the anaconda is installed.

---
## Dependencies (Windows)
> Install anaconda via this link [Anaconda](https://www.anaconda.com/download#downloads) or follow the steps from: https://www.datacamp.com/tutorial/installing-anaconda-windows
---

#### For Mac M1 chipset install the requirements using following command
```bash
conda env create -f arm64_requirement.yml
```
and use command to activate environment
```bash
conda activate llm_nlp_arm64
```

#### For other chipsets (Windows or Mac) install the requirements using following command
```bash
conda env create -f x8664_requirement.yml
```
and use command to activate environment
```bash
conda activate llm_nlp_x86-64
```