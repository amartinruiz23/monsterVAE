# monsterVAE

Original images [here](https://veekun.com/dex/downloads), fourth and fifth
generation sprites used.

## Usage

This project is in development. These instructions are for installing
dependencies running the code as it is currently in Jupyter.

### Install dependencies

We provide a `pyproject.toml` as well as a `requirements.txt` file.
`requirements.txt` contains the pinned versions for the packages we are
currently using. We recommend that you create a [virtual
environment](https://docs.python.org/3/tutorial/venv.html) and install
these dependencies there.  You can install them with:
```
pip install -r requirements.txt
```

### Run in Jupyter

Assuming you have Jupyter installed, you can add a custom kernel that will let
you run a notebook in the virtual environment you created before. Make sure to
activate the virtual environment and run:
```
python -m ipykernel install --user --name=<venv-name>
```

Now, you should be able to open Jupyter and run the notebooks in this project
and run them with the `<venv-name>` kernel.
