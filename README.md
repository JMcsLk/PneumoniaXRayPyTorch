# Pneumonia X-Ray PyTorch Classification Model

<img src="https://hhp-blog.s3.amazonaws.com/2016/10/iStock_44501454_MEDIUM.jpg" width="300" height="300">


<i>This repository contains PyTorch classification model based on Pneumonia X-Ray image dataset.</i>

<i>This model was based on CNN publication by PhD Krzysztof Sopyla: PyTorch CNN Tutorial CIFAR-10.</i>

<i>Dataset is avalible here:</i> https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

<b><i>Model description:</i></b> 

<b><i>1. Data download process, unziping and clearing useless data.</i></b>

<b><i>2. Libraries import, definition of required classes and methods.</i></b>

<b><i>3. Samples import, files compability verification and new samples generation process based on imgaug library:</i></b>

In this section preprocessing of the images were performed. Basic dataset contains almost 6000 pictures. 
Number of images was multiplied to ~25000 by sequential operations based on imgaug library.

Training pictures visualisation:

<img src="https://i.ibb.co/3srRgRD/pobrane.png" width="600" height="600">

<b><i>4. Parameters definition, images to tensors transformation, and model definition:</i></b>

Images size were set on 224x224 with 1 channel, batch_size was equal 16, two output classes called: 'NORMAL' and 'PNEUMONIA'.
Model was trained on 20 epochs.

<b><i>5. Model Summary and training process: </i></b>

<img src="https://i.ibb.co/RhZHYMD/model.png" width="350" height="500">

<b><i>6. Training results visualisation: </i></b>

<img src="https://i.ibb.co/6Rd9d7v/pobrane-1.png">
