# Terragon.de Image Classifier (TIC-Torch)
with a PyTorch Convolutional Neural Network

# Why TIC-Torch?
The TIC-Torch workflow offers a convenient, fast and effective workflow to create, train and deploy individual and versatile image classifiers.

# What's the workflow?
1. Collect many jpg files of the objects you want to classify and arrange them in the "raw" directory. 

2. Create one subfolder for each object you want to classify and put the images inside. 

3. Run TIC-Torch to resize and create variations of the images to train the Neural Network.

4. Run TIC-Torch to classify a new jpg.

# Installation
Just download this repository as a ZIP file and extract.

Then run "jupyter lab" from terminal, open the "Terragon-TIC-Torch.ipynb" file, and "run all cells" to test with all defaults.

To train with your own data, just delete all subfolders in the "raw" folder and replace them with your own images organised in subfolders named like the classes you want to classify. Then run all cells again (delete old "train" folder and "model.pt" files!)
