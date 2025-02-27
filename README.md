# **Car Fare Price Prediction**

## **Overview**  
This project is a car fare price prediction system that leverages **AWS cloud services** for data processing, model training, and deployment. The prediction is based on two major factors: **distance and time**, which are acquired using the **TomTom API**.

---

## **Tech Stack**  
1. **AWS S3** - Data storage  
2. **AWS Glue (PySpark)** - ETL processing  
3. **AWS SageMaker** - Model training and deployment  
4. **EC2** - Hosting the deployed model  
5. **Power BI** - Dashboarding & Reporting  
6. **Streamlit** - Web application for predictions  
7. **TomTom API** - Fetching distance and time for fare calculations  

---

## **Project Workflow**  
1. **Data Collection** - Data is sourced from a structured dataset and enriched using **TomTom API** for real-time distance and time estimates.  
2. **ETL Process** - Data is ingested into **AWS S3**. **AWS Glue (PySpark)** processes and cleans the data through an ETL pipeline.  
3. **Model Training** - The processed data is used to train a **machine learning model** in **AWS SageMaker**. The trained model is deployed on an **EC2 instance** and as a **pickle file**.  

---

## **Prediction Service**  
- A **Streamlit web application** is developed for users to input pickup and drop-off locations.  
- The app fetches **distance and time (trip duration)** from the **TomTom API** and makes predictions using the **deployed model**.  

---

## **Deployment on AWS**  
1. **Data Storage** - Raw and processed data stored in **AWS S3**.  
2. **ETL Pipeline** - **AWS Glue** processes data and loads it for training.  
3. **Model Training & Deployment** - Model is trained in **SageMaker** and deployed on **EC2**.  
4. **Web Application** - **Streamlit app** hosted for real-time predictions.  

---

## **Future Enhancements**  
1. **Integrate more features** like weather and traffic conditions.  
2. **Integrate Kafka** for user inputs.  
3. **Optimize the ML model** for better accuracy.  
4. **Implement containerization** using **Docker** for easier deployment.  

---

## **Deployed Link and Repo**  
- **GitHub Repository of AWS Deployment**: [AWS_Deployment_Link](https://github.com/rishikeshdound/cloud_Deploy)  
- **Deployed App on Streamlit Cloud**: [Streamlit Deployment_Link](https://rishi-cabfare.streamlit.app/) *(Might be taken down)*  
- **Deployment**: Used Streamlit Cloud for free deployment. AWS deployment was deleted after testing.  

---




