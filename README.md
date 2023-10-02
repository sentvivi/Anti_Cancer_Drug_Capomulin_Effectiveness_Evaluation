# Anti_Cancer_Drug_Capomulin_Effectiveness_Evaluation
Pymaceuticals, Inc. is a company that makes medicines to fight cancer. They're doing a study to see which medicines work best against a type of skin cancer called squamous cell carcinoma (SCC). I'm a data analyst, and I'm helping the company analyze the data from the study.

Prepare the Data
*  Run the provided package dependency and data imports
*  Merge the "mouse_metadata" and "study_results" DataFrames into a single DataFrame
*  Display the number of unique mouse IDs and check for duplicates
*  Create a new DataFrame with duplicate data removed

Generate Summary Statistics
*  Create a DataFrame of summary statistics for tumor volume, including mean, median, variance, standard deviation, and SEM,       for each drug regimen

Create Bar Charts and Pie Charts
Bar Charts
*  Generate two identical bar charts to show the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout       the study
    *  Create the first bar chart using Pandas "DataFrame.plot()" method
    *  Create the second bar chart using Matplotlib's "pyplot" methods
Pie Charts
*  Generate two identical pie charts to show the distribution of female versus male mice in the study
    *  Create the first pie chart using Pandas "DataFrame.plot()" method
    *  Create the second pie chart using Matplotlib's "pyplot" methods
 
Calculate Quartiles, Find Outliers, and Create a Box Plot
*  Calculate the final tumor volume of each mouse for the most promising treatment regimens: Capomulin, Ramicane, Infubinol,     and Ceftamin
*  Calculate quartiles, IQR, and identify potential outliers
*  Create a box plot using Matplotlib to visualize the distribution of final tumor volumes, highlighting potential outliers
