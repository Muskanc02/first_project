# Project overview
The dataset displayed country/region/area data regarding unemployment, tourism, crime rates, and R&D globally.

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

# Slide presentation

- https://docs.google.com/presentation/d/1YlZzdETY-emjRir9cUDgWQ5Juu6fl1RqSZXtkhXkVtI/edit?usp=sharing

# Questions 

## We are looking to test the following hypothesis:

- Higher R&D investment and tourism contribute to economic growth, leading to lower unemployment and crime rates.
- Higher rate of unemployment lead to higher number of crimes.
- Countries with strong labor markets (low unemployment) attract more tourists and experience lower crime rates.

# Dataset 
The team picked four different datasets csv files from the UN website (https://data.un.org/): unemployment & labor force, crime, tourism, and research & development

## Main dataset issues

- Column names were not all in the same format.
- Column values had multiple incorrect formats and null values.
- Headers for the columns were wrong.
- Irrelevant columns.

## Solutions for the dataset issues
- Cleaned column headers by replacing the spaces for "_" and making the letters in lower case format.
- Filled null values with "0" or "N/A" when necessary.
- Removed rows to show the correct column headers.
- Removed any irrelevant columns.

# Conclussions
- The initial hypothesis were supported by the analysis.
