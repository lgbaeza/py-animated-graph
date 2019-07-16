## Python animated graph

Create an animated graph from a dataset. For example, we will be using the [Capital Bike Sharing Data set](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset)

This repo references the PyPi Package available on ![Pypi AnimatedGraphs](https://pypi.org/project/AnimatedGraphs/). If you wish to contribute, feel free to reach out.

![animated graph](https://github.com/lgbaeza/py-animated-graph/blob/master/bike_sample.gif?raw=true)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install AnimatedGraphs.

```bash
pip install AnimatedGraphs
```

## Usage

```python
import AnimatedGraphs as ag
from AnimatedGraphs import AnimatedBar as agBar

GRAPH_FILENAME = agBar.CreateGraphBar(
    dataset,
    args**
)
if (GRAPH_FILENAME != ""):
    print("Succeed. Animated grahBar available at {}" + GRAPH_FILENAME)
else:
    print("something went wrong")
```

## Sample notebbok

The ![sample notebook notebook](https://github.com/lgbaeza/py-animated-graph/blob/master/Animated%20Graph%20Sample%20Usage.ipynb) was created on Azure Machine Leaarning Studio.Create a free account in [https://studio.azureml.net](https://studio.azureml.net)

* Create an account in Azure ML
* Create a dataset using your CSV file
* Import the notebook
* Configure the properties of your data set in the CreateGraphBar() function
* Run the notebook
* Right click on the generated image and then save as GIF

Author: Luis Gerardo Baeza
lgbaeza@gmail.com