# A/B Testing Analysis

##  Overview
This project performs an A/B test analysis to determine whether there is a significant difference in conversion rates between a control group and a test group. The dataset includes various campaign performance metrics such as website clicks, add-to-cart actions, and purchases.

##  Dataset
The dataset consists of two CSV files:
- `control_group.csv`: Data for the control group
- `test_group.csv`: Data for the test group

### **Columns in the Dataset:**
- `Campaign Name`
- `Date`
- `Spend [USD]`
- `# of Impressions`
- `Reach`
- `# of Website Clicks`
- `# of Searches`
- `# of View Content`
- `# of Add to Cart`
- `# of Purchase`
- `group` (control or test)

##  Installation
To set up the environment, install the required libraries using:
```bash
pip install -r requirements.txt
```

##  Steps in Analysis
1. **Load and Inspect Data**
   - Read the datasets using pandas
   - Check for missing values and duplicates
2. **Data Cleaning**
   - Merge the control and test groups into a single dataset
   - Add a `converted` column to indicate whether a user made a purchase
3. **Exploratory Data Analysis (EDA)**
   - Visualize conversion rates
   - Compare metrics like website clicks, add-to-cart rates, and view content counts
4. **Statistical Testing**
   - **Z-Test** for proportions to check conversion rate differences
   - **T-Test** to compare mean differences between groups
5. **Conclusion**
   - Interpret results and determine if the test had a significant impact

##  Visualizations
The analysis includes several visualizations such as:
- Bar plots for conversion rates
- Box plots for purchase distributions
- Comparison of website clicks, add-to-cart, and view content rates

##  Requirements
Create a `requirements.txt` file with the following content:
```txt
pandas
numpy
matplotlib
seaborn
scipy
statsmodels
jupyterlab
```

##  Contributing
Feel free to fork this repository, suggest improvements, or report any issues!

##  License
This project is licensed under the MIT License.

## Contributor
This project is created by me **(Mohammed Wajahath Ali)** solely by taking some insights from diff sources like stackoverflow and chatgpt
to refine it and make it more robust.

