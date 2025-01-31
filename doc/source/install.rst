.. install:

**********************
Setting up pygfunction
**********************

*pygfunction* uses Python 3.7, along with the following packages:
	- Coolprop (>= 6.4.1)
	- matplotlib (>= 3.3.4),
	- numpy (>= 1.20.1)
	- scipy (>= 1.6.2)

*pygfunction*'s- documentation is built using:
	- sphinx (>= 4.0.1)
	- numpydoc (>= 1.1.0)

**Users** - `Download pip <https://pip.pypa.io/en/latest/>`_ and install the
latest release:

```
pip install pygfunction
```

Alternatively, `download the latest release
<https://github.com/MassimoCimmino/pygfunction/releases>`_ and run the
installation script:

```
pip install .
```

**Developers** - To get the latest version of the code, you can `download the
repository from github <https://github.com/MassimoCimmino/pygfunction>`_ or
clone the project in a local directory using git:

```
git clone https://github.com/MassimoCimmino/pygfunction.git
```

Install *pygfunction* in development mode (this requires `pip >= 21.1`):
```
pip install --editable .
```

Test that *pygfunction* is running correctly by running any of the
provided examples in ``../pygfunction/examples/``
