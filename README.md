## Rmarkdown Data Analysis Projects

This repository contains a collection of data analysis projects and statistical explorations documented using RMarkdown. The projects focus on applying analytical techniques, visualizations, and statistical models to uncover insights and solve specific questions.

## Contents

### 1. Exploratory Data Analysis
- **Files**:  
  - `EDA.Rmd`  
  - `EDA.html`
- **Description**:  
  This project demonstrates the use of exploratory data analysis (EDA) techniques, including:
  - Data cleaning and preparation.
  - Summary statistics and visualizations.
  - Initial insights into data patterns.

### 2. Predictive Modeling Techniques
- **Files**:  
  - `predictive_modeling.Rmd`  
  - `predictive_modeling.html`
- **Description**:  
  This project applies various predictive modelling techniques, including:
  - Regression analysis.
  - Model evaluation metrics.
  - Comparative analysis of model performance.

## Requirements

- **R** (version 4.0 or higher)
- **RStudio** (for RMarkdown editing and rendering)
- Required R packages:
  - `ggplot2` for visualizations.
  - `dplyr` and `tidyr` for data manipulation.
  - `caret` for modeling.
  - `rmarkdown` for rendering.

## How to Use Chatbotapp

1. Clone the repository to your local machine:
   ```bash
   git clone <https://github.com/rahimunisa01/RMarkdown.git>
2. Switch to the Chatbot branch
   ```bash
   git checkout chatbotapp
3. Create and Set up your Environment
   ```bash
   python -m venv venv
   source venv/bin/activate
4. Install the packages using `requirements.txt`
   ```bash
   pip install -r chatbotapp/requirements.txt
5. Add your api key, hugging face token and database path(sqlite database path)
   ```bash
   OPENAI_API_KEY=your_openai_api_key_here
   HUGGINGFACE_API_TOKEN=your_huggingface_token_here
   DATABASE_PATH=path/to/your/database.db
6. To run the streamlit application
   ```bash
   streamlit run chatbotapp/app.py
