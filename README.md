# Forecasting Volatility of Various Cryptocurrencies

## **Overview**

This project investigates various methodologies for forecasting volatility within cryptocurrency markets. The primary objective is to identify the most effective models and understand the key factors influencing predicted volatility. The insights gained can be applied to algorithmic trading strategies, risk management frameworks, and the pricing of cryptocurrency options.

This individual project builds upon prior group work by exploring six distinct econometric and machine learning models to predict the volatility of six different cryptocurrencies across varying time resolutions. The performance of these models is rigorously compared using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and the Diebold-Mariano (DM) Test.

A key finding of this study is the robustness of the traditional econometric forecasting method, Exponentially Weighted Moving Average (EWMA), which provided competitive results and served as a sufficient baseline against more advanced machine learning models.

Final report can be found [here](final_report.pdf)

## **Repository Structure**

```bash
crypto-rv-forecast/
├── data/             # Raw, processed, and external datasets
├── notebooks/        # Jupyter notebooks for data analysis, modeling, and experimentation
├── reports/          # Project documentation including proposal, literature review, and the final report
├── results/          # Model outputs, visualizations, and evaluation logs
├── environment.yml     # Conda environment configuration file
├── requirements.txt    # Pip requirements file (alternative to environment.yml)
└── README.md         # Project overview and setup instructions (this file)
```

---

## **Getting Started**

This section guides you through the necessary steps to set up and run the project.

### **Prerequisites**

* Python 3.10 or higher
* Conda package manager (recommended) or pip

### **Setup**

**Using Conda (Recommended):**

1.  Clone the repository:
    ```bash
    git clone [https://github.com/zhyoung17/crypto-rv-forecast.git](https://github.com/zhyoung17/crypto-rv-forecast.git)
    cd crypto-rv-forecast
    ```
2.  Create the Conda environment:
    ```bash
    conda env create -f environment.yml
    conda activate crypto-rv-forecast
    ```

**Alternatively, using venv and pip:**

1.  Clone the repository:
    ```bash
    git clone [https://github.com/zhyoung17/crypto-rv-forecast.git](https://github.com/zhyoung17/crypto-rv-forecast.git)
    cd crypto-rv-forecast
    ```
2.  Create a virtual environment:
    ```bash
    python3 -m venv env
    source env/bin/activate  # On macOS and Linux
    # env\Scripts\activate   # On Windows
    ```
3.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### **Running Jupyter Notebooks**

1.  Navigate to the `notebooks` directory:
    ```bash
    cd notebooks
    ```
2.  Start Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```
3.  Open the desired notebooks and follow the instructions within.

---

## **Datasets**

This project utilizes publicly available datasets for analysis:

* **Cryptocurrency Price History:** Hourly resolution historical price data for Bitcoin (BTC), Ethereum (ETH), Solana (SOL), Ripple (XRP), and Dogecoin (DOGE). Data was obtained using the Yahoo Finance API.

## **Contact**

For any questions, suggestions, or feedback regarding this project, please feel free to reach out to:

* **Young Zhan Heng:** [GitHub](https://github.com/zhyoung17/)

---

## **Acknowledgement**

This individual project was completed by **Young Zhan Heng**, a student at the National University of Singapore. It builds upon the foundational work of a group project that included the following contributors:

* Ethan Cheung ([GitHub](https://github.com/ethan-cyj/))
* Young Zhan Heng ([GitHub](https://github.com/zhyoung17/))
* Luo Xinming ([GitHub](https://github.com/kiwi-lemongrass))

I would like to express my sincere gratitude to all the educators who have guided me throughout my undergraduate education at NUS, and especially to my project mentor, Professor Huang Ta Cheng, for his invaluable guidance and support.

---
