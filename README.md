# FinBERT and FinGPT Analysis Project

## Project Overview
This project implements and compares financial text analysis using FinBERT and FinGPT models with LSTM modifications. The analysis is performed on a StockEmotions dataset to evaluate financial sentiment and patterns.

## Repository Structure
```
.
├── tweet dataset/            # Dataset containing StockEmotions tweets for analysis
├── FinBERT_Modified_LSTM.ipynb       # Notebook implementing FinBERT with LSTM modifications
├── FinBERT_FinGPT_Modified_LSTM.ipynb # Notebook combining FinBERT and FinGPT with LSTM
├── FinBERT Results.zip              # Results from FinBERT analysis
└── FinGPT + FinBERT Results.zip     # Combined results from both models
```

## Notebooks
1. **FinBERT_Modified_LSTM.ipynb**
   - Implements FinBERT model with LSTM modifications
   - Analyzes financial tweets
   - Outputs results to FinBERT Results.zip

2. **FinBERT_FinGPT_Modified_LSTM.ipynb**
   - Combines FinBERT and FinGPT approaches
   - Includes LSTM modifications
   - Outputs results to FinGPT + FinBERT Results.zip

## Dataset
The `tweet dataset` contains the financial tweets used for analysis. This data serves as input for both notebooks.

## Results
Results are stored in two zip files:
- `FinBERT Results.zip`: Contains outputs from the FinBERT LSTM analysis
- `FinGPT + FinBERT Results.zip`: Contains outputs from the combined model analysis

## Usage
1. Ensure you have all required dependencies installed
2. Extract the tweet dataset
3. Run either notebook:
   - Use `FinBERT_Modified_LSTM.ipynb` for FinBERT analysis
   - Use `FinBERT_FinGPT_Modified_LSTM.ipynb` for combined model analysis
4. Results will be generated in the respective zip files
