# Travelling Recommendation APP
### Quick Overview:

-  🌍 User-driven input (destination, travel dates)
-  🕷️ Data ingestion via web scraping (Booking.com)
-  🌦️ Retrieve weather data via external weather API  
-  🧹 Data cleaning and structuring using Python and pandas
-  📊 Visualization and recommendation output


### Motivations:

When planning a trip, travelers often need to compare hotel options across different platforms while also considering contextual factors such as weather. This project aims to support travel planning by automatically gathering relevant data and presenting strucutred recommendations.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/cajjster/lunch_box_planner.svg)](https://github.com/cajjster/lunch_box_planner/stargazers)
[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://your-live-demo-link.com)

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Workflow Description](#workflow-description)
3. [Getting Started](#getting-started)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)

---

## About the Project

### Overview:

This project implements a data-driven workflow that collects hotel informaiton from online sources and provides hotel recommendations based on user inputs such as destination and travel dates. The project focuses on real-world ata collection, cleaning, and preparation, using web scraping and external APIs.

### Effects demonstration

#### APP GUI starting:

![image](https://github.com/user-attachments/assets/f7aef480-875b-421a-94a6-0513091a0747)



#### Hotel Recommendations:

![image](https://github.com/user-attachments/assets/fed77ba8-13e5-4c7f-b1a3-b5a6b787ad62)



#### Weather forecasts:

![image](https://github.com/user-attachments/assets/038250a9-47a0-4fff-b647-c88b59c3e9d5)


---

## Workflow Description

### 1. User Input
The workflow begins with user-defined parameters:
- Travel destination
- Check-in and check-out dates
- Number of adults and children
These inputs control wich data sources are queried and how the results are filtered.


### 2. Data Collection
Data is collected from multiple external sources:
- Web scraping is used to extract hotel information (e.g. price, rating, distance from centrum) from online booking platforms.
- External APIs are used to retrieve weather information for the selected destination.
The collected data is raw and heterogeneours, reflecting real-wrold conditions.


### 3. Data Cleaning and Preparation
Using Python and pandas, the raw data is processed to make it usable:
- Selecting relevant attributes from scraped data
- Handling missing or inconsisten values
- Converting data into a structured tabular format
This step ensures that the daga can be reliably used for analysis and recommendation.


### 4. Data Transformation
The cleaned data is transformed into analysis-ready form:
- Structruing hotel features for comparsion
- Preparing derived values used in recommendation logic
- Organizing data for visualization
Transformation logic is implemented in a transparent and interpretable way.


### 5. Recommendation and Output
Based on user inputs and processed data:
- Hotels are filtered and compared using predefined criteria
- Recommendation results are generated
- Visual outputs are produced to support user decision-making
Weather information is included as additional context for travel planning.


## Technology used
- Python
- Pandas, Numpy
- Web scraping libraries
- External APIs
- Data visualzation libraries


## Features

This project demonstrates:
- 👩‍💻 User friendly interface;
- 📊 Working with multiple data sources (web scraping and APIs)
- ⚡ Handling messy data
- 🔐 Clean and structuring data for downstream use
- 🌍 Apply data logic in a user-oriented recommendation scenario
This project is implemented as anotebook-based workdflow and emphasizes clarity and correctness over production deployment.

## Getting Started
Step-by-step instructions to get a local copy running:
1. Open Holiday_Hotel_Weather_2.ipynb to run it;
2. Input the desired city, country, check-in-date, check-out-date, number of adults, children, rooms.
3. You will get the figure results of hotel recommendations and weather forecasts automatically.

### Prerequisites
List tools and dependencies needed:
- Python 3.10+
- Other requirements (e.g., `pip install load_dotenv`)

### Installation
Provide clear installation steps:

```bash
# Clone the repo
git clone https://github.com/TianTao1111/Hotel_recommendation.git

# Navigate to the project directory
cd GitHub/Hotel_recommendation

# Install dependencies
pip install load_dotenv
```



## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

Refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License
Distributed under the MIT License. See `LICENSE` for more information.


