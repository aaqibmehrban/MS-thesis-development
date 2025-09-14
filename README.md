# Public Transport Carbon Emissions Analysis (Helsinki Region, 2017–2023)

This repository contains Jupyter Notebooks analyzing the **change in carbon emissions from public transport trips** in the Helsinki region between **2017** and **2023**.  
The analysis includes both multi-destination trips and focused case studies on **Helsinki city center, Leppävaara, and Pasila**.

---

## Repository Structure

### Emission Calculation Notebooks
These notebooks calculate estimated carbon emissions for trips in **2017** and **2023**:

- **2017**
  - `2017_carbon_emissions-multi.ipynb` → Multiple origins to multiple destinations  
  - `2017_carbon_emissions_helsinki.ipynb` → Trips to Helsinki city center  
  - `2017_carbon_emissions_leppavara.ipynb` → Trips to Leppävaara  
  - `2017_carbon_emissions_pasilaa.ipynb` → Trips to Pasila  

- **2023**
  - `2023_carbon_emissions-multi.ipynb` → Multiple origins to multiple destinations  
  - `2023_carbon_emissions_helsinki.ipynb` → Trips to Helsinki city center  
  - `2023_carbon_emissions_leppavara.ipynb` → Trips to Leppävaara  
  - `2023_carbon_emissions_pasilaa.ipynb` → Trips to Pasila  

### Emission Change Mapping Notebooks
These notebooks generate **spatial maps** showing the difference in emissions between 2017 and 2023:

- `helsinki_emission_change_maps.ipynb` → Change maps for Helsinki city center  
- `leppa_emission_change_maps.ipynb` → Change maps for Leppävaara  
- `pasila_emission_change_maps.ipynb` → Change maps for Pasila  
- `multidesti_emission_change_maps.ipynb` → Change maps for multiple destinations  

---

## Objective

The aim of this repository is to:

1. Calculate and compare public transport carbon emissions for **2017** and **2023**.  
2. Identify spatial differences across major hubs in the Helsinki region.  
3. Visualize how emissions have shifted through interactive and static maps.  

This work supports the thesis:  
**“Visualizing the Change in Carbon Emissions from Public Transport in the Helsinki Region: A Comparative Analysis Between 2017 and 2023.”**

---

## Setup

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-name>


2. Create the conda environment using the provided `environment.yaml`:

   ```bash
   conda env create -f environment.yaml
   conda activate carbon-emissions
   ```

3. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

---

## Usage

* Open any `2017_*.ipynb` or `2023_*.ipynb` notebook to compute emissions.
* Open the `*_emission_change_maps.ipynb` notebooks to visualize the change between 2017 and 2023.

---

## License

This repository is for academic research purposes. Please cite appropriately if you use or build upon this work.

