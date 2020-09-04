# {{ cookiecutter.project_name }}

## Overview

This is a tutorial project, which was generated using `Kedro {{ cookiecutter.kedro_version }}`. It is the completed version of the [Space Flights tutorial](https://kedro.readthedocs.io/en/stable/03_tutorial/01_spaceflights_tutorial.html) described in the Kedro [documentation](https://kedro.readthedocs.io) and includes the data necessary to run the project.

The tutorial works through the steps necessary to create this project. To learn the most about Kedro, we recommend that you start with a blank template as the tutorial describes, and follow through all the working. However, if you prefer to read swiftly through the documentation and get to work on the code, you may want to run this example because the steps have been done for you.

Before running this project, make sure you have the required dependencies, run in your virtual environment (see [the documentation](https://kedro.readthedocs.io/en/stable/02_getting_started/01_prerequisites.html#python-virtual-environments) for how to set up your virtual environment):

```bash
pip install kedro=={{ cookiecutter.kedro_version }}
kedro install
```

You can run the project with:

```bash
kedro run
```
