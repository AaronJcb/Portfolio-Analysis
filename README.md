# Portfolio Optimization and Performance Evaluation

Welcome to the Portfolio Optimization and Performance Evaluation project! This analysis dives into modern portfolio management techniques, explores risk-adjusted returns, and applies advanced optimization methodologies to create an efficient portfolio. From exploring individual stock characteristics to designing an optimal portfolio, this project offers both a detailed exploration and a real-world approach to portfolio management.

[Access the Project on Google Colab](https://colab.research.google.com/drive/1PStobRGyd9dHu7n9nJjLgB7Ra4CKLu4e?usp=sharing)

---

## 📊 Overview

This project uses a blend of finance theory and Python-based analysis to optimize and evaluate portfolios with various constraints. Using daily stock data from 2020 to 2024, we analyze eight carefully chosen stocks across diverse sectors and regions, aiming for balanced growth potential and risk exposure. Through mean-variance optimization, Fama-French 3-Factor analysis, and Sharpe Ratio maximization, this project demonstrates how data-driven strategies can lead to efficient and effective portfolio construction.

## 🧠 Key Features & Findings

1. **Efficient Frontier & Monte Carlo Simulations**  
   - Generated thousands of potential portfolios using Monte Carlo simulations, providing a visual representation of risk-return profiles. By plotting these against the Efficient Frontier, we can see the optimal balance between risk and return, guiding our selection of a minimum-risk and a maximum-Sharpe portfolio.
   
2. **Optimal Portfolio Selection**  
   - Through risk minimization and Sharpe Ratio maximization, two portfolios—unconstrained (fully optimized) and constrained (industry-weighted)—were developed. Key metrics such as Jensen's Alpha, Treynor’s Ratio, Information Ratio, and Appraisal Ratio reveal that flexibility significantly impacts performance.

3. **Fama-French 3-Factor Model Analysis**  
   - Applying this model to the constrained portfolio, we gain insights into the portfolio’s exposure to market, size, and value factors. This analysis showed a slight preference for growth stocks over value stocks, with a beta indicating moderate market sensitivity—a valuable insight for positioning in varying economic conditions.

4. **Capital Market Line (CML)**  
   - By plotting the CML, we visually analyze the risk-return trade-off relative to the market and showcase where our portfolios stand against risk-free alternatives. The steeper the CML slope, the higher the risk-adjusted returns of the tangency portfolio, making it a core benchmark for portfolio comparison.

## 🔍 Unique Insights

- **Cross-Industry Diversification**: With holdings ranging from high-tech (NVIDIA) to pharmaceuticals (Novo Nordisk), we capture not only growth but also stability, aligning well with diverse market cycles. Stocks like NVIDIA and WOLF introduce volatility and high growth potential, while JNJ and HSBC act as stabilizers in risk-off environments.
  
- **Factor Analysis Revelation**: The Fama-French loadings reveal a lean toward small-cap and growth characteristics, emphasizing potential for high returns in bull markets but also susceptibility to downturns. This blend reflects a high-risk, high-reward strategy that seeks to capture market upsides while carefully managing downsides.

- **Dynamic Allocation Strategy**: The portfolio analysis points to an ideal mix of low and moderate correlations, enabling balanced risk-taking. Using pairs like Johnson & Johnson with WOLF enables us to harness growth while reducing vulnerability to single-sector downturns, a crucial advantage in uncertain economic climates.

---

## 🔗 Why Explore the Code?

This project bridges theoretical finance with practical Python implementation. You’ll find value in how each code segment builds upon the previous to refine portfolio performance, aligning well with modern investment strategies. Take a closer look at how Monte Carlo simulations, Fama-French analysis, and risk-adjusted metrics like Sharpe Ratio culminate in a real-world, optimized portfolio. 

[Explore and Run the Project on Google Colab](https://colab.research.google.com/drive/1PStobRGyd9dHu7n9nJjLgB7Ra4CKLu4e?usp=sharing)

Jump in to see how finance theory becomes actionable strategy in this portfolio analysis journey!
