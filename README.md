# Uber Trip Analysis  
Analyzing Uber trip data to identify patterns, predict trip demand, and uncover insights into ride-hailing trends in New York City.  

## 📂 Dataset  
This dataset contains Uber trip data from **April 2014 to June 2015**, obtained from the NYC Taxi & Limousine Commission (TLC) through a Freedom of Information Law request. It includes:  
- **4.5 million Uber pickups (April - September 2014)**  
- **14.3 million Uber pickups (January - June 2015)**  
- **Non-Uber For-Hire Vehicle (FHV) trips** from multiple companies  
- **Aggregate ride and vehicle statistics**  

📥 **[Download Dataset](https://drive.google.com/file/d/1oRoQupHhyNlmQU5YGP9HLXTRnV2-LHRa/view?usp=sharing)**

### **Dataset Features**  
#### 🚖 Uber Trip Data (2014)  
- **Date/Time**: Timestamp of the Uber pickup  
- **Lat, Lon**: Latitude and longitude of the pickup location  
- **Base**: TLC base company code  

#### 🚕 Uber Trip Data (2015)  
- **Dispatching_base_num**: TLC base that dispatched the Uber  
- **Pickup_date**: Date and time of the Uber pickup  
- **Affiliated_base_num**: Base affiliated with the Uber pickup  
- **locationID**: Pickup location ID  

#### 🚘 Non-Uber FHV Trips  
- **Trip details for 10 FHV companies** (Lyft, Carmel, Skyline, etc.)  
- **Data includes** pickup time, location, driver license number, vehicle license number  

#### 📊 Aggregate Statistics  
- **Daily pickup data** for 329 FHV companies (January - August 2015)  
- **Uber trip statistics** (January - February 2015)  

## 🛠️ Tools & Technologies  
- **Python, SQL, Excel**: Data processing and analysis  
- **Machine Learning**: Predictive modeling for trip demand  
- **Jupyter Notebook / VS Code**: Development environment  

## 🔍 Key Objectives  
- Perform **Exploratory Data Analysis (EDA)** to identify trends in ride demand  
- Build a **predictive model** for trip demand forecasting  
- Analyze **busiest pickup locations, peak hours, and fare estimations**  
- Visualize **trip distributions and patterns**  

## 📌 Steps & Implementation  
1. **Data Preprocessing**  
   - Clean missing values and format timestamps  
2. **Exploratory Data Analysis (EDA)**  
   - Identify peak times, busiest days, and location-based trends  
3. **Feature Engineering**  
   - Extract relevant features for trip demand prediction  
4. **Model Building**  
   - Train machine learning models for demand forecasting  
5. **Model Evaluation**  
   - Assess model accuracy and performance  
6. **Visualization**  
   - Use data visualization to present key insights  

## 📊 Project Difficulty Level  
**Advanced**  

## 🚀 Getting Started  
1. Clone the repository:  
   ```sh
   git clone https://github.com/AgnideepPoddar/Uber-Trip-Analysis.git
   ```    
2. Run the analysis scripts to explore insights.  

## 🤝 Contributions  
Contributions are welcome! Feel free to open issues or submit pull requests.  

## 📜 License  
This project is for educational purposes and follows the **MIT License**.  
