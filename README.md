# VAV1\_proteomics

This repository contains the code and environment setup used in the study:
**Beyond the G-Loop: VAV1 Degradation Unveils an RT-Loop Degron for CRBN Molecular Glues**

## Overview

This project analyzes global proteomics data to investigate the degradation of VAV1 and the identification of an RT-loop degron relevant to CRBN molecular glues. The analysis reproduces key visualizations from the manuscript, including volcano and bubble plots.

## Getting Started

### Prerequisites

* [Conda](https://docs.conda.io/en/latest/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Hanfeng-Lin/VAV1_proteomics.git
   cd VAV1_proteomics
   ```



2. Create and activate the conda environment:

   ```bash
   conda env create -f environment.yml
   conda activate proteomics
   ```



## Usage

Run the Jupyter notebook `DataAnalysis_Jurkat.ipynb` to reproduce the analysis:

```bash
jupyter notebook DataAnalysis_Jurkat.ipynb
```



Ensure that the file `Supplementary Data 3 - VAV1 global proteomics.pg_matrix.tsv` is placed in the appropriate directory as expected by the notebook.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For more information, please refer to the original publication associated with this code.

---
