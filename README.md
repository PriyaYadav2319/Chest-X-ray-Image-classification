 Chest Xray Classification

Unlocking insights from pixels, our AI breathes life into every Xray frame, shaping a healthier tomorrow with each classification.

 Why Image Classification?

Our innovative approach, utilizing Histogram of Oriented Gradients (HOG) feature extraction and custom Convolutional Neural Network (CNN) models, accurately discerns pneumonia presence from chest Xray images, offering early detection potential. Beyond binary classification, this method could aid in subtype differentiation and optimize resource allocation, while contributing valuable insights for monitoring disease trends.

 Libraries Used

 TensorFlow: For building and training deep learning models.
 Keras: Highlevel neural networks API (backed by TensorFlow) for easy model development.
 Scikitlearn: For model evaluation and metrics calculation.
 Matplotlib: For data visualization.
 Glob2: For file handling and directory operations.

 Pipeline

 1. Data Collection
Chest Xray images were sourced from diverse repositories, including public medical databases and hospital archives, ensuring a comprehensive dataset representing various demographics and clinical conditions.

 2. Preprocessing
Data preprocessing involved:
 Artifact removal and irrelevant information elimination.
 Augmentation (rotation, flipping).
 Pixel value scaling for consistent normalization across images.

 3. Model Training
During training:
 Convolutional Neural Networks (CNNs) were selected for image classification tasks.
 Optimization using algorithms like Adam or RMSprop for improved parameter adjustment.

 4. Deployment
Potential deployment strategies involve:
 Creating a userfriendly interface for image uploads.
 Integrating the model into PACS.
 Deploying it as a cloudbased diagnostic tool, with regular updates to maintain accuracy and relevance in clinical practice.

 5. Evaluation
Model performance was rigorously assessed via crossvalidation to prevent overfitting, ensuring generalizability, with metrics like accuracy, precision, recall, and F1score for precise classification evaluation.

 6. Data Exploration
Our dataset comprises chest Xray images categorized into normal and pneumonia classes. We conducted exploratory data analysis, including:
 Displaying sample images from the dataset.
 Visualizing the distribution of pixel intensities through histograms.
 Analyzing class distribution using a pie chart.
 Examining image dimensions through box plots and violin plots.

 7. Data Preprocessing
Prior to model training, we preprocessed the data by:
 Resizing images to a uniform size (224x224 pixels).
 Performing data augmentation techniques such as rotation, shearing, and flipping (if applicable).
 Normalizing pixel values to a range between 0 and 1.

 8. Model Training
We compiled the model with categorical crossentropy loss and the Adam optimizer. The data was fed into data generators for efficient processing. We trained the model using the `fit()` function, monitoring training and validation loss/accuracy over epochs.

 9. Model Evaluation
For model evaluation, we calculated various metrics including accuracy, precision, recall, and F1score. Additionally, we generated a confusion matrix to visualize the model's performance in classifying normal and pneumonia cases.

 Conclusion
In conclusion, our analysis showcased the effectiveness of deep learning for chest Xray image classification. Despite encountering challenges, our model demonstrated promising results. Future enhancements may involve exploring advanced architectures, optimizing hyperparameters, and incorporating additional data sources for improved performance.






