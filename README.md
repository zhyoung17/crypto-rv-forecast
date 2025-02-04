# DSE4101-Group

Code repository for group component of final year Capstone project.

# **Volatility Forecasting in Cryptocurrency Markets**

## **Overview**

This project focuses on exploring and evaluating various methodologies for forecasting volatility in cryptocurrency markets. The primary goal is to identify the best models and key driving features of predicted volatility, with applications in algorithmic trading, risk management, and cryptocurrency options pricing. Additionally, we aim to corroborate findings from literature by training similar models and adapting them to different use cases across varying time resolutions.

---

## **Repository Structure**

```bash
volatility-forecasting-project/
├── data/                  # Raw, processed, and external datasets
├── notebooks/             # Jupyter notebooks for analysis and modeling
├── scripts/               # Python scripts for data processing, modeling, and evaluation
├── reports/               # Proposal, literature review, and final report
├── results/               # Model outputs, plots, and logs
├── environment.yml        # Conda environment setup
└── README.md              # Project overview (this file)
```

---

## **Features**

* **Comprehensive Literature Review** : Evaluation of traditional statistical models, machine learning techniques, and hybrid approaches.
* **Model Training and Evaluation** : Testing models like GARCH, LSTM, Random Forests, and hybrid approaches.
* **Feature Selection** : Incorporating market sentiment, macroeconomic indicators, and volume-based features.
* **Applications** : Adapting forecasting techniques for algorithmic trading, options pricing, and long-term investment strategies.

---

## **Getting Started**

### **Prerequisites**

* Python 3.10+
* Conda package manager (or pip)

### **Setup**

1. Clone the repository:
   ```bash
   git clone https://github.com/ethan-cyj/DSE4101-Group.git
   cd DSE4101-Group
   ```
2. Create the environment (on macOS):
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### **Run Jupyter Notebooks**

---

## **Datasets**

The project uses publicly available datasets:

* **Cryptocurrency Price History** : Daily and minute-resolution data for Bitcoin, Ethereum, and other cryptocurrencies.
* **Sentiment Data** : Extracted from platforms like Twitter and Reddit (e.g., WallStreetBets subreddit).
* **Macroeconomic Indicators** : From the FREDMD database (e.g., GDP, inflation). 
* **Bitcoin Futures Data** : Includes futures prices and implied volatility.

---

## **Contributing**

Contributions are welcome! To collaborate:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes and push:
   ```bash
   git commit -m "Add your feature description"
   git push origin feature/your-feature-name
   ```
4. Open a pull request.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](https://chatgpt.com/g/g-678f118d47f081918da95d90bd10d502-dse4101-fyp-assistant/c/LICENSE) file for more details.

---

## **Contact**

For questions or suggestions, feel free to reach out:

* **[Ethan Cheung](https://github.com/ethan-cyj/)**
* **[Young Zhan Heng](https://github.com/zhyoung17/)**
* [**Luo Xinming**](https://github.com/team-member-2)
