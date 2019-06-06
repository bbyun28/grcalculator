## Instructions

### Formatting input files

Input files may be either comma- or tab-separated text files (.csv or .tsv). For more information about the input format, click "Import data file" and make a selection.


### Step 1: Load the data file containing cell counts for treated and control cells.

GRcalculator accepts comma-separated (.csv) or tab-separated (.tsv) input files. It can also accept files that use commas as decimal points.

The input files can come in one of two different formats, here called "Case A" and "Case C". Case A is the simplest format, with treated and control cell counts in different columns. Case C is more general and has treated and control cell counts in the same column. See below for exact descriptions of Case A and Case C.

Click **Load Example Case A** or **Load Example Case C** to the left to view a sample data file in the *Data Tables* tab.

### Step 2: Select the grouping variables.
 
The key variables selected define on which variables the GR values will be averaged before fitting of the dose-response curves. By default, all variables are pre-selected, but, for example, replicates can be averaged by deselecting the proper column header. To deselect a variable, click on it in the grouping variables box and then press the "delete" or "backspace" key. You may repeat this with as many variables as you like.

### Step 3: Select additional options and click "Analyze"

Additionally, the user may select **Advanced options** and choose **Cap GR values below 1** and/or **Force sigmoidal fit**. If **Cap GR values below 1** is selected, all calculated GR values that are greater than 1 will be set to 1. If **Force sigmoidal fit** is selected, the calculator will attempt to "force" a sigmoidal rather than a straight line fit, i.e. it will allow for sigmoidal fits with F-test p-values greater than .05.