#### Lung_segmentation
This dataset contains 20 CT scans of patients diagnosed with COVID-19 as well as segmentations of lungs and infections made by experts.
#### This project also consist of Xray images of Covid-19, Viral Pneumonia, lung infection and normal images.
People with pulmonary disease often have a high opacity, which makes segmentation of the lung from chest X-rays more difficult.
In this study, I propose a methodology to improve the performance of the U-NET structure so that it is able to extract the features and spatial characteristics of the X-ray images of the chest region, in addition to the ability to find a link between the left and right parts of the chest region, which helps the neural network to locate the lungs within the X-ray images ( segmentation).
Since the variational autoencoder is used for generation, we can use it to extract the most important information in the x-ray images, such as what we mentioned, the relationship between the left and right parts of the chest region.
Therefore, I proposed integrating the U-NET structure with the variational autoencoder structure in order to reach a neural network structure capable of segmentation for people with lung diseases.
To ensure the accuracy of the study, the neural network was trained on medical chest x-rays of people with lung opacity, and then the model was tested on chest x-rays of people with COVID-19.
The results were as follows: The model was able to train it on chest x-rays of people with lung opacity: accuracy: 0.9829 - precision: 0.9939 - recall: 0.9606. After completing the training, the model was tested on chest X-rays of people infected with COVID-19, and the results obtained were accuracy: 0.9789 - precision: 0.9902 - recall: 0.9650
