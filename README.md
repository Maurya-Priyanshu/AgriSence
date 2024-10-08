# AgriSense: Precision Crop Selection Using Weather and Soil Data

## Overview
AgriSense is an innovative precision agriculture tool designed to optimize crop selection by leveraging real-time weather data and comprehensive soil nutrient analysis. The primary objective of AgriSense is to enhance agricultural productivity, improve resource management, and promote sustainable farming practices by providing farmers with data-driven insights.

## Features
- **Real-Time Weather Integration**: AgriSense collects and analyzes weather data, including temperature, humidity, precipitation, and more, to recommend the most suitable crops.
- **Soil Nutrient Analysis**: The system evaluates soil nutrients (N, P, K levels, pH, etc.) to ensure the selected crops are compatible with the soil conditions.
- **Machine Learning Algorithms**: AgriSense uses advanced algorithms, particularly Random Forest, to process and analyze data, delivering highly accurate crop recommendations.
- **User-Friendly Interface**: The platform offers an intuitive interface, making it easy for farmers to input their data and receive actionable recommendations.
- **Future Enhancements**: Plans include direct API data integration, expanded datasets, crop yield predictions, and more farmer-friendly features.

## Installation

### Prerequisites
- **Python 3.8+**
- **pip** (Python package installer)
- Libraries: `numpy`, `pandas`, `scikit-learn`, `flask`, `matplotlib`, `requests`, etc.

### Clone the Repository
```bash
git clone https://github.com/Maurya-Priyanshu/AgriSence
cd agrisense
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python app.py
```

The application will be accessible at `http://localhost:5000` in your web browser.

## Usage

### Data Input
1. **Weather Data**: Input current and forecasted weather parameters.
2. **Soil Data**: Enter soil nutrient levels including nitrogen (N), phosphorus (P), potassium (K), pH, and more.
3. **Crop Recommendation**: Based on the input data, AgriSense provides the best crop choices for your farm.

### Example Workflow
1. Launch the application.
2. Navigate to the input section.
3. Enter weather and soil data.
4. View the crop recommendations, including additional tips for crop management.

## Project Structure
- **app.py**: Main application file to run the server.
- **models/**: Contains machine learning models used for crop prediction.
- **static/**: Static files like CSS, JS, and images.
- **templates/**: HTML templates for the web interface.
- **data/**: Sample datasets and scripts for data preprocessing.
- **notebooks/**: Jupyter notebooks for data analysis and algorithm testing.


## Contact
For any questions or suggestions, feel free to reach out to:
- **Priyanshu Maurya**
- Email: [priyanshumau2021@gmail.com](mailto:priyanshumau2021@gmail.com)
- GitHub: [Maurya-Priyanshu](https://github.com/Maurya-Priyanshu)

---

Thank you for using AgriSense!  
