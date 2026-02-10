
# Portfolio Diversification Analyzer
Developer & Creator: tubakhxn

## What is this project about?
This project helps you analyze how diversifying your investment portfolio across multiple stocks can reduce risk. It fetches historical stock data, calculates correlations between asset returns, and visualizes them with a heatmap. You can see how combining assets with low or negative correlation can make your portfolio safer.

## What is Diversification?
Diversification is an investment strategy that involves spreading investments across various financial assets, industries, or other categories to reduce exposure to any single asset or risk. The goal is to minimize the impact of poor performance from any one investment on the overall portfolio.

## Why Does Correlation Matter?
Correlation measures how two assets move in relation to each other. If two assets are highly correlated, their prices tend to move together, reducing the benefits of diversification. Low or negative correlation between assets means that when one asset performs poorly, another may perform well, helping to reduce overall portfolio risk.

## How to Read the Correlation Heatmap
The correlation heatmap visualizes the correlation coefficients between asset returns. Values close to 1 (red) indicate strong positive correlation, values close to -1 (blue) indicate strong negative correlation, and values near 0 (white) indicate little or no correlation. Diversification is most effective when assets have low or negative correlations.

## How to Run the Project
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the analyzer:
   ```bash
   python diversification.py
   ```
3. Follow the prompts to enter stock tickers and date range.

The script will fetch historical data, calculate correlations, and display a heatmap to help you analyze diversification benefits.

## How to Fork This Project
1. Click the "Fork" button at the top right of the repository page on GitHub.
2. Clone your forked repository:
   ```bash
   git clone https://github.com/yourusername/Portfolio-Diversification-Analyzer.git
   ```
3. Make your changes and push to your fork.
4. Optionally, create a pull request to contribute improvements.
