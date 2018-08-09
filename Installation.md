# Installation steps

## Verify Python version

```bash

python --version

```

## Install Anaconda using `Homebrew`

```bash

brew cask install anaconda2

```

## Add anaconda to the system PATH

```bash

/usr/local/anaconda2/bin

```

## Restart iTerm2 & verify packages installed as part of Anaconda installation

```bash

conda list

```

## Jupyter Notebook

```bash

jupyter notebook

```

## Install `cookiecutter` project template using pip

```bash

sudo pip install cookiecutter

```

## Alternate approach using conda install

```bash

conda install cookiecutter

```

### Add `conda-forge` channel to overcome the `PackageNotFound` error

```bash

conda install -c conda-forge cookiecutter

```

### Create data science project named `titanic` using the cookiecutter

```bash

cookiecutter https://github.com/drivendata/cookiecutter-data-science

```