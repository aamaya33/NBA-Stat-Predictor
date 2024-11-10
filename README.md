# NBA Stat Predictor

This project is a web application designed to predict if a basketball player will reach a specified point threshold in upcoming games. Utilizing a machine learning model (XGBoost) and a FastAPI backend, the application combines player stats from various sources to deliver reliable performance predictions.

## Project Overview

The Player Performance Predictor integrates NBA data, machine learning, and a responsive user interface to provide insights on potential player performance. By leveraging Google Cloud Platform (GCP) for hosting and XGBoost for predictive modeling, this application aims to deliver accurate and fast predictions in a scalable environment.

## Features

- **Player Performance Prediction**: Input player names and point thresholds to get insights on whether they might achieve the desired score.
- **Machine Learning Model**: Utilizes XGBoost for efficient, high-accuracy predictions based on player stats and recent performance data.
- **Real-Time Data**: Integrates with NBA and other sports APIs to provide up-to-date player and game statistics.
- **Web Interface**: Built with a responsive and user-friendly frontend, allowing for seamless interactions.

## Project Goals

1. **Enable Data-Driven Decisions**: Provide users with reliable, data-backed predictions on player performance.
2. **Scalable and Performant**: Build a robust, fast backend using FastAPI and Google Cloud Platform.
3. **Intuitive UI**: Create a frontend that makes data insights accessible and engaging.

## Roadmap

### Week 1: Initial Research and Setup

1. **Data Acquisition**:
   - Research methods to fetch NBA player stats using `nba_api` and `basketball-reference` API.
   - Explore options for integrating with the `FanDuel` API.
2. **Platform and Hosting**:
   - Evaluate hosting options, with a preference toward **GCP** for easy integration with Firebase and scalability.

### Technology Stack

**Database**:  
- **MongoDB** - NoSQL database for flexible data storage and large datasets.
- **Firebase** - GCP integration and real-time data syncing.

**Hosting**:  
- **GCP** - Primary choice for hosting due to integration with Firebase and scalability.
- **AWS** - Alternative for robust infrastructure and ML workflow support.

**Backend**:  
- **FastAPI** - Asynchronous framework, ideal for microservices and efficient API handling.
- **Django** - Considered for large applications requiring high security, though more complex than FastAPI.
- **Flask** - Suitable for smaller projects requiring flexibility but lacks some features like async support.

**Frontend**:  
- **HTML/Tailwind CSS** - Responsive styling for a quick, modern interface.
- **Next.JS** - For server-side rendering with React, providing fast page loading times.
- **Angular** and **Bootstrap** - Considered for interactive and responsive UI development.

**Machine Learning Model**:  
- **XGBoost** - Chosen for high accuracy and efficiency, with an initial focus on classification to predict player points.
