# Off-the-Shelf Medicine Management System for Medical Dispensaries

A medicine management system designed for use in medical dispensaries to efficiently manage and track inventory, as well as predict diseases based on symptoms.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Inventory Management](#inventory-management)
- [Machine Learning for Disease Prediction](#machine-learning-for-disease-prediction)
- [Symptom Prediction](#symptom-prediction)
- [Files and Directory Structure](#files-and-directory-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

The Off-the-Shelf Medicine Management System is a comprehensive solution for medical dispensaries to effectively manage their medicine inventory and assist in disease diagnosis based on patient symptoms. This system streamlines inventory tracking, sales, and symptom-based disease prediction, making it an essential tool for healthcare providers.

## Features

- **Inventory Management:** Efficiently manage medicine inventory, including adding new medicines, updating stock, and removing out-of-stock items.
- **Sales:** Perform medicine sales, update stock availability, and manage shelf, row, and rack numbers.
- **Machine Learning for Disease Prediction:** Utilize machine learning models for disease prediction based on patient symptoms.
- **Symptom Prediction:** Predict diseases based on a list of patient symptoms, assisting healthcare professionals in diagnosis.
- **User-Friendly Interface:** A user-friendly interface makes it easy for staff to navigate and use the system.

## Getting Started

Follow these instructions to set up and start using the Off-the-Shelf Medicine Management System.

### Prerequisites

Before getting started, ensure you have the following prerequisites:

- Python (version X.X.X)
- Pandas (version X.X.X)
- Scikit-learn (version X.X.X)
- Matplotlib (version X.X.X)
- Seaborn (version X.X.X)
- Other necessary libraries (see requirements.txt)

### Installation

1. Clone this repository to your local machine:

   ```bash
   $ git clone https://github.com/yourusername/medicine-management-system.git
   $ cd medicine-management-system
Install the required Python libraries using pip:

    ```bash

    $ pip install -r requirements.txt
## Usage
The Off-the-Shelf Medicine Management System offers the following functionalities:

## Inventory Management
The system allows you to manage your medicine inventory efficiently. You can perform tasks such as adding new medicines, updating stock quantities, and removing items that are out of stock.

## Machine Learning for Disease Prediction
This system incorporates machine learning models for disease prediction. It uses patient symptoms to predict potential diseases, aiding healthcare professionals in diagnosis.

## Symptom Prediction
You can predict diseases based on a list of patient symptoms. Simply provide a comma-separated list of symptoms, and the system will generate predictions.

    ```python

    from medicine_management_system import predictDisease

    symptoms = "Fever, Cough, Fatigue"
    predictions = predictDisease(symptoms)
    print(predictions)
## Files and Directory Structure
The project directory is organized as follows:

    medicine-management-system/
      ├── data/
      │   ├── Medicine.csv
      │   ├── Training.csv
      │   └── Testing.csv
      ├── models/
      │   ├── svm.pkl
      │   └── random_forest.pkl
      ├── medicine_management_system.py
      ├── README.md
      ├── requirements.txt
      └── other_files/
## Contributing
Contributions to this project are welcome! Please follow our contributing guidelines to get started.

## License
LICENSE file for details.

## Acknowledgments
We would like to acknowledge the following resources and libraries that contributed to the success of this project:

    Pandas
    Scikit-learn
    Matplotlib
    Seaborn
