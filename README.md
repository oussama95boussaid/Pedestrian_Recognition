# **PedestrianGuard AI**

PedestrianGuard AI is a cutting-edge project designed to enhance urban safety by leveraging advanced image classification techniques. The primary goal of this project is to classify images swiftly and accurately, determining whether they contain pedestrians or not.

# **Key Features:**

**HOG Feature Descriptor:** PedestrianGuard AI utilizes Histogram of Oriented Gradients (HOG) as a powerful feature descriptor. HOG captures the local intensity gradients of an image, allowing for robust detection of pedestrian shapes and structures.

**SVM Classification:** The project employs Support Vector Machines (SVM) as the classification algorithm. SVM excels at distinguishing between pedestrian and non-pedestrian images, creating a reliable model for real-time decision-making.

# **How It Works:**

**Image Preprocessing:** PedestrianGuard AI preprocesses images using the HOG feature descriptor, extracting essential information about the gradients and shapes present in the image.

**Classification:** The preprocessed data is then fed into a Support Vector Machine, which has been trained on a diverse dataset to recognize patterns indicative of pedestrians. This robust classification process ensures accurate identification.

# **Data Set Summary & Exploration**

**1.Dataset presentation**

  - Total Number of Images =  20000
  - Number of Ped Images =  24000
  - INumber of Non Ped Images = 25000
  - Image data shape =  (36, 18)

To download the dataset use this commands

        !wget -p dataset/  http://www.lookingatpeople.com/data/Daimler/pami06-munder-gavrila/DC-ped-dataset_base.tar.gz
        !tar -xvf  /content/www.lookingatpeople.com/data/Daimler/pami06-munder-gavrila/DC-ped-dataset_base.tar.gz

**2.Visualization of the dataset.**

Here is an exploratory visualization of the data set. It is a bar chart showing how the data is ditributed across the different labels.

<img src="training_set_counts.png"  title="AlexNet Architecture">

Here is an visualization of some 5 randomly picked training examples for each class. As we can see, within each class there is a high variability in appearance due to different weather conditions, time of the day and image angle.
