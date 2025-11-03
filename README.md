# Deforestation and Biodiversity in U.S. Forests (2019–2021)

This project investigates whether forest loss across U.S. states is associated with changes in biodiversity indicators such as species richness and threatened/endangered species counts.

## 📊 Key Findings
- **Plot_count** (a proxy for fragmentation) was the strongest predictor of deforestation.
- **Species richness** and **TE species counts** were weak predictors in the short term.
- **Temperature** showed emerging correlation with threatened species (R² ≈ 0.21).

## 📁 Repository Structure
- `data/` — input datasets (from USFS and NPS)
- `notebooks/` — analysis and modeling in Jupyter Notebook
- `figures/` — generated visualizations
- `README.md` — project overview
- `requirements.txt` — Python dependencies

## Project Files
- [Notebooks](notebooks/)
- [Figures](figures/)
[View Biodiversity Map](figures/biodiversity_map.html)



## ⚙️ Dependencies
Install required libraries with:
```bash
pip install -r requirements.txt
