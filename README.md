# Group 5 CSC 4850 Project

## Description

This repository contains the model testing python notebook used to generate data found in the Group 5 Project Report.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- Git
- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the Repository**

   First, clone the repository to your local machine using Git.

   ```bash
   git clone https://github.com/marendale/group_5_csc_4850.git
   ```
   
   Navigate to the repository directory.

   ```bash
   cd group_5_csc_4850
   ```
   
2. **Set Up Your Environment** (Optional)
   
   It's recommended to create a Python virtual environment and install the dependencies.
   
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```
   
3. **Launch Jupyter Notebook**
   
   Start Jupyter Notebook or JupyterLab from the command line.

   ```bash
   jupyter notebook
   ```

   Or for JupyterLab:

   ```bash
   jupyter lab
   ```

4. **Open the Notebook**
   
   In the Jupyter interface, navigate to the directory where the repository was cloned and open the `.ipynb` file.

### Configuring the Notebook

1. **Set the Data Path**

   In the notebook, find the line where the path variable is set. It will look something like this:

   ```python
   path = '/path_to_data_InSummary/Drug_{}/{}/drug_embedding.csv'
   ```

   Replace the `path_to_data_InSummary` with the appropriate values for your data.

2. **Run the Notebook**

   With the path variable set, you can now run all the cells in the notebook. In Jupyter Notebook, you can do this by clicking on `Kernel` > `Restart & Run All`. In JupyterLab, the option might be slightly different but will be found under the Run menu.
   
   

   

