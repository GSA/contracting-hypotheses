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
First, you'll need Jupyter Notebook. You can find directions on how to get that [here](https://jupyter.org/install).

Then you'll want to install the packages we use.

You can either install them globally

```bash
cd path/to/this/locally/cloned/repo
pip install -r requirements.txt
```

or create a virtual environment using [venv](https://docs.python.org/3/library/venv.html):

```bash
cd path/to/this/locally/cloned/repo
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

### Launch Jupyter
Once you've got jupyter and the Python dependencies, you can launch Jupyter and then open these notebooks:

```bash
cd path/to/this/locally/cloned/repo
jupyter notebook
```

The above will open Jupyter in your browser, using this repo as the root directory. From there, you can navigate to the notebooks and open them.

## Contributing
Please read [CONTRIBUTING.md](https://github.com/GSA/contracting-hypotheses/blob/master/CONTRIBUTING.MD) for details on our code of conduct, and the process for submitting pull requests to us.


## License

This project is licensed under the Creative Commons Zero v1.0 Universal License - see the [LICENSE.md](https://github.com/GSA/contracting-hypotheses/blob/master/LICENSE) file for details.
