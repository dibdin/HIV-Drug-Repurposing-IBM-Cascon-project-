# HIV Drug Repurposing via Machine Learning  
**IBM Cascon × Evoke 2021 Conference Project**

Applied ML to repurpose FDA-approved drugs for HIV treatment, enabling scalable local production in Africa.

Link to presentation at IBM's Cascon X Evoke 2021 Conference: https://www.youtube.com/watch?v=Tb_laDsw29A

---

## Repository Structure  

HIV-Drug-Repurposing-IBM-Cascon-project/
├── data/                # Input datasets (drug molecules, assay results)
├── notebooks/           # Jupyter notebooks for EDA, model exploration
├── src/                 # Python scripts: preprocessing, model training, evaluation
├── results/             # Output: prediction tables, visualizations
├── requirements.txt     # Python dependencies
└── README.md            # Project overview (this file)

---

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/dibdin/HIV-Drug-Repurposing-IBM-Cascon-project-.git
   cd HIV-Drug-Repurposing-IBM-Cascon-project-
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Explore the analysis:
   ```bash
   jupyter notebook notebooks/HIV_Drug_Repurposing_EDA.ipynb
   ```

4. Run the full pipeline:
   ```bash
   python src/run_pipeline.py --config config.yaml
   ```

---

## Highlights & Outcomes

- Leveraged ML (e.g., random forest, logistic regression) to screen FDA-approved compounds for HIV treatment.
- Developed pipeline scalable for local implementation in African settings.
- Delivered a working prototype presented at IBM Cascon × Evoke Conference (2021).

(Include images of top predictions or results from results/ here)

---

## Key Learnings

- Demonstrated ML can accelerate drug repurposing using existing pharmaceutical compounds.
- Showcased potential for remote, resource-limited deployment of computational health tools.
- Designed a modular and reproducible pipeline for future adaptation in drug discovery contexts.

---

## About the Author

Diba Dindoust — Stanford University student focusing on ML applications in health, including neonatal outcomes and global health equity.

- GitHub
- LinkedIn
- Email

---

## Acknowledgments

This project was presented at the IBM Cascon × Evoke conference (2021).
