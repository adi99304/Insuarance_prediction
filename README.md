# 📊 Insurance Data Analysis & Model Comparison

A Streamlit web application for analyzing insurance data and comparing different machine learning models for predicting insurance charges.

<img width="955" alt="image" src="https://github.com/user-attachments/assets/0d506ad0-2469-4384-9b3b-3d3b7822e662" />
<img width="952" alt="image" src="https://github.com/user-attachments/assets/ccf30d89-c0b8-4f1f-a2f5-519c10f4391b" />



## 🌟 Features

- **Data Upload**: Easily upload your own CSV dataset for analysis
- **Data Visualization**: Generate various plots to understand your data
  - Distribution plots
  - Scatter plots with optional color variables
  - Box plots for categorical analysis
  - Violin plots with data points
  - Correlation heatmaps for numeric features
- **Model Training**: Compare different regression models
  - Linear Regression
  - Decision Tree
  - Random Forest
- **Model Evaluation**: View performance metrics
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R-squared (R²)
- **Custom Predictions**: Test trained models with your own input values
  - Support for both numeric and categorical inputs
  - Includes demographic features (sex, smoker status, region)

## 📋 Requirements

- Python 3.8+
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly Express

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/insurance-data-analysis.git
   cd insurance-data-analysis
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📝 Usage

1. Upload your CSV file containing insurance data
   - Required columns: age, sex, bmi, children, smoker, region, charges
   - You can use the sample dataset provided in the `data` folder

2. Select plot types and variables to visualize your data

3. Choose a model type and train it on your data

4. Enter custom values to test predictions with your trained model

## 📚 Example Dataset

The app works with insurance datasets containing the following features:
- `age`: Age of the insured person
- `sex`: Gender of the insured (male/female)
- `bmi`: Body Mass Index
- `children`: Number of dependents
- `smoker`: Smoking status (yes/no)
- `region`: Residential area (northeast/northwest/southeast/southwest)
- `charges`: Insurance premium charges

## 🔄 Converting from R Shiny

This app was converted from an R Shiny dashboard to Python Streamlit. The conversion maintains the core functionality while leveraging Python's machine learning ecosystem.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

Your Name - [(https://github.com/adi99304)](https://github.com/adi99304/)

## 🙏 Acknowledgments

- [Streamlit](https://streamlit.io/) for the amazing framework
- [Scikit-learn](https://scikit-learn.org/) for machine learning tools
- [Plotly Express](https://plotly.com/python/plotly-express/) for interactive visualizations
