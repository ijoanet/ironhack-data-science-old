# Ironhack Data Science Bootcamp

Repository made to store learning materials provided by Ironhack Data Science Bootcamp and deliver the required exercises.

Exercises can be found at `labs`.

## Getting started

Sync `git submodules`
```bash
git submodule update --init --recursive
```

In MacOS, if you are using `homebrew` you will experience a hard time to download `python` packages.
My suggestion is to use `conda` that allows you to create environments and download packages for your `python` applications.
```bash
brew install miniconda

# Add conda to your $PATH
conda init
# If you are using zsh, you will need to use (use `echo $SHELL` to know)
conda init zsh
```

Create an environment for this project, to avoid polluting your local machine
```bash
conda create -f environment.yml
# Activate environment
conda activate ironhack-ds
```

Start Jupiter Notebook Server
```bash
jupiter notebook
```


