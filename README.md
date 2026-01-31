# AIAI Customer Segmentation

Project for the Data Mining course, Masters in Data Science and Advanced Analytics, NOVA IMS

---

## Project Authors

Pedro Santos – 20250399 – [20250399@novaims.unl.pt](mailto:20250399@novaims.unl.pt)  
Miguel Correia – 20250381 – [20250381@novaims.unl.pt](mailto:20250381@novaims.unl.pt)  
Pedro Fernandes – 20250418 – [20250418@novaims.unl.pt](mailto:20250418@novaims.unl.pt)  
Tiago Duarte – 20250360 – [20250360@novaims.unl.pt](mailto:20250360@novaims.unl.pt)

---

## Project Overview

Amazing International Airlines Inc. (AIAI) operates a loyalty program with detailed member profiles and monthly flight activity.  
The objective of this project is to build clear, interpretable customer segments that support marketing prioritization, retention actions, and service personalization.

---

## Project Goals

1. **Customer-level dataset** – Combine membership data with aggregated flight activity and create segmentation-ready features.
2. **Segmentation modelling** – Build behavioural and value-oriented segmentations and compare clustering approaches.
3. **Validation and profiling** – Select stable segment structures and profile them with business-friendly descriptions.
4. **Extensions** – Add geo-spatial context, fuzzy membership (soft segmentation), and impact-oriented scenario modelling.
5. **Stakeholder communication** – Produce a concise business briefing with recommended actions and KPIs.

---

## Usage

- Run the notebooks to reproduce the full workflow from data preparation to final segments.
- Use the resulting segment profiles to support targeting, retention strategies, and loyalty program optimization.

---

## Outcome

A final segmentation that combines behavioural and value signals, resulting in four business-facing customer segments:

- **Established Active Core**  
- **Emerging High Growth**  
- **Seasonal Solo Travelers**  
- **At Risk Low Engagement**

---

## Notebooks

Our main notebook is **Group4_Clustering_Code.ipynb**, which contains the segmentation workflow and consolidates the final segments. It relies on the prepared dataset and engineered features built in the EDA notebook.

- **Group4_EDA_Code.ipynb** – data audit, cleaning decisions, merge strategy, customer-level aggregation, feature engineering  
- **Group4_Clustering_Code.ipynb** – clustering experiments, validation, segment selection, segment profiling and interpretation  
- **BonusOption4- Geo-Spatial Insights.ipynb** – geographic concentration analysis and route or hub context to assess location effects  
- **BonusOption2 - Fuzzy Clustering Implementation.ipynb** – fuzzy clustering with membership degree analysis to capture overlap and confidence  
- **BonusOption1- Financial Impact Modeling.ipynb** – scenario-based impact modelling to help prioritize segment initiatives  

---

## Reports

- **Group4_EDA_Report.pdf**  
- **Group4_Clustering_Report.pdf**  
- **BonusOption6 - Business Briefing.pdf**  
- **Financial Impact Modeling.pdf**  
- **BonusOption2 - Fuzzy Clustering.pdf**

---

## Setup

### Create environment
```bash
conda env create -f environment.yml
```

## Activate Environment
```bash
conda activate AIAI
```

## Create kernel (necessary for jupyter on browser)
```bash
python -m ipykernel install --user --name AIAI --display-name "Python (AIAI)"
```

## Run

Open notebooks in Jupyter or VSCode and select `AIAI` kernel.

## Deactivate
```bash
conda deactivate
```
