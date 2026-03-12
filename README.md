# The Merchant Bank Paradox & The Knowledge Vacuum: WAMZ Regional Study

## Project Overview
This repository contains the empirical data and analysis for the study: **"The Merchant Bank Paradox and the 'Knowledge Vacuum': A Comparative Analysis of Structural Breaks in Private Sector Credit Across Anglophone West Africa."**

The research utilizes a **Chow Test for Structural Stability** to identify significant decoupling between banking liquidity and private sector credit in Nigeria, Ghana, Sierra Leone, and Liberia.

## Key Theoretical Contribution: The Knowledge Vacuum
We introduce the **Labor Precariousness Index (LPI)** to explain why West African banks have retreated into rent-seeking (Government Bonds). The study argues that high staff turnover and the use of precarious contract labor have created a "Knowledge Vacuum," hollowing out the institutional memory required to assess private sector credit risk.

## Empirical Results (Chow F-Statistics)
### **Figure 1: Structural Break Intensity (Chow Test Results)**
This bar chart illustrates the intensity of the "structural break" in private sector credit across the WAMZ quartet.
### **Figure 2: The Credit Growth Collapse (Pre- vs. Post-Break)**
This trend line demonstrates the sharp "decoupling" that triggered the structural breaks.
### **### **Empirical Visualizations**

#### **Figure 1: Chow Test Structural Break Intensity**
![F-Statistic Chart](https://raw.githubusercontent.com/bamideleadedeji/WAMZ-Merchant-Bank-Paradox/master/outputs/f_statistic_comparison.png)

#### **Figure 2: Private Sector Credit Growth Trends**
![Trends Chart](https://raw.githubusercontent.com/bamideleadedeji/WAMZ-Merchant-Bank-Paradox/master/outputs/credit_growth_trends.png)

- **The Steep Descent:** The visualization tracks the YoY Private Sector Credit growth before and after the 2024/2025 policy shifts.
- **The Divergence:** While banking sector profits may remain stable due to government bond yields, the private sector's access to credit has plummeted. 
- **Analytical Insight:** The steepness of the Sierra Leone slope compared to Nigeria illustrates the difference between an "Acute Fracture" and a "Total Rupture" in institutional DNA.

- **Sierra Leone (F=153.91):** Represents a total institutional rupture. The extreme value indicates that the relationship between banking liquidity and private lending has completely collapsed under high interest rate pressure.
- **Nigeria & Ghana:** Show significant acute and moderate fractures, proving that even the region's largest economies are not immune to the "Merchant Bank Paradox."
- **Threshold Analysis:** Values above the dashed line (10.0) indicate an "Acute Fracture," where traditional monetary policy transmission is severely compromised.
- **Sierra Leone:** 153.91 (Total Institutional Rupture)
- **Nigeria:** 12.62 (Acute Fracture)
- **Ghana:** 7.03 (Sustained Transition)
- **Liberia:** 6.59 (Risk-Averse Stagnation)

## Repository Structure
- `data/`: Aggregated time-series data from WAMZ Central Bank bulletins.
- `scripts/`: Jupyter Notebook (`.ipynb`) containing the Chow Test implementation.
- `requirements.txt`: Python dependencies required to replicate the analysis.

## How to Reproduce
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis in the `scripts/` folder.

## Author
**Adedeji Bamidele, M.Sc. (Economics), PGDS**
Financial Professional & Researcher
University of Ibadan Alumnus
