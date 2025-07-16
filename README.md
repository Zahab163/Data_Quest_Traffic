# Data_Quest_Traffic
Data Quest's Webinar's Data Visualization Project using Python, Pandas, Matplotlib , and Seaborn
# 🚦 Metro Interstate Traffic Volume Analysis

This project explores hourly traffic volume data from Interstate 94 in Minneapolis, Minnesota. It uses Python, Pandas, Matplotlib, and Seaborn to analyze traffic patterns and visualize trends based on time and weather conditions.

## 📁 Dataset
- **Source**: [Metro_Interstate_Traffic_Volume.csv](https://raw.githubusercontent.com/Gmann13/Traffic-Projection/main/Metro_Interstate_Traffic_Volume.csv)
- **Features**:
  - `date_time`: Timestamp of observation
  - `traffic_volume`: Number of cars
  - `temp`, `rain_1h`, `snow_1h`, `clouds_all`: Weather metrics
  - `weather_main`, `weather_description`: Weather conditions
  - `holiday`: Holiday indicator

## 📊 Project Goals
- Visualize traffic volume distribution
- Compare day vs night traffic patterns
- Analyze impact of weather and holidays on traffic
- Prepare data for future predictive modeling

## 🧪 Technologies Used
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 📈 Key Visualizations
- Histogram of traffic volume
- Day vs night traffic comparison
- Hourly traffic trends
- Weather impact on traffic

## 🚀 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/1Ohh7Km3Jil3-_sxB6ethLXCS6ODKFHid?usp=sharing)
2. Run all cells sequentially
3. Make sure you're connected to the internet to load the dataset from GitHub

## 📌 Notes
- The dataset is loaded directly from GitHub using `pd.read_csv()`
- Make sure to use the **raw** CSV link to avoid parser errors

## 🙌 Credits
- Dataset from UCI Machine Learning Repository
- Notebook inspired by Dataquest’s Traffic Volume Project Lab

