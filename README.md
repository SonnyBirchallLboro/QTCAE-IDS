# QTCAE-IDS
A quantised temporal convolutional autoencoder deployed on the PYNQ-Z2 FPGA using the FINN framework. 


The model architecture, training, and validation can be found in the QuantisedAutoEncoder.ipynb Python Jupyter Notebook
This part of the project was done using the Google Drive and Google Colab, and as such any filesystem based code 
using paths etc is likely to need changing.

The dataset used is the CarHacking dataset [1].
Note that I have preprocessed this dataset into my own proprietary format using the numpy library however cannot 
upload this to github as it is much larger than 25MB.


The FINN code is also uploaded which only operates in a FINN docker container on a specific version of Ubuntu
on a machine that has a X86 architecure processor.


TODO: Upload the PYNQ-Z2 PS code. 







[1] H. M. Song and H. K. Kim, “CAN network intrusion datasets,” [Online]. Available: https://ocslab.hksecurity.net/Datasets/car-hacking-dataset. [Accessed 21 03 2025].
