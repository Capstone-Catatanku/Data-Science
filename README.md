# 🧠 Financial Data Analysis Project

The Financial Data Analysis Project is a comprehensive data analysis and visualization project that aims to provide insights into financial transactions. The project leverages data wrangling, exploratory data analysis (EDA), and visualization techniques to uncover spending patterns, transaction trends, and category-based financial insights.

The project focuses on transforming raw transaction data into meaningful information through data cleaning, preprocessing, feature engineering, and visualization using popular Python libraries.

## 🚀 What Does This Project Do?

* Data cleaning and preprocessing using Pandas and NumPy
* Exploratory Data Analysis (EDA)
* Data visualization using Matplotlib and Seaborn
* Data transformation and feature engineering
* Financial transaction analysis and insight generation
* Support for CSV and Excel datasets
* Trend analysis based on transaction dates and categories

---

## 📊 Dataset Overview

This project uses a cleaned financial transaction dataset containing personal finance records collected between August 2019 and December 2024.

### Dataset Statistics

| Metric         | Value                       |
| -------------- | --------------------------- |
| Total Records  | 37,291                      |
| Total Features | 4                           |
| Date Range     | August 2019 – December 2024 |
| File Format    | CSV                         |

### Dataset Features

| Column              | Description                                   |
| ------------------- | --------------------------------------------- |
| tanggal             | Transaction date                              |
| deskripsi_transaksi | Description of the transaction                |
| kategori            | Transaction category                          |
| nominal             | Transaction amount in Indonesian Rupiah (IDR) |

### Transaction Categories

The dataset includes multiple transaction categories such as:

* Belanja (Shopping)
* Konsumsi (Food & Consumption)
* Tagihan (Bills & Utilities)
* Transportasi (Transportation)
* Kesehatan (Healthcare)
* Hiburan (Entertainment)
* Investasi (Investment)
* Pendapatan (Income)
* Lain-lain (Others)

### Sample Data

| Tanggal    | Deskripsi Transaksi                           | Kategori  | Nominal |
| ---------- | --------------------------------------------- | --------- | ------- |
| 2023-06-03 | order mesin bor skill | Belanja | 325,000 |
| 2021-06-13 | jajan rames ayam pop deket kosan              | Konsumsi  | 131,000 |
| 2023-03-14 | saham tlkm telkom fundamental kuat            | Investasi | 86,150  |

### Dataset Purpose

The cleaned dataset is intended for:

* Financial behavior analysis
* Spending pattern identification
* Income and expense tracking
* Category-based expenditure analysis
* Time-series trend analysis
* Data visualization and reporting
* Machine learning and predictive analytics experiments

---

## 🛠️ Tech Stack

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Python Dateutil
* Jupyter Notebook

---

# 📦 Installation

It is recommended to use a virtual environment before running the project to keep dependencies isolated.

## 1. Clone Repository

```bash
git clone https://github.com/Capstone-Catatanku/Data-Science.git
cd Data-Science
```

## 2. Create Virtual Environment

### Windows

```bash
python -m venv venv
```

### Linux/macOS

```bash
python3 -m venv venv
```

## 3. Activate Virtual Environment

### Windows (Command Prompt)

```bash
venv\Scripts\activate
```

### Windows (PowerShell)

```bash
venv\Scripts\Activate.ps1
```

### Linux/macOS

```bash
source venv/bin/activate
```

## 4. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy python-dateutil jupyter
```

Or install using a requirements file:

```bash
pip install -r requirements.txt
```

---

# 💻 Usage

## 1. Start Jupyter Notebook

```bash
jupyter notebook
```

## 2. Open the Notebook

Open:

```text
Progress1.ipynb
```

## 3. Run the Analysis

Execute all notebook cells to perform:

* Data preprocessing
* Data cleaning
* Exploratory Data Analysis (EDA)
* Statistical analysis
* Data visualization
* Insight generation

---

## 📂 Project Structure

```text
project/
│── Data-clean/
│   │── Data-clean.csv                   
│
│── RawData/
│   │── gofood_food_overviews.csv            
│   │── produk_tokopedia.csv
|   │── Sintesis_Data.csv            
│
│── .gitignore
│── Data-pure.csv
│── Data_Dictionary_Keuangan_fix.xlsx
│── Progress1.ipynb
│── README.md
```

---

## 📈 Analysis Objectives

This project aims to answer questions such as:
- Di bulan apa total pengeluaran tertinggi terjadi dalam dua tahun terakhir?
- Apa perbedaan rata-rata pengeluaran antara akhir pekan dan hari  kerja dalam 6 bulan terakhir, dan kategori apa yang paling signifikan  penyebab perbedaan tersebut?
- Berapa total kerugian finansial dari transaksi outlier (2 SD di atas  rata-rata) dalam 1 tahun terakhir, dan berapa banyak yang  sebenarnya bisa dicegah jika saya menerapkan aturan 'tunggu 3 hari sebelum belanja >500rb'?


## Technical Report
https://drive.google.com/file/d/1VnePd5dlUXD865H7xTdwwXcPEsU1ikP_/view?usp=drive_link

---

## 📝 License

This project is licensed under the MIT License.

---

## 💖 Acknowledgements

A huge thanks to everyone who has contributed to this project. Your support, feedback, and contributions have helped improve the quality and impact of this work.

Special thanks to all team members involved in data collection, preprocessing, analysis, and project development.
