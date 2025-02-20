# 🚍 Real-Time Public Transit Optimization and Analytics Platform 🚦

## 🌟 Overview
This platform tackles the operational and logistical challenges of public transit in the San Francisco Bay Area. By combining **real-time data**, **predictive analytics**, and **user-friendly visualizations**, it enhances transit efficiency and reliability, offering actionable insights for city planners, transit authorities, and passengers.

---

## ✨ Features
- **📡 Real-Time Data Integration**: Stream live data from sources like 511.org, OpenWeatherMap API, and Google Maps Directions API using Apache Kafka.
- **🤖 Predictive Analytics**: Machine learning models forecast delays and optimize routes dynamically.
- **📊 Interactive Dashboards**: Tableau-powered visualizations display transit performance, delay trends, and optimization opportunities.
- **🔔 Real-Time Alerts**: Notify passengers about delays and alternate routes for an improved commuting experience.
- **🗂️ Dimensional Modeling**: Fact and dimension tables enable advanced analytics and smarter decision-making.

---

## 🛠️ Tools and Technologies
- **⚡ Data Streaming**: Apache Kafka  
- **💾 Data Storage**: AWS S3  
- **🔄 ETL**: AWS Glue, AWS Glue DataBrew  
- **🗃️ Database**: PostgreSQL on AWS RDS  
- **📈 Visualization**: Tableau   
- **💻 Programming Languages**: Python, SQL  (ETL scripts, API integrations)
- ![image](https://github.com/user-attachments/assets/20440263-a66e-4c1e-9295-ee3ce62ce833)


---

## 🔬 Methodology
1. **🛠️ Data Collection**: Streamed real-time and historical data from APIs into Kafka topics and stored in AWS S3 buckets.
2. **🔄 Data Transformation**: Unnested and preprocessed data using AWS Glue DataBrew, then applied dimensional modeling.
3. **📥 Data Loading**: Stored transformed data in a PostgreSQL database hosted on AWS RDS.
4. **📊 Dashboard Creation**: Connected PostgreSQL to Tableau for interactive visualizations.

---

## 🏆 Results
- 🗺️ **Geospatial Dashboards**:
  - Distribution of delays and their correlation with weather and traffic events.
  - Passenger demand trends and seat availability visualization.
- 🚦 **Insights**:
  - Traffic events were identified as a primary cause of delays during analysis.

---

## 🚀 Future Improvements
- **🤖 Advanced Machine Learning**: Use LSTM and GNN models for more accurate predictions.
- **🌐 Multimodal Transit Integration**: Include rideshares, bicycles, and scooters.
- **📱 Mobile App Development**: Offer personalized commute suggestions and live updates.
- **⚡ Latency Optimization**: Achieve sub-second real-time data processing.

---

## 🛠️ Installation and Setup
1. **🔗 Clone the repository**:
   ```bash
   git clone https://github.com/your-repository-link.git
   cd project-directory
   ```
2. **📦 Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **🔑 Set up AWS credentials** for S3 and Glue.
4. **📜 Create the database schema** in PostgreSQL using the provided SQL scripts in `schema/`.
5. **📊 Connect Tableau** to PostgreSQL for dashboard creation.

