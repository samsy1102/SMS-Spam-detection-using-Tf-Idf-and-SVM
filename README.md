# SMS-Spam-detection-using-Tf-Idf-and-SVM

**📧 Spam Message Detection using SVM & TF-IDF**

This project is a Spam Detection Model that classifies SMS messages as Spam or Ham (not spam) using:

TF-IDF Vectorization for text feature extraction.

Support Vector Machine (SVM) classifier with a linear kernel.

Evaluation metrics like accuracy, classification report, and confusion matrix.



**📂 Project Structure**
├── Main.ipynb        # Main Jupyter Notebook with code
├── spam.csv          # Dataset used for training & testing
├── README.md         # Project documentation



**📊 Dataset**
The project uses the SMS Spam Collection dataset.
It contains:

label → ham (0) or spam (1)

message → SMS text content

The dataset is preprocessed by removing numbers, punctuation, and converting text to lowercase.



**⚙️ Installation**

Make sure you have Python 3.8+ installed. Then install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn



**📈 Model Workflow**

Data Loading & Cleaning

Lowercasing

Removing numbers & punctuation

Feature Extraction

TF-IDF Vectorization with 3000 max features

Model Training

Support Vector Machine (Linear Kernel)

Evaluation

Accuracy score

Classification report

Confusion matrix visualization


**📊 Example Output**
Accuracy: 0.976
Classification Report:
              precision    recall  f1-score   support
           0       0.98      0.99      0.98      965
           1       0.97      0.94      0.95      150



**📌 Requirements**

Python 3.8+

pandas

numpy

scikit-learn

matplotlib

seaborn
