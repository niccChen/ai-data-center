# Optimize Carbon Footprint in AI Data Center

This project analyzes the carbon footprint of AWS EC2 infrastructure using a collection of datasets and a Jupyter Notebook. It provides insights into platform power profiles, hardware-specific emissions, region-based energy intensities, and more.

All datasets are stored in the [`data/`](./data) folder.  
The notebook [`Ai.Data Lab.ipynb`](./Ai.Data%20Lab.ipynb) contains preprocessing, visualization, and modeling steps.

---

## Folder Structure

```text
ai-data-center/
├── Ai.Data Lab.ipynb                # Jupyter notebook for analysis
└── data/
    ├── AWS EC2 Carbon Footprint Dataset(AWS Platforms Ratios).csv
    ├── AWS EC2 Carbon Footprint Dataset(...).csv
    ├── Cleaned_*.csv
    └── Final_Cleaned_*.csv
```

---

## Included Datasets (in `data/`)

| Filename (partial) | Description |
|--------------------|-------------|
| `AWS Platforms Ratios` | Power consumption ratios across EC2 instance types |
| `AWS Regions Mix Intensity` | Carbon intensity by geographic region |
| `Bare Metal Power Profiles` | Server-level power consumption data |
| `Carbon Footprint Estimator` | High-level emissions model |
| `Dell R740 LCA` | Lifecycle assessment for specific hardware |
| `GPU Specs & Ratios` | GPU-related energy usage metrics |
| `Scope 3 Ratios` | Indirect emissions (e.g., hardware manufacturing) |
| `Cleaned_*.csv` | Cleaned/preprocessed versions of the raw datasets |
| `Final_Cleaned_EC2_Instances.csv` | Fully prepared dataset for model training |

---

## Notebook Overview

**`Ai.Data Lab.ipynb`** includes:

- Data cleaning and standardization
- Carbon footprint normalization
- Exploratory visualizations
- Preparation for machine learning (scope 2/3 predictions)

---

## Tools & Environment

- Python 3.9+
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Optional: Scikit-learn (for model-ready datasets)

---

## License

MIT License © [niccChen](https://github.com/niccChen)

---

## Future Work

- Integrate Scope 2 + Scope 3 modeling pipeline
- Compare carbon efficiency across cloud vendors
- Automate notebook-to-HTML reporting


