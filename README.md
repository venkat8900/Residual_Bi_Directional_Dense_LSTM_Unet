# Residual_Bi_Directional_Dense_LSTM_Unet

Novel Image Segmentation model which uses Residual blocks, Bi_directional LSTM network (to concatenate encoding and decosing paths at every layer) and Dense connected layers in the final layer. 

Encoder-Decoder network base architecture style: U-net
 

# link for dataset

Retinal Vessel Segmentation: https://drive.google.com/file/d/17wVfELqgwbp4Q02GD247jJyjq6lwB0l6/view

Lung Segmentation: https://www.kaggle.com/kmader/finding-lungs-in-ct-data/data

Skin Lesion Segmentation: https://challenge.kitware.com/#phase/5abcb19a56357d0139260e53 

# Codes
model1.py: modifed version of BCDUNet. Added Residual blocks, modifed pooling layers, modified activation in Bidirectional LSTM 


# To-Do

1) Upload documented code for image preprocessing, dataset preparation and running the code for Retinal Vessel Segmentation, Lung Segmentation, Skin lesion segmentation.

Will updates the codes soon after proper documentation





Base code taken from: https://github.com/rezazad68/BCDU-Net
