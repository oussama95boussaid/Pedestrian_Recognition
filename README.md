# PedestrianGuard
The primary goal of this project is to classify images swiftly and accurately, determining whether they contain pedestrians or not

**Key Features:**

**HOG Feature Descriptor:** PedestrianGuard AI utilizes Histogram of Oriented Gradients (HOG) as a powerful feature descriptor. HOG captures the local intensity gradients of an image, allowing for robust detection of pedestrian shapes and structures.

**SVM Classification:** The project employs Support Vector Machines (SVM) as the classification algorithm. SVM excels at distinguishing between pedestrian and non-pedestrian images, creating a reliable model for real-time decision-making.

**How It Works:**

**Image Preprocessing:** PedestrianGuard AI preprocesses images using the HOG feature descriptor, extracting essential information about the gradients and shapes present in the image.

**Classification:** The preprocessed data is then fed into a Support Vector Machine, which has been trained on a diverse dataset to recognize patterns indicative of pedestrians. This robust classification process ensures accurate identification.
