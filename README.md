## Project Title: Exam Grade Analysis

**Description:**

This project aims to analyze a fabricated dataset consisting of exam grades for a class. The dataset includes student IDs, exam grades, and a label feature representing the sum of grades. The project involves several stages of preprocessing, normalization, and correlation analysis.

**File Structure:**

- `main.py`: Contains the Python code for the project.
- `Sample_Data.xlsx`: Excel file containing the fabricated dataset.
- `README.md`: Markdown file containing project information and instructions.

**Project Code Explanation:**

The `main.py` file consists of Python functions to perform the following tasks:

1. **Preprocessing:**
   - Filling missing data with the mode of the target feature.
   - Identifying and managing outliers using the IQR method.
   
2. **Normalization:**
   - Shifting the mean of each feature to zero and normalizing the standard deviation to one.

3. **Correlation Matrix:**
   - Calculating the correlation between all features of the dataset.
   - Selecting features with the highest correlation with the label.
   - Removing features with lower correlation iteratively until two features remain.

**Instructions for Running the Code:**

1. Ensure Python 3.x is installed on your system.
2. Install necessary libraries: `numpy`, `pandas`.
3. Place the dataset file `Sample_Data.xlsx` in the same directory as `main.py`.
4. Run the `main.py` script using the command: `python main.py`.

**Sample Data:**

The dataset (`Sample_Data.xlsx`) contains exam grades for a class, with student IDs and a label feature representing the sum of grades.

**Output:**

The script generates processed data along with correlation matrices and the final dataset after feature selection.

**References:**

- `numpy`: https://numpy.org/
- `pandas`: https://pandas.pydata.org/

**Contributors:**

- Nima Ahmadi


**Contact:**

For any inquiries, please contact Nima87760@gmail.com.

