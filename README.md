# eBay Sandbox Portfolio Project

This project demonstrates how to use the **eBay Developer Sandbox APIs** in a data analyst context. It focuses on authentication and sandbox data retrieval using Python and Jupyter Notebook.

## What's Included

- OAuth 2.0 Authentication (Client Credentials Flow)
- Sample data retrieval using **Browse API** in Sandbox
- Structured notebook format for portfolio presentation
- Secure `.env` setup to manage API credentials

## 🚫 What’s Not Included

- No live marketplace data (Sandbox-only)
- No use of the Taxonomy API (not supported in sandbox)

## Tools Used

- Python 3.x
- VS Code
- `requests` library
- `.env` file for secret management

## How to Run This Project

1. **Clone the repo**  
   ```bash
   git clone https://github.com/YOUR_USERNAME/ebay-sandbox-portfolio.git
   cd ebay-sandbox-portfolio

2. **Create a .env file in the root directory with your sandbox API credentials:**
    EBAY_CLIENT_ID=your_sandbox_client_id
    EBAY_CLIENT_SECRET=your_sandbox_client_secret

3. **Install dependencies**
    pip install -r requirements.txt

4. **Launch the Jupyter Notebook**
    Then open eBay_Price_Comparison.ipynb and run the cells.

## Disclaimer
This is a personal portfolio project using eBay’s Sandbox API, which provides fake data for development purposes only. No production data is accessed or stored. This project is compliant with the eBay Developer Program Agreement.

## Project Structure
.
├── eBay_Price_Comparison.ipynb
├── .env               # (excluded via .gitignore)
├── .gitignore
├── README.md
└── requirements.txt   # (optional, for pip install)
