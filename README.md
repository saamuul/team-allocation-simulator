# Team Allocation Simulator  

## Overview  
The **Team Allocation Simulator** automatically forms balanced and diverse student teams.  

It assigns students into teams of five (or customizable team sizes) while ensuring fairness across:  
- **School Affiliation** – prevents majority from the same school  
- **Gender** – promotes gender diversity  
- **CGPA** – balances academic performance  

The program reads student records from `records.csv` and outputs a new file with assigned team numbers.

## Software Requirements
- Python 3.8+
- Jupyter Notebook

## Installation  

1. Clone the repository
   ```bash
   git clone https://github.com/saamuul/team-allocation-simulator.git
   cd team-allocation-simulator
   
2. Create a Virtual Environment
   ```bash
    python -m venv venv
    source venv/bin/activate   # Mac/Linux
    venv\Scripts\activate      # Windows

3. Install Dependencies
      ```bash
    pip install -r requirements.txt

## Running the Program
1. Open the Jupyter Notebook
   ```bash
    jupyter notebook FCE1_Team4.ipynb

2. Run All Cells in Order
- The notebook will read data from records.csv.
- Teams are generated based on diversity criteria (School, Gender, CGPA).
- Two output csv files will be created automatically. (team-allocated-output.csv & assignment_statistics.csv)
