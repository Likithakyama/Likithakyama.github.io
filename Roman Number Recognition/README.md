**Roman Number Recognition**

This project focuses on recognizing handwritten Roman numerals using deep learning techniques. The dataset used for training consists of handwritten characters modified from English characters, providing a diverse range of styles and variations.

**Key Features:**

**Dataset:**

The model is trained on the Chars74K dataset, containing handwritten characters including Roman numerals.

**Preprocessing:** 

Images are preprocessed, resized, and normalized to prepare them for training.

**Model Architecture:**

Utilizes transfer learning with the VGG19 convolutional neural network architecture pretrained on the ImageNet dataset.

**Training:**

The model is trained on the preprocessed dataset with categorical cross-entropy loss and Adam optimizer.

**Evaluation:**

Performance is evaluated using accuracy metrics and a confusion matrix.

**Prediction:** 

Users can upload their own handwritten Roman numeral images for prediction. The model returns the predicted class along with confidence scores for each class.

**Technologies Used:**

Python

TensorFlow

OpenCV

Scikit-learn

Matplotlib

Seaborn
