

## 🤖 Project 2: Tire Degradation Prediction with ML

Using **Linear Regression** (Scikit-Learn) to analyze how tire wear affects lap times for Max Verstappen during the 2024 Bahrain GP.

### 🎯 Objective
To calculate the **Degradation Rate** (seconds lost per lap due to tire wear) using historical lap time data.

### 🧠 Methodology
1.  **Data Extraction:** Filtered for `SOFT` compound tires and `Accurate` laps (removing pit stops/VSC).
2.  **Model:** Trained a Linear Regression model on 80% of the data.
3.  **Result:** Calculated the slope (coefficient) of the trend line.

### 📈 Results
![Tire Degradation](tire_degradation.png)
* *The black line represents the predicted tire wear trend over time.*

### ⚠️ Engineering Note
The observed degradation rate might be lower than expected due to the **Fuel Effect**. As the race progresses, the car burns fuel (~100kg total), becoming lighter and faster, which partially masks the time lost to tire wear.
