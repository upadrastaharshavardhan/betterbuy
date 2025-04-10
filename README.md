
 # Price Comparison and Sentiment Analysis Project

This project aims to perform price comparison between e-commerce websites and sentiment analysis on user reviews using web scraping techniques, Python programming language, and Support Vector Machine (SVM) model. The project utilizes the Amazon Reviews dataset from Kaggle for training and evaluating the sentiment analysis model.

<img src="https://i.ibb.co/XDNXz2y/image.png" alt="image" border="0">

## Features

1. **Price Comparison**: The project allows users to compare prices of products across different e-commerce websites. By providing the product name or keyword, the program scrapes the specified websites and retrieves the prices of the products. The scraped data is then presented to the user for easy comparison.

2. **Sentiment Analysis**: The project also includes sentiment analysis of user reviews. The SVM model is trained on the Amazon Reviews dataset to classify the sentiment of user reviews. Each review is automatically assigned a rating based on its sentiment, indicating whether it is positive, negative, or neutral.

## Technologies Used

The project leverages the following technologies:

- **Python**: The project is implemented using the Python programming language, making use of its extensive libraries and frameworks for web scraping and machine learning.

- **Web Scraping**: Web scraping is performed using Python libraries such as BeautifulSoup and Requests. These libraries enable the extraction of relevant data, including product prices, from e-commerce websites.

- **Support Vector Machine (SVM)**: SVM is a machine learning algorithm used for sentiment analysis in this project. The SVM model is trained on the Amazon Reviews dataset, which consists of labeled reviews for training the sentiment analysis model.

- **Amazon Reviews Dataset**: The project utilizes the Amazon Reviews dataset sourced from Kaggle. This dataset contains a large collection of user reviews, along with their associated ratings, making it suitable for training the sentiment analysis model.

## Installation and Setup

To set up and run the project locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/price-comparison-sentiment-analysis.git
```

2. Install the required dependencies using pip:

```
pip install -r requirements.txt
```

3. Run the program:

```
python main.py
```

Web server will be running at http://localhost:5000/

## Usage

1. Price Comparison:

- Launch the program and provide the product name or keyword you wish to search for.
- The program will initiate web scraping on the specified e-commerce websites.
- Once the data is retrieved, it will be displayed for comparison, allowing you to make an informed decision based on prices across different platforms.

2. Sentiment Analysis:

- User reviews can be submitted through the application's interface.
- The sentiment analysis model will automatically assign a rating to each review based on its sentiment, indicating whether it is positive, negative, or neutral.
- These ratings can be used to assess the overall sentiment of user feedback and make data-driven decisions accordingly.

## Contributing

Contributions to the project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make the necessary changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request describing the changes you have made.

## Acknowledgments

We would like to express our gratitude to the following resources and communities for their valuable contributions:

- [Kaggle](https://www.kaggle.com/) for providing the Amazon Reviews dataset, which serves as the foundation for sentiment analysis training.
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) and [Requests](https://requests.readthedocs.io/) libraries for enabling efficient web scraping capabilities.
- The Python community for developing and maintaining various packages and frameworks that make this project possible.

## Contact

For any inquiries or support related to the project, please reach out to us at [upadrastaharsha09@gmail.com](mailto:upadrastaharsha09@gmail.com). We appreciate your feedback and suggestions.
