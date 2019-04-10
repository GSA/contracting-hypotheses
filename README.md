# contracting-hypotheses
Statistical Tests for Federal Contracting Hypotheses

In the Fall/Winter of 2018, [OGP Evidence & Analysis](https://www.gsa.gov/about-us/organization/office-of-governmentwide-policy/office-of-evidence-and-analysis) prepared an analysis of government-wide contracting data with the objective of identifying the characterisitcs of a high performing contracting office. The results of the analysis were presented 12/3 - 12/4/18 at the Government Contract Management Symposium.

This repository provides a jupyter notebook for each of the statistical analyses involved in that presentation. Each notebook documents:
 - the data source
 - the unit of analysis
 - decisions made to prep/clean the data, including how missing values and/or data quality issues were addressed
 - reasoning behind the model selection, including the statistical tests used to validate the model's assumptions
 - interpretation of the model summary


## Getting Started

### Prerequisites

First, you'll need Python 3.7. We recommend using `pyenv` to get this (as well as other versions of Python).

Then you'll need Jupyter Notebook. You can find directions on how to get that [here](https://jupyter.org/install). They recommend downloading Anaconda to get it, but we suggest using `pip` if you're already using `pyenv` to manage your python versions.

Then you'll want to clone this repo and `cd` in to it:

```bash
git clone git@github.com:GSA/contracting-hypotheses.git
cd contracting-hypotheses
```

We use `pipenv` for a virtual environment. You can find instructions on installing that [here](https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv).

Once you've got `pipenv` installed, you can start up the virtual environment using:

```bash
pipenv install
```

Next, activate the Pipenv shell:

```bash
pipenv shell
```

This will spawn a new shell subprocess, which can be deactivated by using `exit`.

One of the required packages you just installed is `ipykernel`. We use this to create a kernel that uses our virtual enivronment for the Jupyter Notebook:

```bash
ipython kernel install --user --name=contracting-hypotheses
```

At this point, you can start jupyter with `jupyter notebook`. When you open a notebook, be sure you're using the kernel you created(contracting-hypotheses).

## Contributing

Please read [CONTRIBUTING.md](https://github.com/GSA/contracting-hypotheses/blob/master/CONTRIBUTING.MD) for details on our code of conduct and the process for submitting pull requests to us.


## License

This project is licensed under the Creative Commons Zero v1.0 Universal License - see the [LICENSE.md](https://github.com/GSA/contracting-hypotheses/blob/master/LICENSE) file for details.
