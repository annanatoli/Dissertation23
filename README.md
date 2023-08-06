# Dissertation23

## Financial Valuation Forecasting using Gradient Boosting Machines and FinBERT:

### Overview:
In today's data-driven era, financial markets are leveraging machine learning (ML) techniques to augment traditional financial valuation methods. This repository dives deep into research demonstrating the power of supervised machine learning (specifically GBMs) in predicting financial valuation metrics such as EV/EBITDA. Leveraging diversified data sources, ranging from company filings to media announcements, this research exploits quantitative and qualitative metrics. To integrate sentiment and classification features into financial forecasting models it has been utilised FinBERT, a pre-trained Natural Language Processing (NLP) model.


#### Key Highlights:
- **Approach**: The research leverages Gradient Boosting Machines, particularly the LightGBM architecture, for forward financial valuation metric prediction.
- **Data Sources**: The data has been extracted from EIKON Workspace API, a platform provided by Refinitiv.
- **NLP Integration**: The pre-trained Natural Language Processing model, FinBERT, is utilised to weave in sentiment and classification features, providing a richer financial forecasting perspective.
- **Special Focus**: The research highlights the forecasting efficiency of GBMs, demonstrated across both the broader market— represented by the S&P 500—and individual firms whose valuation is inherently complex, such as the London Stock Exchange Group (LSEG). 
- **Findings**: The results emphasise the potent forecasting abilities of GBMs, and aer signicant to provide future-oriented financial valuable analysis for financial institutions and decision-makers. 

#### Repository Structure (Following the Microsoft Team Data Science Process):

1. **Data**:
    - Raw
    - Processed

2. **Code**:
    - 1 Data mining
    - 2 Data Exploration
    - 3 Merging 1 ( macroeconomic and financial features)
    - 4 Guidance text - 4a for LSEG
    - 5 Merging 2 and wrangling - 5a for LSEG
    - 6 Modelling - 6a for LSEG

4. **Documents**:
    - Final Paper

#### Utility:
This research is poised at the intersection of machine learning and finance, highlighting the capability of ML techniques like Gradient Boosting Machines to craft precise, futuristic financial analyses. It serves as a repository of knowledge for financial practitioners, institutions, and decision-makers.

---

#### Getting Started:

1. **Prerequisites**: Refer to `requirements.txt` to set up the necessary environment.
2. **Data**: Access raw and refined datasets in the `data` directory.
3. **Training**: The `code` directory houses all notebooks pertinent to data pre-processing model training.

Should you have questions or wish to contribute, kindly raise an issue or forward a pull request.
