# Image_Captioning
In this project, we build a neural network based on the following paper https://arxiv.org/pdf/1411.4555.pdf.
Architecture of net consists of two parts, Encoder and Decoder. Encoder serves as a feature extractor and decoder serves for generating sequences. In this project, the decoder consisted of LSTM layers with dropout.
The net was trained on captions for MS COCO dataset.
For evaluation of neural network performance, we used perplexity. It measures how well the neural network predits the sample. A low perplexity means that NN is good at predicting captions for samples.

