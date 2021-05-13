# Periocular Recognition in the Visible Spectrum

Project Abstract:

With the growing applications of facial recognition systems in various fields, rising challenges
have become prominent. The traditional facial recognition systems and technologies have
become error prone in cases of occlusions, facial expression, and aging which is aimed to be
addressed. The aim of this project is to develop a recognition model that makes use of the
periocular region.
Periocular region refers to the region around the eye inclusive of various features including
sclera, eyelids, lashes, brows, and skin. The model intends to make use of a unique contrast
enhanced region of interest consisting of the region around both the eyes for feature extraction,
using a custom dataset. The dataset comprises of various subjects shot in the visible spectrum. A
convolutional neural network is used to perform the feature extraction that outputs a feature map
for each eye. This intermediate result, when retrieved from gallery images, is fed to classification
model for training. In case of performing the recognition process, this intermediate result is
retrieved from input image selected by the user and fed to the classifier for recognition results

Code Execution:

1. Open the Google Collab file UI.ipynb in the collab environment and run all the cells.
2. Once the last cell starts to execute, click on the second website which contains the
domain as ngrok.
3. The UI will then open, and all functionalities can be utilized as a simple website.
