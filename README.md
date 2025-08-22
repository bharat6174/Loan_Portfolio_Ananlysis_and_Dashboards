# Loan_Portfolio_Tableau_&_Excel_Dashboards

## Project Objective
To visualize loans data for easy and better understanding of various KPIs and metrics. Using which the stakeholders can take informed decisions for future approvals and business needs.

## Dataset used
- Dataset: <a href="https://github.com/bharat6174/Loan_Portfolio_Dashboards/blob/main/The%20Project%20-%20Data_Pivots_Dashboard.xlsx">The Project - Data_Pivots_Dashboard.xlsx</a> (open it, then click on _**View raw**_ to download the excel file)

## Questions (KPIs)
1. **Aggregate Measures**(on both dashboards)
    - Total Loan Applications
        - Month to Date(MTD) Applications
        - Month on Month(MoM) Change in Applications
    - Total Disbursal Amount
        - MTD Disbursal Amount
        - MoM Disbursal Amount
    - Total Collection Amount
        - MTD Collection Amount
        - MoM Collection Amount
    - Average Interest Rate: Overall
        - Average Interest Rate: MTD
        - Average Interest Rate: MoM
    - Average Debt-to-Income Ration(DTI): Overall
        - Average DTI: MTD
        - Average DTI: MoM
2. **Good Loan Measures**
      - Good loan applications percentage
      - Total Good loan applications
      - Good Loan Disbursal Amount
      - Good Loan Collection Amount
3. **Bad Loan Measures**
      - Bad loan applications percentage
      - Total Bad loan applications
      - Bad Loan Disbursal Amount
      - Bad Loan Collection Amount
4. **Grid View w.r.t. Loan Status**
      - Applications
      - Disbursal Amount
      - Collection Amount
      - Average Interest Rate
      - Average DTI
5. **Applications by Month**(Line chart)
6. **Applications by State**(Map)
7. **Applications by Tenor**(Donut Chart)
8. **Applications by Employment Period**(Bar Chart)
9. **Applications by Purpose**(Bar Chart)
10. **Applications by House Ownership**(Tree Map)

## Process
1. Understand the columns and their significance using data dictionary(<a href="https://github.com/bharat6174/Loan_Portfolio_Excel_Dashboards/blob/main/Data%20Dictionary.png">see dictionary</a>) and data itself.
2. Analysing the data requirement for various KPIs.
### In Tableau
1. Importing data in a new tableau file.
2. Created multiple sheets for various KPIs(1 to 4) with the help of multiple calculated fields.
3. Placed the KPIs on a new dashboard with appropriate formatting for visual appeal.
4. For the 2nd dashboard, created a parameter with 3 measures - Loan Accounts, Disbursal Amount, Colleiton Amount to reflect these on KPIs 5 to 6.
5. Then created 6 different types of charts for KPIs 5 to 10 with above parameter and placed them on the 2nd dashboard along with the above 3 measures as a drop down item.
6. For the 3rd dashboard, simply placed some categorical columns with respective measures in a table.
7. Added 3 items for filtering the data in all the sheets and same items as slicers in all 3 dashboards.
8. Turned on the filter tool on every dashboard element to use as filter for all other elements and with applicability on all 3 dashboards simultaneously. 
9. Added 3 navigation switches on left side of the dashboards for faster switching between all the dashboards.<br>
### In Excel
1. To create metrics and visualisations, created appropriate pivot tables in a seperate sheet (named as **Design Sheet** in the excel file attached).
4. Made required graphs along with respective pivot tables for various metrics and KPIs.
5. Created 2 seperate sheets, 1 for each dashboard(named as **Dashboard 1**and **Dashboard 2** in the excel file attached).
6. Made the dashboards and formatted the tiles and charts in the dashboards as per the requirement and visual appeal.
7. At last added 2 slicers for filtering in the pivot table sheet and attaching the same on dashboards.
8. Added switch tiles on left side of the dashboards for faster switching between both dashboards and the data(loan_data).<br>


**Note:** There are 3 dashboards in Tableau and 2 in Excel as the main data sheet in Excel is doing the same work as the **Details (Dashboard No. 3)** is doing in Tableau.<br>
**Note:** The **MoM rate** in the dashboard is w.r.t Nov-Dec as the dataset is limited to the year 2021.<br>
**Note:** The interaction with the dashboards and slicers is only possible in the attached excel sheet(The Project - Data_Pivots_Dashboard.xlsv) in this repository and the Tableau file, not in the attached images of dashboards.

## Dashboards in Tableau
**Dashboard 1 - Summary Dashboard**<br>
It has visualizations for KPIs 1 to 4<br>
<img width="1559" height="877" alt="image" src="https://github.com/user-attachments/assets/621aa9d9-2cf9-4f32-a78b-c8efa94fe8c2" />
- <a href="https://github.com/bharat6174/Loan_Portfolio_Ananlysis_and_Dashboards/blob/main/Dashboard%201.png">View Dashboard</a><br>


**Dashboard 2 - Overview Dashboard**<br>
It has visualizations for KPIs 1 and 5 to 10<br>
<img width="1560" height="879" alt="image" src="https://github.com/user-attachments/assets/e4c04fb2-5b4a-4e8b-bd07-b32f61da0c59" />
- <a href="https://github.com/bharat6174/Loan_Portfolio_Ananlysis_and_Dashboards/blob/main/Dashboard%202.png">View Dashboard</a><br>


**Dashboard 3 - Details Dashboard**<br>
It has a crisp view of various categories and repective measures<br>
<img width="1559" height="876" alt="image" src="https://github.com/user-attachments/assets/bcc32248-e26f-486b-82d5-1e4de446cbbe" />
- <a href="https://github.com/bharat6174/Loan_Portfolio_Ananlysis_and_Dashboards/blob/main/Dashboard%203.png">View Dashboard</a><br>

## Dashboards in Excel
**Dashboard 1 - Summary Dashboard**<br>
It has visualizations for KPIs 1 to 4<br>
<img width="1547" height="820" alt="Dashboard_1" src="https://github.com/user-attachments/assets/d0c78f6b-f8eb-484c-bf92-746dc41a9563" /><br>
- <a href="https://github.com/bharat6174/Loan_Portfolio_Dashboards/blob/main/Dashboard_1.png">View Dashboard</a><br>


**Dashboard 2 - Applications Dashboard**<br>
It has visualizations for KPIs 1 and 5 to 10<br>
<img width="1550" height="821" alt="Dashboard_2" src="https://github.com/user-attachments/assets/884b6f4b-34f5-488a-932b-c37626cb9bb6" /><br>
- <a href="https://github.com/bharat6174/Loan_Portfolio_Dashboards/blob/main/Dashboard_2.png">View Dashboard</a><br>
