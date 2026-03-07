# Exploratory Data Analysis - Titanic & Train Datasets

## Overview
This repository contains comprehensive exploratory data analysis (EDA) of two datasets using Python data science libraries. The analyses systematically explore passenger datasets, examining patterns and relationships between various characteristics.

## Files
- **EDA-Titanic.ipynb** - Jupyter notebook containing complete analysis of the Titanic dataset
- **EDA-Train.ipynb** - Jupyter notebook containing complete analysis of the Train dataset

## Libraries Used
- **pandas** (v2.3.3) - Data manipulation and analysis
- **numpy** (v2.3.5) - Numerical computing
- **matplotlib** (v3.10.6) - Data visualization
- **seaborn** (v0.13.2) - Statistical data visualization

---

# EDA - Titanic Dataset

## Dataset Information
The Titanic dataset contains **891 passenger records** with **15 columns** including:

### Columns:
- **survived** - Target variable (0 = Did not survive, 1 = Survived)
- **pclass** - Passenger class (1st, 2nd, 3rd)
- **sex** - Gender of passenger
- **age** - Age of passenger
- **sibsp** - Number of siblings/spouses aboard
- **parch** - Number of parents/children aboard
- **fare** - Ticket fare
- **embarked** - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- **class** - Passenger class category
- **who** - Classification (man, woman, child)
- **adult_male** - Whether passenger is an adult male
- **deck** - Deck location
- **embark_town** - Town of embarkation
- **alive** - Survival status (yes/no)
- **alone** - Whether passenger was traveling alone

## Key Findings

### Survival Rates by Passenger Class
| Class | Survival Rate |
|-------|---------------|
| First Class | 62.96% |
| Second Class | 47.28% |
| Third Class | 24.24% |

**Insight**: Higher passenger class significantly increased chances of survival.

### Survival Rates by Gender
| Gender | Survival Rate |
|--------|---------------|
| Female | 74.20% |
| Male | 18.89% |

**Insight**: Females had substantially higher survival rates, following the "women and children first" evacuation protocol.

### Overall Statistics
- **Total Passengers**: 891
- **Survivors**: 342 (38.38%)
- **Non-survivors**: 549 (61.62%)
- **Missing Values**:
  - Age: 177 missing values
  - Deck: 688 missing values
  - Embarked: 2 missing values

## Analysis Sections Covered
1. Data loading and library imports
2. Dataset overview (head, tail, info, describe)
3. Data types and structure examination
4. Univariate analysis (value counts by class and gender)
5. Survival rate calculations
6. Data aggregation and groupby operations
7. Statistical summaries

---

# EDA - Train Dataset

## Dataset Information
The Train dataset contains comprehensive train passenger records with multiple features for analysis.

### Key Features:
- Passenger demographics (age, gender, class)
- Journey details (departure, arrival, destination)
- Ticket information (fare, class, seat)
- Additional metadata for comprehensive analysis

## Analysis Sections Covered
1. Data loading and library imports
2. Dataset overview (head, tail, info, describe)
3. Data types and structure examination
4. Univariate analysis (value counts and distributions)
5. Feature relationships and correlations
6. Data aggregation and groupby operations
7. Statistical summaries and insights
8. Visualization of key patterns and trends

## Key Analysis Areas
- Passenger demographics distribution
- Journey patterns and trends
- Feature correlations and relationships
- Missing data analysis
- Univariate and multivariate insights

---

## How to Use
1. Clone the repository
2. Install required libraries: `pip install pandas numpy matplotlib seaborn`
3. Open `EDA-Titanic.ipynb` or `EDA-Train.ipynb` in Jupyter Notebook
4. Run all cells to view the analysis and visualizations