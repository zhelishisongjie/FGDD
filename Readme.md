<div align="center">
  <img src="./figures/logo.png" alt="Logo" width="100%">
</div>


<div align="center">    

# FGDD: An Explainable Dataset of Facial Phenotype-Gene-Disease Association in Rare Genetic Diseases 

</div>

[![License](https://img.shields.io/badge/License-MIT-green)](https://opensource.org/licenses/MIT)
![Contributors](https://img.shields.io/badge/contributors-4-p)
![Version](https://img.shields.io/badge/version-1.0.0-blue) 
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![Dependency](https://img.shields.io/badge/dependency-PyTorch/Sklearn-orange)



## 🌐 Overview
**FGDD are available at [figshare](https://doi.org/10.6084/m9.figshare.28516604.v2)**

<div align="center">
  <img src="./figures/graph abstract.jpg" alt="Logo" width="100%">
</div>

## 🌟 Features

- We propose a new dataset, FGDD, for facial phenotype analysis of rare genetic diseases, which can be used not only for training explainable diagnostic models but also for in-depth analysis of the complex gene-disease-facial phenotype relationships and for mining more potential associations and patterns. 
- We have conducted extensive benchmarking on our dataset, and commonly used machine learning models can achieve up to 81% accuracy and provide clinical support. 
- We conducted an explainability analysis from both local and global perspectives, and the models trained on FGDD can provide explainable predictions that can be corroborated by relevant research, and enhance physicians’ confidence in the model results, which is particularly important in the medical field.


## 📁 File Description
- **`Baselines.ipynb`**: Contains the baseline model implementation and analysis. 
- **`Explainability analysis.ipynb`**: Includes code for explainability experiments and visualizations. 
- **`Construct KG.ipynb`**: Contains the code for constructing the Knowledge Graph (KG) from the dataset, including graph building.
- **`Search terms construction.ipynb`**: Includes the process of generating search terms used in the research. 
- **`requirements.txt`**: Lists all the dependencies required for the project.
- **`README.md`**: Documentation file for the repository. 
- **`LICENSE`**: MIT LICENSE. 


## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate       # For Linux/Mac
    env\Scripts\activate          # For Windows
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```


## 📜 License
MIT License  
The full agreement is available in the LICENSE file

## 📚 Citation
```bash
    
```
