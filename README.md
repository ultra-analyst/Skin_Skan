## Project: Skin Skan - Skin Lesion Classification

### Overview
As part of my capstone project at the University of Miami, in collaboration with Deloitte consultants through the DIRPA Initiative, I developed an application named **Skin Skan**. This project was a key component of my Master’s in Business Analytics at the Miami Herbert Business School. The project was completed with the valuable contributions of my teammates: Natalie Aguilar, Dylan Mason, and Andrea Bianchi.

### Objective
The objective was to create a Convolutional Neural Network (CNN) model to classify skin lesion images into various categories, aiming to assist in early detection and diagnosis of skin cancer.

### Methodology
1. **Data Collection**: Utilized the HAM10000 dataset, consisting of over 10,000 dermatoscopic images of skin lesions.
2. **Data Preprocessing**: Implemented image resizing, normalization, and data augmentation to enhance model performance.
3. **Model Development**: Built a deep CNN with multiple convolutional layers, batch normalization, dropout layers, and max pooling.
4. **Training**: Trained the model using ImageDataGenerator with early stopping and learning rate reduction callbacks to prevent overfitting.
5. **Evaluation**: Achieved an accuracy of 78.96% on the validation set, demonstrating the model’s ability to classify skin lesions accurately.

### Model Architecture
The improved model architecture included:
- Convolutional layers with ReLU activation and batch normalization.
- MaxPooling layers to reduce spatial dimensions.
- Dropout layers to prevent overfitting.
- Dense layers with a final softmax activation for multi-class classification.

### Application
**Skin Skan** was developed as a Flask web application, allowing users to upload an image of a skin lesion. The app preprocesses the image and uses the trained model to predict the type of lesion, providing results in a user-friendly interface.

### Impact
This project showcases the integration of advanced machine learning techniques with practical applications in healthcare. It highlights the potential of AI in improving diagnostic accuracy and accessibility, contributing to early detection and treatment of skin cancer.

### Conclusion
Completing this project as part of my capstone experience was immensely rewarding. The collaboration with Deloitte and the support from the University of Miami’s DIRPA Initiative provided invaluable insights and real-world experience in deploying machine learning solutions. **Skin Skan** stands as a testament to the transformative power of data analytics and machine learning in healthcare.
