# 🏅 Olympic Analysis and Prediction System  

An interactive web application to analyze and visualize Olympic data using Streamlit, Plotly, and Python. This project provides insights into Olympic performance trends, medal tallies, and athlete statistics through dynamic and visually appealing dashboards.  

## 🚀 Features  
- **Medal Tally Dashboard**: View Olympic medal distributions by country and year.  
- **Overall Analysis**: Explore key statistics on Olympic editions, host cities, sports, athletes, and nations.  
- **Country-wise Analysis**: Analyze medal trends, top-performing athletes, and excelling sports for specific countries.  
- **Athlete-wise Analysis**: Visualize athlete performance by age, sport, and medal type with distribution plots and scatter plots.  
- **Interactive Visuals**: Dynamic line charts, heatmaps, and scatter plots powered by Plotly and Seaborn.  

## 🛠️ How It Works  
1. **Preprocessing**: Filters data for Summer Olympics and merges regional information using `preprocessor.py`.  
2. **Visualization**: Uses Plotly and Seaborn to generate interactive visualizations.  
3. **Dashboard**: Streamlit app with sidebar navigation for seamless exploration of analysis sections.  

## 📂 Project Structure  
📁 olympic-analysis
│
├── 📄 app.py # Main Streamlit application
├── 📄 preprocessor.py # Data preprocessing script
├── 📊 athlete_events.csv # Dataset for Olympic athletes and events
├── 📊 noc_regions.csv # Dataset for NOC regions
└── README.md # Project documentation


## 📊 Visualizations  
- **Medal Tally**  
- **Participation Trends (Nations, Events, Athletes)**  
- **Country Performance**  
- **Athlete Distribution (Age, Height, Weight)**  

📈 Datasets
athlete_events.csv: Contains details of Olympic athletes, events, and results.
noc_regions.csv: Maps National Olympic Committees (NOC) to respective regions.

🏗️ Future Improvements
Add Winter Olympics data analysis.
Implement predictive modeling for medal forecasts.
Enhance UI with additional filtering options and charts.

Author: Rohit Kumar
📧 Contact: rohitbhagasra4@gmail.com
🌐 LinkedIn: (https://www.linkedin.com/in/rohit-kumar-85r95/)
