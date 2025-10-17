# Financial Analysis and Valuation Dashboard

![Dashboard Screenshot](<URL_TO_YOUR_SCREENSHOT_HERE>)

A comprehensive web application built with Streamlit to perform financial analysis, including ratio calculation, DuPont analysis, and Discounted Cash Flow (DCF) valuation for publicly traded companies.

---

## 🚀 Features

* **Interactive Visualizations**: Uses Plotly to create dynamic charts for key financial ratios (Liquidity, Profitability, Solvency, etc.).
* **DuPont Analysis**: Breaks down the Return on Equity (ROE) into its core components to analyze operational efficiency, asset use, and financial leverage.
* **Company Comparison**: Allows for a side-by-side comparison of financial metrics across different companies.
* **DCF Valuation**: Implements both Free Cash Flow to Equity (FCFE) and Free Cash Flow to Firm (FCFF) models to estimate the intrinsic value per share.
* **User-Friendly Interface**: Clean and intuitive UI built with Streamlit, making complex financial analysis accessible.

---

## 🛠️ Technologies Used

* **Python**: Core programming language.
* **Streamlit**: For building and deploying the interactive web app.
* **Pandas**: For data manipulation and analysis.
* **Plotly Express**: For creating rich, interactive data visualizations.

---

## ⚙️ How to Run Locally

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Python 3.8 or higher
* pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

4.  **Run the Streamlit app:**
    ```sh
    streamlit run your_app_file_name.py
    ```

The application will open in your default web browser.

---

## 📄 `requirements.txt`

The dependencies for this project are listed in the `requirements.txt` file:

```text
streamlit
pandas
plotly
openpyxl
