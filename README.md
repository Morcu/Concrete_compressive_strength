# Concrete_compressive_strength

Solving a regresion problem using ANN, predict the Concrete compressive strength. 

The solution can be found in _CCS_Pytorch.ipynb_ and _CCS_TensorKeras.ipynb_ with the implementation of the ANN in pytorch or tensorflow (with keras).

## Model

The Final model is a fully connected Network with an 8 node input layer, 3 hidden layers (30, 20, 10 nodes) with a relu activation and a output layer with 1 node with a sigmoid activation


![ANN](model.png)

## Data  
   
| Atributes                | Values |
|--------------------------|--------|
| Number of instances      | 1030   |
| Number of Attributes     | 9      |
| Features                 | 8      |
| Outputs                  | 1      |
| Missing Attribute Values | None   |



| Variable                      | Unit               |
|-------------------------------|--------------------|
| Cement                        | kg in a m3 mixture |
| Blast Furnace Slag            | kg in a m3 mixture |
| Fly Ash                       | kg in a m3 mixture |
| Water                         | kg in a m3 mixture |
| Superplasticizer              | kg in a m3 mixture |
| Coarse Aggregate              | kg in a m3 mixture |
| Fine Aggregate                | kg in a m3 mixture |
| Age                           | 1 - 365            |
| Concrete compressive strength | MPa                |

The dataset is also availabe from the source: http://archive.ics.uci.edu/ml/datasets/concrete+compressive+strength