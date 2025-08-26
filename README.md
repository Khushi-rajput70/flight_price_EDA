Flight Price Analysis - Exploratory Data Analysis (EDA)

📌 Overview

This project performs Exploratory Data Analysis (EDA) on a flight price dataset to understand the key factors that influence airline ticket prices.
The dataset includes details such as airline, source, destination, total stops, duration, and ticket price.
The goal of this project is to clean, visualize, and analyze the dataset to uncover patterns and trends in flight pricing.

⚙ Features

Data preprocessing and cleaning (handling missing values, formatting features)

Univariate and multivariate analysis

Visualizations of price distribution across different airlines, routes, and travel durations

Insights on how features like airline, stops, journey time, and class affect ticket prices

Preparation of the dataset for future machine learning models


📂 Dataset

The dataset contains the following columns:

Airline – Name of the airline

Date of Journey – Flight date

Source – Starting location

Destination – Arrival location

Route – Flight path

Total Stops – Number of stops (non-stop, 1 stop, 2 stops, etc.)

Duration – Total travel time

Price – Ticket price (Target variable for future prediction)


(You can add the dataset source here, e.g., Kaggle or given dataset.)

🛠 Technologies Used

Python 🐍

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Data visualization

Jupyter Notebook – Analysis


🚀 How to Run

1. Clone the repository:

git clone https://github.com/Khushi-rajput70/flight_price_EDA.git


2. Navigate to the project folder:

cd flight_price_EDA


3. Install dependencies:

pip install -r requirements.txt


4. Open Jupyter Notebook and run the analysis:

jupyter notebook



📊 Insights

Ticket prices vary significantly across different airlines.

Non-stop flights tend to be more expensive than connecting flights.

Travel duration and number of stops are strong indicators of flight pricing.

Prices fluctuate depending on the source-destination route.


📜 License

This project is licensed under the MIT License – see the LICENSE file for details.
