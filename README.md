# Project overview
This project explores the relationship between economic growth, unemployment, tourism, crime, and research & development (R&D) investment using global datasets from the United Nations. By leveraging data wrangling, cleaning, and analytics techniques, we aimed to uncover potential correlations and causations between these socioeconomic factors. The study focuses on understanding how labor market conditions, tourism activity, and R&D expenditure influence crime rates and GDP across various regions and countries.

# Installation

1. **Clone the repository**:

```bash
git clone https://github.com/YourUsername/repository_name.git
```

2. **Install UV**

If you're a MacOS/Linux user type:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

If you're a Windows user open an Anaconda Powershell Prompt and type :

```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

3. **Create an environment**

```bash
uv venv 
```

3. **Activate the environment**

If you're a MacOS/Linux user type (if you're using a bash shell):

```bash
source ./venv/bin/activate
```

If you're a MacOS/Linux user type (if you're using a csh/tcsh shell):

```bash
source ./venv/bin/activate.csh
```

If you're a Windows user type:

```bash
.\venv\Scripts\activate
```

4. **Install dependencies**:

```bash
uv pip install -r requirements.txt
```

## Slide presentation

- https://docs.google.com/presentation/d/1YlZzdETY-emjRir9cUDgWQ5Juu6fl1RqSZXtkhXkVtI/edit?usp=sharing

## Research Questions & Hypotheses

1.The project aimed to answer the following key research questions:

2.Does higher investment in R&D and an increase in tourism contribute to economic growth, thereby reducing unemployment and crime rates?

3.Is there a direct correlation between high unemployment rates and increased crime levels?

4.How does the labor market interact with crime trends over time?


## Hypothesis :

- H1.Higher R&D investment and tourism contribute to economic growth, leading to lower unemployment and crime rates.
- H2.Higher rate of unemployment lead to higher number of crimes.

# Dataset 
The dataset was compiled using multiple CSV files from the United Nations data repository (UN Data):

Unemployment & Labor Force: Provides country-wise data on employment rates, labor force participation, and unemployment.

Crime Data: Covers reported crime incidents per country, categorized by type (violent, property-related, etc.).

Tourism Statistics: Includes data on international arrivals, tourism revenue, and its economic contribution.

Research & Development (R&D) Expenditure: Details investment in innovation and technological development.

## Dataset Challenges and Cleaning Process

- During data preprocessing, we encountered the following issues:
- Inconsistent column formats: Different naming conventions across datasets.
- Incorrect and missing values: Presence of null or improperly formatted values.
- Incorrect headers: Some datasets had misaligned column headers.
- Irrelevant columns: Some columns were unnecessary for analysis.

## Solutions implemented
- Cleaned column headers by replacing the spaces for "_" and making the letters in lower case format.
- Handled missing values by filling them with "0" or "N/A" where appropriate.
- Removed rows to show the correct column headers.
- Dropped irrelevant columns to streamline analysis.
- Standardized column headers (replacing spaces with underscores and converting to lowercase).
- Corrected misaligned headers by manually adjusting column placements.


## Methodology

Our data analysis process involved:
- Data Wrangling & Cleaning: Preprocessed datasets to ensure consistency and accuracy.
- Exploratory Data Analysis (EDA): Used statistical analysis and visualizations to explore trends.
- Correlation Analysis: Measured relationships between GDP, unemployment, crime, tourism, and R&D investment.
- Hypothesis formation: Based on the data analysis proved the hypothesis as right or wrong.
- Interpretation & Insights: Derived conclusions based on observed trends and statistical significance.

## Key Findings & Conclusions
- Tourism and GDP Growth: Countries with higher tourism revenues showed stronger economic stability and lower unemployment rates.
- Unemployment and Crime: A clear correlation was observed between rising unemployment rates and increased crime incidents, particularly in economically unstable regions.
- R&D and Economic Growth: Nations with higher R&D investments exhibited better economic resilience and lower crime rates.
- Regional Differences: The relationship between these factors varied significantly across continents due to policy differences, governance quality, and social conditions.

## Final Conclusion:

Our analysis largely supported the initial hypotheses. While economic growth driven by tourism and R&D investment was associated with lower unemployment and crime rates, the extent of these relationships varied by country and region. The findings highlight the importance of policy interventions that promote economic stability and labor market improvements to curb crime rates globally.



## Future Work
- Expanding the dataset to include more years for a longitudinal analysis.
- Investigating additional socioeconomic factors such as education levels and healthcare access.
