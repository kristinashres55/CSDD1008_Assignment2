For this Go Project, we need to run main.go file where the program prints a greeting message that includes the student's name "Kristina Shrestha" and student ID "500223379".
For running the program 
1. Clone the repository from (https://github.com/kristinashres55/CSDD1008_Assignment2)

# Property Price Prediction App

## Project Overview

This is a **Property Price Prediction App** that uses a neural network model (built with `brain.js`) to predict property prices based on features like area, bedrooms, bathrooms, location, and age. The app also includes data visualization to compare predicted prices with actual prices and displays feature importance.

### Key Features

- **Price Prediction**: Predict property prices using a trained neural network model.
- **Data Visualization**:
  - Compare predicted prices vs. actual prices using a line chart.
  - Display feature importance using a bar chart.
- **Model Management**:
  - Save the trained model to LocalStorage.
  - Load the model from LocalStorage.
  - Retrain the model if needed.

---

## How to Run Locally

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/kristinashres55/CSDD1008_Assignment2

   ```

2. **Install Dependencies**:

   ```bash
   npm install

   ```

3. **Run the App:**:
   ```bash
   npm start
   ```

The app will start on http://localhost:3000.

4. **Train the Model**:

- The app will automatically train the model when you first run it.
- You can also retrain the model by clicking the "Retrain Model" button.

5. **Make Predictions**:

- Enter property details (area, bedrooms, bathrooms, location, age) and click "Predict Price" to see the predicted price.

---

### Features & Technologies Used

**Price Prediction**:
- Predict property prices using a neural network model.

**Data Visualization**:
- Line Chart: Compare predicted prices vs. actual prices.
- Bar Chart: Display feature importance.

**Model Management**:
- Save and load the trained model to/from LocalStorage.

### Technologies Used
- **Frontend**:
    - React.js
    - Chart.js (for data visualization)

- **Machine Learning**:
    - brain.js (neural network library)

- **Styling**:
    - Tailwind CSS (for responsive and modern UI)

- **Build Tool**:
    - Vite (for fast development and production builds)

---

### Contact
For questions or feedback, feel free to reach out:

- Your Name: kristinashrestha2055@gmail.com

- GitHub: kristinashres55

1. **Price Prediction Form**: A screenshot of the form where users input property details.
2. **Predicted vs. Actual Prices Chart**: A screenshot of the line chart comparing predicted and actual prices.
3. **Feature Importance Chart**: A screenshot of the bar chart showing feature importance.

---
