# Koç Bootcamp Final Project
This is the final project of Koç Deep Learning Bootcamp. In this project, we need to build a CNN model that classifies UrbanSounds8K data.

## How to run the notebooks?
- PREPROCESSING NOTEBOOK: You need access to the given spectrograms (link in the project documentation file) in your own Google Drive. If you have access, you can just run all the cells. If you do not have access, you can create your spectrograms and modify paths in the notebook.
After preprocessing all the images, you need to put them into a folder named 'spectrograms_processed'. After running all the cells, you'll have a folder called 'spectrogram_data'.
- MODEL NOTEBOOK: First, you must do all the steps in the preprocessing notebook. Second, if you have a folder named 'spectrogram_data', you can just run the cells and get a working CNN model.

### Note: If you want to work on these notebooks on Colab, you need to upload 'spectrogram_data' as a zip file. After uploading the zip file, you need to run !unzip cell in the model notebook.
