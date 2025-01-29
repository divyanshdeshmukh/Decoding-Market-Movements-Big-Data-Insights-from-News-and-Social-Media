# Decoding Market Movements: Big Data Insights from News and Social Media

## Project Overview
This project analyzes financial news and stock price data using big data frameworks like **Apache Spark** and **Natural Language Processing (NLP)** techniques. By extracting key financial topics, assessing their sentiment, and correlating them with market volatility, we aim to provide actionable insights for investors and analysts.

## Team Members
- **Sun-Hye Baek** - Visualizations & Presentation
- **Rajvardhan Reddy Nandyala** - Keyword Extraction & Correlation Analysis
- **Ravi Teja Nalluri** - Data Collection, Preprocessing, Sentiment Analysis
- **Divyansh Deshmukh** - Literature Review, Sentiment Analysis Implementation
- **Shiva Shashank Adlagatta** - Data Collection, Correlation Analysis

## Features
- **Big Data Processing**: Utilizes **Apache Spark** for large-scale data handling.
- **Sentiment Analysis**: Implements **LLM-based sentiment scoring**.
- **Keyword Extraction**: Uses **TF-IDF** for financial term analysis.
- **Correlation Analysis**: Applies **Pearson correlation** to analyze stock price trends.
- **Data Visualization**: Generates **heatmaps and scatterplots** for insights.

## Dataset
We used the **Financial News and Stock Price Integration Dataset (FNSPID)** from Hugging Face, which contains:
- **Stock Prices**: Open, Close, High, Low, Volume.
- **Financial News**: Articles, publishers, timestamps, and sentiment labels.

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **Apache Spark**
- **PySpark**
- **NLTK** (Natural Language Toolkit)
- **Scikit-learn**
- **Hugging Face Transformers**

### Steps to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/decoding-market-movements.git
   cd decoding-market-movements
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start Apache Spark:
   ```bash
   pyspark
   ```
4. Run the main script:
   ```bash
   python main.py
   ```

## Directory Structure
```
├── data/                 # Raw and processed datasets
├── src/                  # Source code for preprocessing and analysis
│   ├── preprocess.py     # Data cleaning and transformation
│   ├── sentiment.py      # Sentiment analysis using NLP
│   ├── correlation.py    # Pearson correlation analysis
│   ├── visualization.py  # Data visualization scripts
├── results/              # Generated reports and visualizations
├── README.md             # Project documentation
├── requirements.txt      # Python dependencies
├── main.py               # Main execution script
```

## Results
- **Correlation Analysis:** Weak but notable correlation between sentiment scores and stock price trends.
- **Visualization Insights:** Heatmaps show limited but observable sentiment impact on volatility.
- **Conclusion:** Financial news sentiment is **one of many** factors influencing stock prices.

## Future Improvements
- **Integration of Macroeconomic Indicators** (e.g., interest rates, inflation)
- **Refinement with Advanced NLP Models** (e.g., FinBERT for finance-specific sentiment analysis)
- **Event-Based Analysis** for significant financial news impacts
- **Expansion to Additional Stocks and Sectors**

## License
This project is licensed under the **MIT License**.

## Contact
For any inquiries, feel free to reach out via GitHub Issues or contact the project members.

