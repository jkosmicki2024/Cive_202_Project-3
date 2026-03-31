# Cive_202_Project-3

## Project Summary

This project was completed for CIVE 202 on behalf of the Federal Highway Administration (FHWA). The goal was to organize, visualize, and analyze two transportation datasets — the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) — using Python. The project also includes an Intelligent Driver Model (IDM) simulation study to model car-following behavior.

## Files in this Repository

| File | Description |
|------|-------------|
| `Project3_Final_Kosmicki.ipynb` | Jupyter Notebook containing all Python code for NHTS visualizations, NGSIM time-series plots, and the IDM simulation |
| `NHTS.csv` | National Household Travel Survey dataset|
| `NGSIM.csv` | Next Generation Simulation dataset|
| `Project_3_Report_Kosmicki.docx` | Technical report with Introduction, Methods, Results & Discussion, and References |
| `Project3_SOW_Kosmicki.docx` | Scope of Work describing project objectives, variable selection, tasks, and deliverables |
| `Project3_AnnotatedCode.docx` | Annotated code reference table explaining each line of Python code |
| `Project3_Timesheet_Kosmicki.xlsx` | Engineering timesheet documenting hours spent on each task |
| `Project3_GanttChart_Kosmicki.*` | Gantt chart of project activities and schedule |
| `README.md` | This file |

## How to Run the Code
### Steps
1. Clone or download this repository to your local machine
2. Make sure `NHTS.csv` and `NGSIM.csv` are in the same folder as the notebook
3. Open `Project3_Final_Kosmicki.ipynb` in Jupyter Notebook
4. Run cells sequentially from top to bottom — the notebook is broken into labeled sections:
   - **Section 1**: Package imports and global plot settings
   - **Section 2**: Load and inspect both datasets
   - **Section 3**: NHTS visualizations (bar chart, histogram, boxplot, fuel type chart)
   - **Section 4**: NGSIM time-series plots (speed, acceleration, position, gap distance, 2x2 dashboard)
   - **Section 5**: IDM simulation (function definition, Euler time-stepping, comparison plots)

### User Guide for Sequential Prompts
This notebook does not require any user input prompts. All variables, trajectory selections, and IDM parameters are set directly in the code cells. To change which trajectory pair is analyzed, modify the `trajectory_number` variable in Sections 4.3 and 5.3.

## Author
Jacob Kosmicki — CIVE 202, Spring 2026
