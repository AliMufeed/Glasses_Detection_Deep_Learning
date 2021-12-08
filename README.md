
# Image Classification: Glasses Detection

### Backstory & scope

Glasses which are known as eyeglasses or spectacles ,are typically used for vision correction, such as with reading.
Also, there are other types of glasses such as safety glasses, sunglasses, and specialized glasses like 3D glasses.

The goal of this project is to build a neural network model that uses image data to predict whether someone is wearing a glasses or not using
classification models to find the best model, after clustering the images. This project can be used in places where wearing safety glasses is a 
must such as factories and laboratory to detect people who are not wearing glasses.

### Data

![image](https://user-images.githubusercontent.com/90555117/145207468-ce4e4b06-cb6f-4346-9647-e5eca0374698.png)

The data for this project is from Kaggle.com (Find the dataset on the following [link](https://www.kaggle.com/jeffheaton/glasses-or-no-glasses).
The obtained dataset consists 5000 images of
people wearing different shapes of glasses and people who does not wear glasses. at the first the data should be clustered into two parts (glasses and No-glasses)
then the best deep learning classification model will choosing based on the accuracy and the overfitting. However, 
this data set has two categories (Glasses 1 or No Glasses 0 ).

Before applying augmentation to the images the Glasses class was 56% and the No Glasses class was 43%, but after augmentation the number of images has been increased from 5000 to 9399 images,
51% Glasses and 49% No Glasses.

### Tools
- Pandas library will be used to create data frames.
- Sklearn library will be to implement the baseline classification models.
- Matplotlib, Seaborn and visualkeras to visualize and discuss the results of the analysis.
- keras and tensorflow for deep learing models and image preprocessing.

#
[Project Proposal](Proposal_Glasses_Detection.md)

[Project MVP](MVP_Glasses_Detection.md)

[Project Presentation](https://github.com/AliMufeed/Glasses_Detection_Deep_Learning/blob/e19f000f4a3d998a9d6e1608d6225a299f29b019/Glasses%20Detection%20Image%20Classification%20Presentation.pdf)

[Project Code](Glasses_Detection_Image_Classification.ipynb)
