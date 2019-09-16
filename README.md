# convotate-methods

## Methods for Convotate: rapid prokaryotic gene annotation using convolutional neural networks.

Please see the 3 notebooks for complete reproducibility of results in the manuscript and links to data.

1. The "data preparation" notebook shows all the data pre-processing that took place (aside from some very minor filters in bash), such as removal of short sequences and duplicates. It also has a link to a ~4GB tar.bz2 archive which contains ALL the  data used.
2. The "training methods" notebook shows the full pipeline for training the data, and has code for results benchmarking. Options and useful things start around cell number 29. 
3. The "conf matrices" notebook creates the supp info figures

The data and models folders contain all the models and some raw result csvs used in the paper. If desired, you could use the full ~20 million sequences in the bz2 archive with the pre-trained models to investigate accuracy.

If github is not displaying the notebook correctly, you can paste the link and preview without downloading at:
https://nbviewer.jupyter.org
