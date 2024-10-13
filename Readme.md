# Mobile Recommendation System

## License

![GitHub License](https://img.shields.io/github/license/Yashraj-Sonawane/Mobile-Recommendation-Application)

This project is licensed under the GPL 3.0 - see the [LICENSE](LICENSE) file for details.


## Overview

The **Mobile Recommendation System** is an application designed to help users find the perfect mobile device based on their preferences such as budget, brand, and desired features like battery capacity, camera quality, and more. The system utilizes a recommendation algorithm to suggest mobile phones, making it easier for users to navigate through the vast number of available options.

## Features

- **User Preferences Input**: Allows users to input their preferences for mobile devices, such as budget, preferred brands, and important features.
- **Recommendation Engine**: Provides personalized mobile recommendations using the user's input and a pre-scraped dataset.
- **Web Scraping**: Scrapes mobile device data from online sources to provide real-time pricing and specifications.
- **Interactive User Interface**: Easy-to-use interface for selecting preferences and viewing recommendations.
- **Up-to-Date Information**: Mobile data is periodically refreshed using web scraping to ensure the recommendations are based on the latest models and prices.

## Tech Stack

- **Frontend**: 
  - Streamlit (Python-based web application framework for the user interface)
- **Backend**: 
  - Python for handling data processing and recommendations
- **Web Scraping**: 
  - BeautifulSoup and Requests for static web scraping
  - Selenium for dynamic web scraping (if needed)
- **Data Analysis**: 
  - Pandas and NumPy for manipulating mobile device data
- **Machine Learning** (Optional):
  - Scikit-learn for implementing recommendation algorithms (content-based or collaborative filtering)

## Installation

### Prerequisites

Ensure you have the following installed:
- Python 3.7 or higher
- Pip (Python package manager)

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/mobile-recommendation-system.git
   cd mobile-recommendation-system
