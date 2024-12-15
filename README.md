# Task Priority Prediction and To-Do List Management System

## Introduction
This project is a machine learning-powered **Task Priority Prediction and To-Do List Management System**. It helps users manage tasks by predicting their priority (Low, Medium, High) and maintaining an interactive to-do list. The system utilizes **Linear Regression** to predict priorities based on task descriptions.

## Features
- **Priority Prediction**:
  - Predicts task importance (Low, Medium, or High) using a trained machine learning model.
- **To-Do List Management**:
  - Add tasks with automatic priority prediction.
  - View all tasks with their priority and status.
  - Mark tasks as "done."
  - Delete tasks from the list.
- **Machine Learning Integration**:
  - Uses **Linear Regression** to analyze task descriptions and predict priorities.

## Purpose
- Enhance task management by automating priority predictions.
- Provide an intuitive interface to track and organize tasks.
- Demonstrate the application of **Linear Regression** in a real-world project.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas` - For handling data in table format.
  - `scikit-learn` - For machine learning (Linear Regression, TF-IDF vectorization).
  - `TfidfVectorizer` - To convert task descriptions into numerical data.
  - `mean_squared_error` - To evaluate the machine learning model.

## How It Works
1. **Training the Model**:
   - The system uses a small dataset of task descriptions and their corresponding priorities to train a **Linear Regression model**.
   - Text data is converted into numerical vectors using **TF-IDF Vectorizer**.
2. **Priority Prediction**:
   - When a new task is added, the model predicts its priority based on the task description.
3. **Interactive To-Do List**:
   - Users can manage their tasks through a simple menu-driven interface.

## Getting Started

### Prerequisites
- Install Python (version 3.7 or above).
- Install required libraries using `pip`:
  ```bash
  pip install pandas scikit-learn
