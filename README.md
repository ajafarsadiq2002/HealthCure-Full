# MediScan360

MediScan360/HealthCure is an all-in-one medical solution web application that provides detection for multiple diseases including Alzheimer's, Brain Tumor, Breast Cancer, COVID-19, Diabetes, Heart Disease, and Pneumonia. The application allows users to upload relevant medical images and information for disease detection through an intuitive web interface.
# Sample Images
![MediScan360 Logo](https://github.com/ajafarsadiq2002/HealthCure-Full/blob/679baae68783a557e2a1c133b3ec7c50d362b745/HP.jpg)


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [File Descriptions](#file-descriptions)
- [Contributing](#contributing)

## Installation

To install and run this project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/MediScan360.git
    cd MediScan360
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application:**

    ```bash
    python app.py
    ```

5. **Open your web browser and navigate to:**

    ```
    http://localhost:5000
    ```

## Usage

- Navigate through the homepage to access various disease detection services.
- Fill in the required information on the respective disease detection page.
- Upload the relevant medical image (e.g., MRI, X-ray).
- Submit the form to receive the diagnosis result.

## Features

- **Homepage:** Provides an overview of all available disease detection services.
- **Alzheimer Detection:** Upload MRI images to detect Alzheimer's disease.
- **Brain Tumor Detection:** Upload MRI images to detect brain tumors.
- **Breast Cancer Detection:** Input specific medical details to detect breast cancer.
- **COVID-19 Detection:** Upload chest scans to detect COVID-19.
- **Diabetes Detection:** Input personal medical details to detect diabetes.
- **Heart Disease Detection:** Input specific medical details to detect heart disease.
- **Pneumonia Detection:** Upload chest scans to detect pneumonia.

## File Descriptions

- `app.py`: The main Flask application file.
- `requirements.txt`: Lists all the dependencies required to run the application.
- `templates/`: Contains all HTML templates for the web pages.
  - `homepage.html`: Homepage template.
  - `alzheimer.html`: Alzheimer detection page template.
  - `braintumor.html`: Brain tumor detection page template.
  - `breastcancer.html`: Breast cancer detection page template.
  - `covid.html`: COVID-19 detection page template.
  - `diabetes.html`: Diabetes detection page template.
  - `heartdisease.html`: Heart disease detection page template.
  - `pneumonia.html`: Pneumonia detection page template.
- `static/`: Contains static files like images and CSS used in the application.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/fooBar`).
3. Commit your changes (`git commit -am 'Add some fooBar'`).
4. Push to the branch (`git push origin feature/fooBar`).
5. Create a new Pull Request.
