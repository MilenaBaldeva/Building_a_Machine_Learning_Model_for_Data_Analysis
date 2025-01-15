<h1 align="center">Building a Machine Learning Model for Data Analysis</h1>

### Table of Contents
- [Dataset](#dataset)
- [Key Attributes](#key-attributes)
- [Steps Performed](#steps-performed)
- [Tools and Libraries](#tools-and-libraries)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

This project performs exploratory data analysis (EDA) and preprocessing on a dataset of used cars. The dataset provides a detailed overview of car attributes, making it suitable for tasks such as price prediction, market analysis, or customer segmentation.

### Dataset

The dataset used in this project was sourced from Kaggle using the kagglehub package. It includes attributes such as car make, model, year, mileage, fuel type, transmission, and price.

### Key Attributes
- **Car_Name**: Name of the car.
- **Make**: Manufacturer.
- **Model**: Car model.
- **Make_Year**: Year manufactured.
- **Mileage_Run**: Total mileage.
- **Price**: Selling price.
- **Fuel_Type**: Petrol/Diesel.
- **Body_Type**: SUV, sedan, etc.
- **Transmission**: Manual/Automatic.

### Steps Performed

**1. Dataset Loading**
- The dataset was downloaded and loaded using the kagglehub package.
- The file FINAL_SPINNY_900.csv was processed.

**2. Data Inspection**
- Checked for null values.
- Reviewed duplicate entries and removed them (62 duplicates were identified and removed).
- Inspected data types and converted them for optimization:
- Categorical columns: Emission, Transmission_Type, Body_Type, Fuel_Type.
- Numeric conversion for Price and No_of_Owners.
  
 **3. Data Preprocessing**
- Duplicates Removal: Duplicates were identified and removed.
- Data Cleaning:
Replaced ordinal string representations in No_of_Owners with numeric values.
Converted Price from a string format with commas to a numeric type.

- Type Conversion: Optimized data types for memory efficiency.

**4. Descriptive Statistics**
Generated summary statistics to understand the central tendency and variability of numerical features like Make_Year, Price, Power(BHP), and Torque(Nm).

**5. Exploratory Data Analysis (EDA)**
Conducted preliminary inspections to identify trends and anomalies in the data.
Insights from unique value counts and distribution summaries.

### Tools and Libraries

The following tools and libraries were used in this project:

Python Libraries:

NumPy, Pandas for data manipulation.

Matplotlib, Seaborn for visualization.

Scikit-learn for preprocessing and potential modeling.

External Tools: kagglehub for dataset retrieval.

### Acknowledgments

Dataset by Rakkesh Arv.

Special thanks to the open-source community for tools and libraries used.

### Contact
If you have any questions or would like to contribute, feel free to reach out:

- Email: [milena.baldeva@gmail.com](mailto:milena.baldeva@gmail.com)
