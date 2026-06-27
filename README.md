#  NFHS-5 Public Health Analytics Dashboard-Samsung Innovation Campus Practice Project

An interactive **Python-based public health analytics dashboard** built using India's **National Family Health Survey (NFHS-5)** dataset. The project analyzes obesity, anaemia, hypertension, and blood sugar prevalence across Indian states through statistical analysis and geospatial visualization.

##  Features

-  Clean and preprocess NFHS-5 data
-  Perform Exploratory Data Analysis (EDA)
-  Analyze correlations between health indicators
-  Compare male vs. female hypertension rates
-  Interactive Folium choropleth map of India
-  State-wise health information using interactive popups

##  Project Workflow

### Phase 1: Data Preparation
- Load NFHS-5 dataset
- Clean missing values and convert numeric columns
- Create derived features (e.g., **Gender Obesity Gap**)

### Phase 2: Data Analysis
- Pearson correlation between childhood anaemia and adult obesity
- Top 10 states by hypertension (grouped bar chart)
- Female anaemia vs. female obesity scatter plot

### Phase 3: Geographic Visualization
- Interactive India map using Folium
- Choropleth showing obesity distribution
- State-wise health metrics displayed through popups

##  Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Folium
- Jupyter Notebook


##  Outputs

- Correlation Analysis
- Hypertension Comparison Chart
- Anaemia vs. Obesity Scatter Plot
- Interactive India Health Dashboard

##  Dataset

State-level **National Family Health Survey (NFHS-5)** data covering key public health indicators across India.
