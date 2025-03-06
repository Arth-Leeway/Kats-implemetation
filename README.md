# Kats-Implementation  

This repository provides an implementation of the **Kats** library in 2025 for time series analysis and understanding. Kats is a lightweight, easy-to-use, and generalizable framework for time series data analysis.  

---

## 🚀 Installation  

We will be using a **Conda environment** for installation. Follow the steps below:  

### 1️⃣ Create a Conda Environment  

Navigate to your desired directory and create a Conda environment with Python 3.7:  

```sh
conda create --prefix ./env python=3.7
```

###2️⃣ Install Dependencies
##📌 Install fbprophet

```sh
conda install -c conda-forge fbprophet
```

##📌 Install Kats

```sh
pip install kats
```

###3️⃣ Downgrade packaging to Version 21.3
Kats requires a specific version of packaging. To resolve compatibility issues, downgrade it:

##✅ Reference for version change:
StackOverflow Solution
Downgrade Guide

###4️⃣ Ensure Compatibility of Prophet and Holiday Packages
To avoid errors, also downgrade prophet and holiday to their legacy versions:



###📊 Using Kats Library

After that you can start working with Kats Liabrary.
Above is code representing impemetation of TsFeature of Kats for understanding the feature relationship. And also plotted forcasting using Prophet which comes build in using Kats for time series data.
