**Developing Multi-Input Models For OCR**
**Project Description**
Optical Character Recognition (OCR) unlocks numerous possibilities in data management.

By leveraging multi-modal modeling, paired with robust training and optimization, you'll deploy deep learning techniques to classify insurance codes from scanned insurance documents and develop an advanced OCR model.

Develop an Optical Character Recognition (OCR) model to sort categories of ID codes extracted from scanned insurance documents.

Create a model named OCRModel in PyTorch. It should have the following specifications:

A network architecture with different layers to ingest both the image and the type. The layers relative to the image should be saved as a sequential module called image_layer, and compatible the input dimensions of the images (64x64 pixels size).
A Conv2d layer with kernel size 3x3, padding 1, and appropriate in/out channels.

Train the Model: call the model as model and use an appropriate optimizer and loss function to train it. Iterate through your training for ten epochs.