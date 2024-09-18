# SMS-Spam-Classification
![IMG_4702](https://github.com/user-attachments/assets/7637f875-8cce-4d0d-8f41-173172b80e18)

This project focuses on classifying SMS messages as either spam or ham (non-spam) using machine learning techniques. The notebook walks through data preprocessing, feature extraction, model training, and evaluation.


---
### Project Structure
- __Data Loading and Exploration:__ The SMS dataset is loaded and basic exploratory analysis is conducted.
- __Data Visualization:__ Visual representations of the dataset help in understanding the distribution of spam and ham messages.
- __Data Preprocessing:__ The data is cleaned and transformed, and new features are created to improve model performance.
- __Model Training:__ Machine learning models like Multinomial Naive Bayes and Decision Tree are trained to classify SMS messages.
- __Model Evaluation:__ The models are evaluated using various metrics, and their performance is compared.
- __Predictions:__ The trained models are used to predict whether new SMS messages are spam or ham.

### Steps to perform SMS Spam Classification:
- __Data Loading:__ Load the SMS dataset and explore its structure.
- __Data Visualization:__ Generate count plots and histograms to understand the dataset.
- __Data Preprocessing:__ Clean the SMS text, handle class imbalance, and create new features like word count, presence of currency symbols, and numbers.
- __Feature Extraction:__ Convert the SMS text into numerical features using TfidfVectorizer.
- __Model Training:__ Train the models (e.g., Multinomial Naive Bayes, Decision Tree) using the training data.
- __Model Evaluation:__ Evaluate the models on test data using accuracy, confusion matrix, and classification report.
- __Make Predictions:__ Use the trained model to classify new SMS messages as spam or ham.

### Results
- The models can classify SMS messages as spam or ham with a good level of accuracy.
- The visualization techniques provide insights into the distribution of words and features that help in distinguishing spam from ham.

### Limitations
- The performance of the models depends on the quality and variety of the data.
- Handling highly imbalanced datasets can be challenging and may require more sophisticated techniques.

### Conclusion
This project provides a practical approach to SMS spam classification, demonstrating the effectiveness of machine learning in text classification tasks. The models and methods used here lay a solid foundation for further improvements and applications in real-world scenarios.

### License
This project is licensed under the MIT License.
