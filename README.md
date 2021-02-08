# ChequeDetection
Detect different parts of a Bank Cheque
## Dataset source
The dataset was downloaded from: [IDRBT Cheque Image Dataset](https://www.idrbt.ac.in//icid.html).

You can also find the dataset here: [Kaggle Dataset](https://www.kaggle.com/pranav10000/chequedetection)

P. Dansena, S. Bag, and R. Pal, “Differentiating Pen Inks in Hand-written Bank Cheques Using Multi-Layer Perceptron”, Proc. of 7th International Conference on Pattern recognition and Machine Intelligence, Kolkata, India, December 2017.
## Annotations
The annotations were done using the [SuperAnnotate Tool](https://superannotate.com/).

The tool exports a separate `.json` file for every image containing the bounding box and class information. It does not export the size of image though.
## Training

The model was trained on Kaggle GPU(P100). You can check the kaggle notebook/kernel [here](https://www.kaggle.com/pranav10000/cheque-detection): 

## Prediction
The [Inference Notebook](https://github.com/pranavmp-10-000/ChequeDetection/blob/main/ChequeDetection_Inference.ipynb) can be used to run the prediction on the model trained.

The Google Colab link: [Colab Notebook](https://colab.research.google.com/drive/16REjj0e_ncVeWPPzlDU8GJPDicWq9o2R?usp=sharing)

## SSD MobileNet V1 
![Prediction_SSD_MN_V1](https://github.com/pranavmp-10-000/ChequeDetection/blob/main/prediction.png?raw=true)
