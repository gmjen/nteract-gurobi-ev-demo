# Gurobi EV charging in nteract

A complete optimization workshop in one notebook. nteract installs its dependencies automatically; the data is included.

1. **[Download and install nteract](https://www.nteract.io/)** if you haven't already. It is required to run this notebook with automatic dependency setup.
2. **[Download the notebook](https://github.com/gmjen/nteract-gurobi-ev-demo/releases/latest/download/gurobi_ev_conda.ipynb).**
3. Open the downloaded `.ipynb` file in nteract.
4. Approve the notebook's dependencies when prompted, then wait for setup to finish.
5. Choose **Run All**.

No terminal commands, separate Python installation, or data files needed. Initial setup requires internet access. These small examples work with Gurobi's included restricted license; the 3,000-vehicle example is intentionally infeasible.

Tested with nteract 2.7.6 on macOS (Apple Silicon): all 58 code cells passed. Other platforms have not been tested.

Adapted from the completed [Gurobi EV Charging Example](https://github.com/spurschke98/Gurobi-EV-Charging-Example/tree/42f7d1a814e03fa01ef926d84b3a8adf03354aff), with notebook-managed conda dependencies and embedded CSV data.
