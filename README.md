# SumStar AI - Product Review Analysis

![SumStar AI](website/images/header-bg.jpg)

## Project Overview

SumStar AI is an NLP-powered product review analysis system that aggregates customer feedback from various sources to provide insightful product recommendations. The system uses natural language processing techniques to classify reviews, cluster product categories, and generate comprehensive recommendation articles.
    Dataset used: https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products/data

## Features

- **Review Classification**: Automatically categorizes customer reviews as positive, negative, or neutral
- **Product Categorization**: Clusters products into meaningful categories for easier navigation
- **AI-Generated Summaries**: Creates detailed recommendation articles based on customer feedback
- **Interactive Website**: Presents findings in a user-friendly web interface

## Project Structure

```
SumStarAi/
├── website/               # Original web interface files
├── docs/                  # Deployment folder for GitHub Pages
│   ├── index.html         # Home page
│   ├── styles.css         # Main stylesheet
│   ├── script.js          # JavaScript functionality
│   ├── images/            # Website images
│   └── articles/          # Product category articles
├── Generated Articles/    # Raw article content in markdown
├── Images/                # Project images and assets
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## Technologies Used

- **Data Analysis**: Python, Pandas, NumPy
- **NLP Processing**: NLTK, Transformers, PyTorch
- **Web Development**: HTML, CSS, JavaScript
- **Visualization**: Matplotlib, Seaborn

## Getting Started

### Prerequisites

- Python 3.8+
- Required Python packages (install using `pip install -r requirements.txt`)

## Deployment

The website is deployed using GitHub Pages and can be accessed at: https://kkatt88.github.io/SumStarAi/

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all the open-source libraries that made this project possible
- Special thanks to the contributors and reviewers
