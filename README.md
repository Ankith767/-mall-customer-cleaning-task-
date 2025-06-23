#  Mall Customer Segmentation – Data Cleaning (Task 1)
##  Objective
Clean and prepare a raw dataset (`Mall_Customers.csv`) by addressing:
- Missing values
- Duplicate records
- Inconsistent text formats
- Incorrect data types
- Column naming inconsistencies


##  Tools Used
- Python 
- Pandas 
- Google Colab


##  Files Included
| File Name                  | Description                                |
|---------------------------|--------------------------------------------|
| `Mall_Customers.csv`      | Original dataset (raw)                     |
| `cleaned_mall_customers.csv` | Final cleaned dataset (ready for analysis) |
| `data_cleaning_ELabs.ipynb`  | Jupyter notebook with full cleaning steps  |
| `README.md`               | This documentation                        |

---

##  Cleaning Steps Performed
1. **Renamed columns** to `snake_case` (e.g., `CustomerID` → `customer_id`)
2. **Removed duplicates** using `.drop_duplicates()`
3. **Handled missing values**:
   - `gender` filled with `'unknown'`
   - Numerical fields filled using mean/median
4. **Standardized text values** (lowercased and stripped whitespace in `gender`)
5. **Fixed data types**:
   - Converted `customer_id`, `age`, `annual_income_(k$)`, and `spending_score_(1-100)` to `int`
6. **Exported clean dataset** to `cleaned_mall_customers.csv`

---

##  Outcome
The cleaned dataset is now ready for:
- Segmentation modeling
- Customer behavior analysis
- Visual storytelling or dashboards


##  Preview

| customer_id | gender  | age | annual_income_(k$) | spending_score_(1-100) |
|-------------|---------|-----|--------------------|-------------------------|
| 1           | male    | 19  | 15                 | 39                      |
| 2           | male    | 21  | 15                 | 81                      |
| 3           | female  | 20  | 16                 | 6                       |



