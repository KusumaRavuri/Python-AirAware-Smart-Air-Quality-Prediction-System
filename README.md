# Python-AirAware-Smart-Air-Quality-Prediction-System


## 📖 Introduction

The **Smart Air Quality Monitoring Dashboard** is a web-based application developed using **Streamlit**.
It helps users **monitor, analyze, and understand air pollution data** in a visual and interactive way.

The project mainly focuses on:

* **Air Quality Index (AQI)**
* **PM2.5 pollution**
* Other pollutants like **NO₂** and **O₃**

This dashboard converts raw air quality data into **easy-to-understand charts and alerts**, making it useful for students, researchers, and the general public.

---

## 🎯 Purpose of the Project

The main purpose of this project is:

* To display air quality data in a **simple and clear format**
* To help users understand **how polluted the air is**
* To show **health warnings** based on AQI values
* To allow easy upload and analysis of air quality datasets

---

## ⚙️ How the Project Works

1. The application starts with an **animated Earth loading screen**
2. Users can select:

   * Monitoring station
   * Time range (Last 24 Hours or Last 7 Days)
3. In **Admin Mode**, users can upload a CSV file containing air quality data
4. The system:

   * Reads and cleans the dataset
   * Converts date columns to proper format
   * Calculates AQI if it is missing
5. The dashboard displays:

   * Current AQI
   * PM2.5 trend graph
   * Multiple pollutant trends
   * Daily air quality alerts

---

## ✨ Features

* 📊 **AQI Donut Chart** showing current air quality
* 📈 **PM2.5 Trend Graph** over time
* 📉 **Pollutant Trend Analysis** for PM2.5, NO₂, and O₃
* 📅 **Daily Air Quality Alerts** based on AQI levels
* 📂 **CSV File Upload** for air quality data
* 🎛 **Simple Sidebar Controls**
* 🌐 **Smooth User Interface with Loader Animation**

---

## 🧪 Dataset Requirements

The uploaded CSV file should contain:

* `Date` or `Datetime` column (required)
* `PM2.5` column (required)
* Optional columns:

  * `NO2`
  * `O3`
  * `AQI`

👉 If the **AQI column is not available**, the system automatically calculates AQI using PM2.5 values.

---

## 🛠 Technologies Used

* **Python** – Programming language
* **Streamlit** – Web application framework
* **Plotly** – Interactive charts and graphs
* **Pandas** – Data handling and processing
* **NumPy** – Numerical calculations
* **HTML & CSS** – Custom loader animation

---

## ▶ How to Run the Project

1. Install required libraries:

```bash
pip install streamlit plotly pandas numpy
```

2. Run the application:

```bash
streamlit run app.py
```

3. Open the browser link shown in the terminal.

---

## 🚦 Air Quality Levels and Alerts

| AQI Value | Air Quality Level | Description                        |
| --------- | ----------------- | ---------------------------------- |
| 0 – 50    | Good              | Air is clean and safe              |
| 51 – 100  | Moderate          | Sensitive people should be careful |
| 101 – 200 | Poor              | Avoid long outdoor activities      |
| Above 200 | Severe            | Health emergency condition         |

---

## 📌 Applications of the Project

* Academic and college projects
* Air pollution monitoring studies
* Smart city demonstrations
* Public awareness about air quality

---

## 🚀 Future Improvements

* Live air quality data using sensors (IoT)
* Location-based air quality tracking
* Machine learning-based AQI prediction
* Mobile and tablet support

---

## 👩‍🎓 Author

**Kusuma Ravuri**
Student – Computer Science 


