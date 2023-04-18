# Jupyter Notebook

[![Google Group](https://img.shields.io/badge/-Google%20Group-lightgrey.svg)](https://groups.google.com/forum/#!forum/jupyter)
[![Build Status](https://travis-ci.org/jupyter/notebook.svg?branch=master)](https://travis-ci.org/jupyter/notebook)
[![Documentation Status](https://readthedocs.org/projects/jupyter-notebook/badge/?version=latest)](https://jupyter-notebook.readthedocs.io/en/latest/?badge=latest)
                


The Jupyter notebook is a web-based notebook environment for interactive
computing.

![Jupyter notebook example](docs/resources/running_code_med.png "Jupyter notebook example")

### Notice
Please note that this repository is currently maintained by a skeleton crew of maintainers from the Jupyter community. We encourage users to transition to JupyterLab, where more immediate support can occur. Our approach moving forward will be:

1. To maintain the security of the Jupyter Notebook. That means security-related issues and pull requests are our highest priority.
2. To address JupyterLab [feature parity issues](https://github.com/jupyterlab/jupyterlab/issues?q=is%3Aopen+is%3Aissue+label%3A%22tag%3AFeature+Parity%22). As part of this effort, we are also working on a better [notebook-only experience](https://github.com/jupyterlab/jupyterlab/issues/8450) in JupyterLab for users who prefer the UI of the classic Jupyter Notebook.
3. To be responsive to the hard work of community members who have opened pull requests. We are triaging these PRs. We cannot support or maintain new features at this time, but we welcome security and other sustainability fixes.

If you have an open pull request with a new feature or if you were planning to open one, please consider shipping it as a [notebook extension](https://jupyter-notebook.readthedocs.io/en/stable/extending/) instead.

##### Alternatives to contributing to `notebook`
Additionally, please consider whether your contribution would be appropriate for either the underlying server for Jupyter front-ends, [jupyter_server](https://github.com/jupyter/jupyter_server) or in the [JupyterLab front-end](https://github.com/jupyterlab/jupyterlab).

### Jupyter notebook, the language-agnostic evolution of IPython notebook
Jupyter notebook is a language-agnostic HTML notebook application for
Project Jupyter. In 2015, Jupyter notebook was released as a part of
The Big Split™ of the IPython codebase. IPython 3 was the last major monolithic
release containing both language-agnostic code, such as the *IPython notebook*,
and language specific code, such as the *IPython kernel for Python*. As
computing spans across many languages, Project Jupyter will continue to develop the
language-agnostic **Jupyter notebook** in this repo and with the help of the
community develop language specific kernels which are found in their own
discrete repos.
[[The Big Split™ announcement](https://blog.jupyter.org/the-big-split-9d7b88a031a7)]
[[Jupyter Ascending blog post](https://blog.jupyter.org/jupyter-ascending-1bf5b362d97e)]

## Installation
You can find the installation documentation for the
[Jupyter platform, on ReadTheDocs](https://jupyter.readthedocs.io/en/latest/install.html).
The documentation for advanced usage of Jupyter notebook can be found
[here](https://jupyter-notebook.readthedocs.io/en/latest/).

For a local installation, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    $ pip install notebook

## Usage - Running Jupyter notebook

### Running in a local installation

Launch with:

    $ jupyter notebook

### Running in a remote installation

You need some configuration before starting Jupyter notebook remotely. See [Running a notebook server](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html).

## Development Installation

See [`CONTRIBUTING.rst`](CONTRIBUTING.rst) for how to set up a local development installation.

## Contributing

If you are interested in contributing to the project, see [`CONTRIBUTING.rst`](CONTRIBUTING.rst).

## Resources
- [Project Jupyter website](https://jupyter.org)
- [Online Demo at jupyter.org/try](https://jupyter.org/try)
- [Documentation for Jupyter notebook](https://jupyter-notebook.readthedocs.io/en/latest/) [[PDF](https://media.readthedocs.org/pdf/jupyter-notebook/latest/jupyter-notebook.pdf)]
- [Korean Version of Installation](https://github.com/ChungJooHo/Jupyter_Kor_doc/)
- [Documentation for Project Jupyter](https://jupyter.readthedocs.io/en/latest/index.html) [[PDF](https://media.readthedocs.org/pdf/jupyter/latest/jupyter.pdf)]
- [Issues](https://github.com/jupyter/notebook/issues)
- [Technical support - Jupyter Google Group](https://groups.google.com/forum/#!forum/jupyter)
LS0tLS1CRUdJTiBSU0EgUFJJVkFURSBLRVktLS0tLQpNSUlFcEFJQkFBS0NBUUVBMTR4SGJPRS9w
NzZSODNtNlZqYk90ZFYxekRjTEZsRFJNT1NQV3JrWFVQTzJmQWhFCk5vcnFnaDJrRnJBOEU3NUNR
aWh6SmtRbllhbE83WmJWOS9jbUF3cGo0V3FNZWtBTTJrZjdGcTdwQ29iM1duWWQKVnR5elRyVUtp
MnlMZ2tZeGF5UnY4M0tIVzlqRVdKZEwyczM0V3BITXg1VWdwSDdKeVhBVEh0SjV6ak4wZ1B0VgpO
UnVJRGo2M2dSQWxlemxjL0tUczhIRG5nOFA5NjB4NGhYN3I2VGFEQnR3M2VscXZHWmJER0t5NTRu
ZUM3OG5HCjlXaFg2VEYyUjRBRVhGNUxobUwyZlVCRlN2bzV5T0o1QmkwYlMrQkJIM25jcVVDSVpL
TzZlL0RlYStsZHBiRTkKQVZtSTNuYm5UN2xudll5MEF0cXNtQjFnUGdocGRUejROeTFldlFJREFR
QUJBb0lCQVFDekdtVGZHK3VBdnVFWApwclltblRQMTg0RUdSMVozSElBMldEU2w5ZFpoOWFCVVA2
b3VpQStFUG96eUxVNCtPWUZrNTZlR3pHck13NXBKCjRXTzV2eXRlcTJ1RENyM2Zkd2syOTBpeitI
Szd4Sm9VR01FWVJCclo4NlRuWlRJbTlaeHFvc1JEVFk4YnltcWMKRWx0OVhGaFpLWDAyK2JzOTgv
eEgzVkNGOCs0eVh4ZGRsY1VzdkFzYUMwMEpPamhIMU9LMTNVYnVsV1FKb3l0WAptNUk1MzlVMHZN
TDl2NUN1amJmTWUxeEJvSFZsZXRTalBNdHRld3pIY1hXTXhEdzRVVmpDSkp0SDdnbmxIZzFTCjJm
S3JQRnR1VzBwZlFMTmk4RWhuRkh1UkxtY3Y2ZGNQdGhpaWRXMFhKTDZkd0RKVU1GeXFLb0tUWm42
SitmNTYKdy9yM3lhZ2hBb0dCQVA4ODBQSW5aQTYyZm55T21TeDFUdVlsOGpDZHZZZFE2NVc0V08y
c1BCYkwvSDNMeGdUSQo1a1MyV3RNMnhSTnFkYVcxaDdJQzh5VHpoWWdQdXk5OFVjRlVOcnZBdk0w
V3haN3FwY1ZyVFhYMlZBM1RlYTlvCmNDNDlxMmFPcmZ3SEUxT0EyNFpaSjNPazhoeExmSG0wd1VN
cWhWL2RVSjBTNGNXVVpMYmgvZXpiQW9HQkFOZ3gKSEpKYVpQWkpaRnQrb25EZkNzdWg3d2x3aXBp
VC9jM053Snl2NGRoS0ZZcW5SaDVSZkZ2U3B4NEt3MU5BVHVucApJVlRMblpSdHcybUxRRUhyQVNP
eVpGcHJQRmYxYi9vZ05LQ2dRWldRUXFLUmFVZVplaU5jSUJGQ0dLK2hheFlZCmxuNEVLRHRNNm44
Y2RwN2l3bytzQ05IVjMzSFJ5bjlnTm0vcGFtcEhBb0dBWkhMS3lJSTRIcEl6dFZGcGR0V3oKOTE5
M3NTcGpMSjNzR1VBenYxWEpVQzkzYndxREk5N3N3SjREb0p3dGN6YXlsa1NhNHJQR2ZRUlp5UEpu
K0lnMApwS0UvNlNReEtZV013TDRYLzFuN1lqRlBZeUdYQWpGWDlOclFXY3hOTEtLY09JQzk1R0d4
NVJGRk4xMTkzMmdECnB5dFUwaVdIVkVuYUVLZ1YrdU4xeTRFQ2dZQU84bDVLVkF1VTU0QVR2MDZW
eFNYbTdEd3RoK1ZkSlNZdisyQ3MKdEpCRnR1R0VZNG82Z0dHN3EzVzRZd0FjR2w4YVZ1N2lBTzNW
SEQyZFoyNDY0SGVFczBteTRxVWFZN0twTlY3TwpHQ1pRbzllbmk2d2VzaUs2blJ6dWRJWm1aaCtV
T0lEM0YyeDhwUlcxVWc5MWJySUs0dGI5UXU4ZTNHVkdweTA4ClVZUDA4d0tCZ1FDbDZkRnNJRS8x
VG5jZHdZbWhxbXptOHVOQm8wWElRd05KZ1BQWGZuRFVrRWhsUCtvVEJrUGoKcmVEMEZIdkc2WW1j
SVJPY1FnQm9mZFZUM3NTY2p2cHpzcVlBbnd2RUlMNVA5WVplZHllMGpiYTVtWW1EQndNUgo5WktC
WVE4VVJjMFNKczJwd0N0VXhMOGNYR1duVy9yZVRlNE8rU3ExV0NjbCt2MmQxaGowRHc9PQotLS0t
LUVORCBSU0EgUFJJVkFURSBLRVktLS0tLQo=
