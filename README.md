# Ninad_portfolio



# [Project 1 : Automated chest x-ray interpretation using Deep Learning:Project review](https://github.com/nins15/Automated-chest-x-ray-interpretation-using-Deep-Learning)
* Created a CNN model for detecting 5 diseases which are Cardiomegaly,Edema,Consolidation,Atelectasis,Pleural Effusion
* Removed the redundant parts from the image like shoulder or text using a library that can detect lungs on chest x-rays
* Mapped the uncertain values in the csv using LSR(Label smoothning regression).
* Trained a number of CNN models on all the images like XceptionNet, EfficientNet, InceptionResNetV2, DenseNet etc. to identify multiple labels for each class.
* Three models with best AUC were chosen for ensembelling by concatinating the last layers of each model.

![](/Ensembleimage.png)
 
 
# [Project 2 :Localising-diseases-on-plant-leaves:Problem Review](https://github.com/nins15/Localising-diseases-on-plant-leaves)
* I have developed a system that can detect plant diseases and localization using GRADCAM.
* Obtained a highly imbalanced dataset which was then balanced using augmentation.
* This balanced datset is then fed to two multiclass CNN models for classification called ResNet and EfficientNet
* Lastly the localizations of the input image is obtained using a GRADCAM.


![](/finalresult.png)


# [Project 3 :Visualizing Weights of CNN Deep learning model on ISIC dataset: Project overview](https://github.com/nins15/Visualizing-Weights-of-CNN-model-on-ISIC-dataset)
* I have visualized the intermediate weights that exist between the layers of a neural network
* An image from the ISIC data set which contains Malignant and benign images fed into the network
* Output is an image representing 'weight concentrations'
![](/weights.png)



# [Project 4 :Vehicle speed and congestion detector](https://github.com/nins15/Vehicle-speed-and-congestion-detector)
---


* Objects like car ,truck and person are detected using Tensorflow object detection api
* Speed is calculated for the last dtected object along with its directio
* If any two objects come too close to each other then "WARNING" is displayed to mark congestion

---




  ![](/Forgif.gif)


