# SMS Spam Detection

## Introduction
Welcome to the SMS Spam Classifier project! This project is designed to help users identify whether a given SMS message is spam or not. With the ever-increasing number of unwanted and potentially harmful messages being sent via SMS, having a reliable classifier can be invaluable in protecting users from scams, phishing attempts, and other malicious activities.

Using state-of-the-art machine learning techniques and natural language processing (NLP) methods, this classifier analyzes the content of SMS messages to determine whether they exhibit characteristics commonly associated with spam. Leveraging the power of Naive Bayes classification algorithms and TF-IDF vectorization, the model can accurately classify messages as either spam or non-spam (ham), providing users with a quick and reliable means of identifying potentially harmful content.

Whether you're a user looking to safeguard your inbox from unwanted messages or a developer interested in exploring machine learning techniques for text classification, the SMS Spam Classifier project offers a powerful and intuitive solution for detecting and filtering out spam messages in real-time.

## Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Technologies Used](#technologies-used)
4. [Project Structure](#project-structure)
5. [Contributing](#contributing)
6. [License](#license)

## Installation
To use the SMS Spam Classifier, follow these steps:
1. Clone the repository to your local machine: `git clone https://github.com/Elangovan0101/SMS-spam-detection.git`
2. Navigate to the project directory: cd sms-spam-classifier`
3. Install the required dependencies:(https://github.com/Elangovan0101/SMS-spam-detection.git)
pip install -r `requirements.txt`
4. Run the Streamlit app: `streamlit run app.py`

## Usage
1. Open the Streamlit app by running `streamlit run app.py` in the terminal.
2. Enter the SMS message you want to classify into the text area provided.
3. Click on the "Predict" button to classify the message as spam or non-spam (ham).

## Technologies Used
- Python
- Streamlit
- Scikit-learn
- NLTK (Natural Language Toolkit)


## Contributing
Contributions to this project are welcome. To contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Create a new pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
