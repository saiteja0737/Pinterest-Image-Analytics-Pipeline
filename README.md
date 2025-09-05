# Pinterest Image Analytics Pipeline
An end-to-end image analytics system that combines web scraping, computer vision, and cloud computing to analyze Pinterest food images and user engagement patterns.

## Project Overview
This project demonstrates a comprehensive data pipeline that scrapes Pinterest food images, applies AWS computer vision analysis, and derives insights about user engagement behaviors. The system integrates multiple data sources and cloud services to perform both technical image analysis and statistical correlation studies.

## Key Features

- **Web Scraping**: Collected 73 Pinterest food images using dual approaches:
  - Python Selenium automation  
  - Apify platform (no-code scraping)  
- **Engagement Metrics**: Extracted user interactions (shares, comments, repins).  
- **Image Analysis**: Applied AWS Rekognition in SageMaker for:
  - Object detection  
  - Confidence scoring of detected labels  
  - Image quality assessment including brightness and sharpness  
- **Cloud Integration**: Stored processed results in Firebase cloud database.  
- **Statistical Insights**: Conducted engagement analysis, identifying a **95% correlation between shares and repins** through statistical analysis and data visualization.  

## Technical Stack
* Programming: Python (Pandas, Selenium, BeautifulSoup, Requests)
* Cloud Services: AWS SageMaker, AWS Rekognition, Firebase
* Data Analysis: Statistical analysis, Matplotlib, Seaborn
* Web Scraping: Selenium WebDriver, Apify platform
* Database: Firebase NoSQL cloud database

## Project Results

* Automated scraping pipeline with dual methodology.
* Generated structured CSV datasets with image properties and confidence scores.
* Identified strong user behavior patterns (shares ↔ repins correlation: 95%).
* Multi-dataset integration with cloud storage
