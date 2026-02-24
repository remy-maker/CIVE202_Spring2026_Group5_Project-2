# CIVE202_Spring2026_Group5_Project-2

## Project Overview 

This project was completed for the course Civil Engineering Analysis II at the University of Nebraska-Lincoln. 
The objective of the project is to migrate an existing concrete mix design model from an Excel-based workflow to a Python-based system. Our client for this project is NDOT (Nebraska Department of Transportation). They would like us to replicate and automate the logic of the "Mix Design" worksheet so that the user can enter material properties and automatically generate the weight chart for one cubic yard of concrete.

The project involves:
- Translation of the Excel logic into Python code. All major calculations are clearly defined and replicated in Python.
- Implement sequential user inputs.The inputs are collected in logical order and mirror the Excel worksheet.
- Generated final mix design. Python program produces a clearly formatted weight chart for 1 cubic yard of concrete.

The final output includes a scope of work (SOW), a formal document defining the tasks our group unertook to automate the NDOT Model. A gantt chart providing a visual project schedule. For python code, a jupyter notebook documenting the automation logic, the sequential user prompts, and the four mix runs. Fully operational and executable without errors. As well as an annotated code document (ACD) explaning said pyhton code and equations. Lastly, a written techinical report, including background on NDOT project, methods, results, and refrences. 

---

## Respository Structure 
The respository is organized as follows:

-`mix-design-submittal.xlsx/`
  Excel workbook including calculation sheets and formulas used to determine mix proportions based on the user inputs for the requirements and quantities. 
  
-`CIVE 202_Spring 2026_Group 5_Project #2.ipynb/`
 Includes all Python scripts used for calculations. Translated and organized similarly to the Excel workbook. 

-`CIVE 202_Spring 2026_Group 5_Project #2_ACD.pdf/`
 Includes a line-by-line explanation of code. With specific explanation of how the Excel formulas were converted into Python functions.

-`CIVE 202_Spring 2026_Group 5_Project #2_Gantt Chart/`
 Contains Gantt Chart results. 

-`CIVE 202_Spring 2026_Group 5_Project #2_SOW.pdf/`
 Contains Scope of Work outlining project's goals and defines the tasks to automate the NDOT model.

-`CIVE 202_Spring2026_Group_5_Project_#2_Written_Report.pdf/`
   Contains detailed report on the background of the NDOT project and objectives. Detailed explanations of methods used to convert excel function to python code. As well as results on the four chosen mix designs, highlighting diffences in results. And refrences to NDOT or other refrences used. 

-`READ.md`
 Documentation and user guide for this project.

 ---

 ## Software and Requirements 

 This project was developed using:

 -Python
 -Required Libraries:
   - numpy
   - pandas

</> 

## How to Run the Project (User Guide)

### Step 1: Review the Excel Workbook
1. Open `mix-design-submittal.xlsx`.
2. Navigate to the input section
3. Note the user input parameters and the formulas we need to convert into Python.

### Step 2: Run the Jupyter Notebook
1. Open `CIVE 202_Spring 2026_Group 5_Project #2.ipynb` in Jupyter Notebook.
2. Ensure the required Python libraries are installed.

</> Code

3. Run all cells sequentially from top to bottom.

The Notebook perfroms:
- Defines material properties
- Calculates volumes for each mix components
- Computes mix proportions
- Determines final concrete quantities

### Step 3: Review Final Results

Fully integrated mix design summary is displayed in the output cells at the end of the notebook. 

### Step 4: Scenario Testing and Refrences

Our group has used the code developed to run four different Scenarios containing different but realistic variables in cement, water-cement ratios, and aggreagate. The fully integrated mix design summaries of these four scenarios is listed at the bottom of the notebook. 

</>

## Methodology

To translate the Exel workbook into Python code we broke down the project into multiple procedures.

The following steps were performed:
1. Define the fundamental constants used throughout the mix design (Unit weight for water, cubic yard of concrete)
2. Define and calculate the first engineering function: Water Weight (Q). Using the parameters A-E to compute Q.
3. Define and calculate material volumes using specific gravity (For each parameter A-D, air volume, and water volume)
4. Define and calculate total aggregate volume (X), total fine aggregate weight (Y), total coarse aggregate weight (Z), total other aggregate weight (AA). 
5. Collect user inputs sequentially. In this section, we introduce user input so that we can collect all user inputs in the mix design sheet. These will be the parameters used in the weight and volume calculations. 
6. Run the completed mix design calculation
7. Report the final mix design results. We present the results in a clear, well organized weight chart for 1 cubic yard of concrete. This output mirrors the final section of the NDOT Mix Design worksheet where material weights are summarized for batching.
8. Verify the automated mix design workflow by running four different concrete mix scenarios. Each scenario should generate a complete weight chart for 1 cubic yard of concrete from user inputs. 

</> 

## Results Summary

The Python code computed the final concrete proportions based on the specified design requirements.

The calculated outputs include:
- Cement weight A (lb per cubic yard)
- Fly ash weight B (lb per cubic yard)
- Silica fume weight C (lb per cubic yard)
- Other SCM weight D (lb per cubic yard)
- Fine Aggregate (Y)
- Coarse Aggregate (Z)
- Other Aggregate (AA)
- Water Weight (Q)

The resulting mix satisfies all design requirements and parameters.

</>

## Conclusion

This project migrated an existing concrete mix design model from an Excel-based workflow to a Python-based system. 

The final calculated mix proportions satisfied NDOT'S standard specifications and provides the client with a readable summary of the inputs entered by the user and the output of the calculations. 

The use of computational tools enured mathematical accuracy, organization, and consistency for future users.  

</> 

Group 5
- Remy Balderas
- Madison Osborn
- Gavin Van Driel

Civil Engineering 202
University of Nebraska-Lincoln
Spring 2026
