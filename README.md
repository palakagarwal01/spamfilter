
# spamfilter: Live AI/ML Text Spam Classifier

A machine learning pipeline built from scratch using Python and Scikit-Learn to detect whether an incoming text message or email is **Spam** or **Ham (Legitimate)**. The system includes an active infrastructure validation pipeline that pulls live data securely via POP3 protocol.

## 🛠️ Architecture & Core Components
* **Dataset Handling:** Trained on the classic SMS Spam Collection Kaggle distribution (5,572 records).
* **Text Processing (NLP):** Implements **TF-IDF Vectorization** to dynamically weigh predictive keyword signatures while stripping common English stop words.
* **Classifier Model:** Engineered with a **Multinomial Naive Bayes Algorithm** optimizing textual frequency distribution counts.
* **Production Data Fetch:** Real-world verification engine connecting securely over SSL (Port 995) utilizing the Python `poplib` network client.

## 📊 Performance Metrics
* **Total Accuracy:** ~96.68% successful target classification on hidden verification splits.

## 🚀 Interactive Deployment
Click the **"Open in Colab"** badge inside the `.ipynb` file directory to execute the text extraction arrays inside your browser runtime.
