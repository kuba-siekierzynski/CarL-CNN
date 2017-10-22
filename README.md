# CarL-CNN
Car Logos CNN - building my own car logos classifying neural network

# Description
CarL-CNN was trained with 20,778 50x50px RGB images depicting logotypes of 40 different car brands. The dataset was handpicked from loosely scraped websites and contain images, photos, drawings, sketches at various color schemes (black/white, RGB, CMYK, one-color), different angles and can sometimes contain some noise (other logotypes, background, etc.)

# Links - needed for the full run of CarL-CNN
(unzip to folder, where CarLogosCNN.ipynb resides)

Model weights (1 file, 140 MB) - http://u.42.pl/GEt0_model_weights
Images (20778 files, 54 MB - ZIP) for the train and test set - http://u.42.pl/GEt7_images
New images (12 files, 677 kB) unseen during the training - http://u.42.pl/GEtf_new_images

# Requirements
numpy
matplotlib
scikit-learn
keras (tensorflow backend)
pillow - for image processing
