# 🚗 Traffic Accident Frequency Modeling & Spatial-Temporal Analysis

## Project Overview

Traffic accidents are **rare events within the overall traffic system**. Therefore, modeling crash frequency requires constructing a complete **spatiotemporal exposure framework** that represents both crash and non-crash spatial-temporal combinations.

In this project, **OpenStreetMap (OSM)** was used to construct the spatial road-network framework, while **historical weather data** was used to establish the temporal context.

The spatial and temporal dimensions were combined through a **spatiotemporal Cartesian product**, generating a dataset with **millions of spatial-temporal observations**. Only a small subset of these observations corresponded to actual crashes, including the original **238,000+ crash records**.

This approach transforms the problem from analyzing only observed crashes into a **spatiotemporal crash-frequency modeling problem**, where both crash and non-crash conditions are represented.

## 🔬 Main Tasks

* **Data Cleaning & Preprocessing**
* **Temporal Feature Engineering**
* **Weather Data Integration**
* **OpenStreetMap Road-Network Extraction**
* **Spatiotemporal Dataset Construction**
* **Traffic Accident Frequency Modeling**
* **Regression Modeling**
* **Spatial Clustering**
* **Exploratory Data Analysis**
* **Model Evaluation & Feature Analysis**

## 🗺️ Spatiotemporal Framework

## 🛠️ Technologies

**Python · Pandas · NumPy · Scikit-learn · GeoPandas · OSMnx · Matplotlib · Seaborn · Jupyter Notebook**

## 📊 Dataset

* **238,582+ observed crashes**
* **191 original features**
* **2004–2023**
* **Allegheny County, Pennsylvania, USA**
* Integrated with **OpenStreetMap road-network data**
* Integrated with **historical weather data**
* Final spatiotemporal dataset: **millions of observations**

## 🎯 Objective

The primary objective is to develop a data-driven framework for **traffic accident frequency analysis and prediction** by incorporating:

* Spatial road-network characteristics
* Temporal and weather conditions
* Crash history
* Spatial clustering
* Regression-based frequency modeling

The resulting framework provides a foundation for analyzing **where and under what temporal and environmental conditions traffic accidents occur**, while explicitly accounting for the large number of spatial-temporal conditions in which no crash occurs.
