# convotate-methods

## Methods for Convotate: rapid prokaryotic gene annotation using convolutional neural networks.

Please see the 3 notebooks for reproducibility of results in the manuscript and links to data.

1. The "data preparation" notebook shows all the data pre-processing that took place (aside from some very minor filters in bash), such as removal of short sequences and duplicates. It also has a link to a ~4GB tar.bz2 archive which contains all the  data used.
2. The "training methods" notebook shows the full pipeline for training the data, and has code for results benchmarking. Options and useful things start around cell number 29. For simple use change "chosen level" to see results for different hierarchical levels of the ontology. If you want more advanced options you can (a) switch from pretrained models to training models yourself or (b) change the data files to use the full database dump. 
3. The "conf matrices" notebook creates the supp info figures

The data and models folders contain all the models and some raw result csvs used in the paper. If you want to use the ~20 million sequences in the bz2 archive with pre-trained models to investigate accuracy, download via the link in the data prep notebook.

If github is not displaying the notebook correctly, you can paste the link and preview without downloading at:
https://nbviewer.jupyter.org
