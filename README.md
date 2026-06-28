# 🚗 Vehicle Counting System Using CNN

## Overview

The **Vehicle Counting System Using Convolutional Neural Networks (CNN)** is a deep learning-based application developed to automatically detect and count vehicles from traffic images. The system eliminates the need for manual vehicle counting by using a trained CNN model to identify different categories of vehicles and display their total count through a simple web interface.

The primary goal of this project is to provide an efficient, accurate, and automated solution for vehicle counting that can support traffic monitoring and management.

---

# Objectives

* To automate the process of vehicle counting.
* To reduce manual effort and counting errors.
* To classify vehicles into different categories.
* To provide an easy-to-use web-based interface.
* To improve the efficiency of traffic monitoring.

---

# Features

* Automatic vehicle detection from uploaded images.
* Vehicle counting using a trained CNN model.
* Supports multiple vehicle categories.
* Displays category-wise and total vehicle counts.
* Simple and responsive web interface.
* Fast and accurate prediction.

---

# Vehicle Categories

The system is trained to detect the following vehicle classes:

* Car
* Bus
* Truck
* Bike
* Van
* Bicycle
* Rickshaw

---

# Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Flask

### Deep Learning

* TensorFlow
* Keras
* Convolutional Neural Network (CNN)

### Image Processing

* OpenCV
* Pillow (PIL)
* NumPy

---

# Project Workflow

1. The user uploads a traffic image through the web application.
2. The uploaded image is preprocessed before being sent to the CNN model.
3. The trained CNN model analyzes the image and detects different types of vehicles.
4. Each detected vehicle is classified into its respective category.
5. The system counts the number of vehicles in each category.
6. The final results are displayed on the web interface.

---

# Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/vehicle-counting-system.git
cd vehicle-counting-system
```

### Step 2: Create a Virtual Environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/Mac**

```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Required Packages

```bash
pip install -r requirements.txt
```

If you don't have a `requirements.txt` file, install the packages manually:

```bash
pip install flask tensorflow keras opencv-python numpy pillow
```

---

# Running the Application

Start the Flask server using:

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

# Expected Output

After uploading a traffic image, the application displays:

* Number of Cars
* Number of Buses
* Number of Trucks
* Number of Bikes
* Number of Vans
* Number of Bicycles
* Number of Rickshaws
* Total Vehicle Count

---

# Applications

* Traffic Monitoring
* Smart Traffic Management
* Highway Vehicle Counting
* Parking Management
* Smart City Projects
* Transportation Planning

---

# Future Enhancements

* Real-time CCTV video processing
* Live vehicle counting
* Traffic density analysis
* Speed estimation
* Dashboard with graphical reports
* Cloud deployment
* Mobile application integration

---

# Advantages

* Fully automated vehicle counting
* Reduces manual effort
* Faster than traditional counting methods
* Easy to use
* Scalable for different traffic environments
* Cost-effective solution

---

# Requirements

* Python 3.10 or above
* Flask
* TensorFlow
* Keras
* OpenCV
* NumPy
* Pillow

---

# Developer

**E. Baby**
B.Tech – Electronics and Communication Engineering

---

# License

This project is developed for educational and academic purposes. It may be modified and extended for research or learning with appropriate acknowledgment.

---

# Acknowledgements

Special thanks to the open-source communities behind **TensorFlow**, **Keras**, **OpenCV**, **Flask**, and **Python** for providing the tools and libraries that made this project possible.
