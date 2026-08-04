# ANNWasteClassification

An image classification system that uses an Artificial Neural Network (ANN) to classify waste into three categories:
- Compost
- Recycle
- General Waste
  
Made in Google Colab, written in Python using TensorFlow/Keras model 

## Preparing Dataset
1. Collect and Collate images of different categories of waste (the more the better)
2. Organise the images using the following folder structure:
  Dataset/
   ├── Compost/
   ├── Recycle/
   └── General/
  
3. Compress the dataset folder into a ZIP file.

## Running Project with Google Colab:
1. Open the `.ipynb` notebook in Google Colab.
2. Select the folder icon on the left-hand side.
3. Select **Upload to session storage**.
4. Upload the zipped dataset.
5. Run the notebook cells from top to bottom.

Please note that files uploaded to Colab session storage are temporary and may need to be uploaded again when starting a new session.

## Testing the Model
After training is complete, run the final cell to upload an image you want the model to classify.

## Note  
The dataset is not included in this repository. Users must provide their own images and organise them using the required folder structure.
