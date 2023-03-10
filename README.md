# EvolveGAT
Graph Neural Network model for link prediction in temporal networks.

The architecture is a conjunction of : 
- Graph Convolution network : for graph embedding and reduction in model parameters.
- Graph Attention network : for enhancing quality of embeddings.
- LSTM : for processing the temporal graph at each time step.

## Model Statistics 
- Training error after 40 epochs - 0.36.
- Test AUC score - 0.53.

## Links 
- Presentation - [PPT](https://github.com/its7ARC/TemporalLinkPrediction/blob/main/EvolveGAT_ppt.pdf).
- Source Code - [Code](https://github.com/its7ARC/TemporalLinkPrediction/blob/main/EvolveGAT_Code.ipynb).
