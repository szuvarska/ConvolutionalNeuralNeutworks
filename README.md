# ConvolutionalNeuralNetworks

This is the repository for the first project in the Deep Learning course in Data Science Masters at the Faculty of Mathematics and Information Science. Here we learn convolutional neural networks (CNN) and on top of it we try to develop intuitions. We were informed that this work's goal is purely educational and research-focused, so we aim not to create the best recognition model but to learn as much as possible.

## Typy testów (this needs to be moved from readme (or it needs to be rewritten))

1. Różne architektury:

* w całości skopiowana od kogoś z internetu
* skopiowana od kogoś ze zmienionymi kernelami
* w całości nasza (różne wersje z regularyzacją, liczbą warstw, liczbą neuronów itd.)

2. Testy z różnymi technikami augmentacji dla różnego procenta przerobionych danych
3. Testy z ograniczonym zbiorem danych do 30-100 obserwacji na kategorię (few-shot learning) to bedzie ciezkie
4. Ensemble - prawdopodobnie stacking

## Current tasks

* Create environment - both till 4.03
* Train simple model (mainly if its working and how long does the training takes) - both till 4.03
* Research few-shot learning - Marta till 9.03
* Research augmentation techniques - Mateusz till 9.03

## Next steps

* how do the distributions on given outputs look like (correct classification, bad classification, bad classification - one class)? Is the model sure or unsure? Can we return the label "unsure", pass noise to the model and see how honfident it is in prediction (in theory it should be very confident on noise)
* visualize output from the best enhanced model
* create a marimo notebook where you show the augmentation techniques
* how does sota model performs, how does our model performs on correct and incorrectly classified samples from sota model, check incorrectly classified samples maybe they are miss labeled
