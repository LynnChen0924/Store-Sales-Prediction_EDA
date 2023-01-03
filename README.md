<br>

## <div align="center">**Store Sales Prediction: Exploratory Data Analysis on Store Sales Data**</div>

<details open>
<summary>Introduction</summary>
  
The goal of this competation is to help an Ecuador company as known as Corporación Favorita to predict store sales for each product family and store combinations. I applied data methods to detect outliers and missing values and conduct univariate and bivariate analysis to explore holiday, earthquake, oil price, seasonal effect on sales/transactions.

<details open>
<summary>Responsibility of the research</summary>
  
**Lingyi Chen** EDA Part. Explore data pattern and characteristics to understand multiple effects on sales. Conduct feature selection for model preparation.
  
**Gorden Li(Kehao Li)**: Model Part.

</details>
  
</details>

<details open>
<summary> Univariate Analysis</summary>

  **1. Sales Rank**
  
  * Rank average sales by store number, product family and cluster

  * Explore filter rules of clusters using pivot table
  <img width="323" alt="image" src="https://user-images.githubusercontent.com/92767352/209512152-39089b4f-8582-43ae-a8ad-e7ed8208f2d0.png">
  
  **2. Holiday**
  
  * Summarize holiday types using histogram
    <img width="990" alt="image" src="https://user-images.githubusercontent.com/92767352/209509668-06b86630-57a1-4c9c-a9a5-eaf94d8f8a59.png">

  **3. Oil Price**
  
  * Show a general trend
  <img width="877" alt="image" src="https://user-images.githubusercontent.com/92767352/209511034-179e00cd-f2ff-4591-8c17-5d582a154843.png">
  
  * Explore trend on sales of September which is the turning point every year
  <img width="408" alt="image" src="https://user-images.githubusercontent.com/92767352/209511158-962c7f24-18d7-410a-9913-38d2fe93e75a.png">

  <img width="391" alt="image" src="https://user-images.githubusercontent.com/92767352/209511207-df3868e4-8597-463d-bc32-e4981146c419.png">

  **4. Promotions**
  
  * Based on Sales of every product family:
  <img width="996" alt="image" src="https://user-images.githubusercontent.com/92767352/209511306-fc5209d7-b911-44a8-bbec-97c9f9a62a6d.png">

  * Explore relationship of region and sales
  <img width="539" alt="image" src="https://user-images.githubusercontent.com/92767352/209511400-8482bb01-a275-47d9-bc9a-4bd55cf84f92.png">

</details>
  
</details>

<details open>
<summary> Bivariate analysis </summary>

  **1. Seasonal Effect**
  
  * Time series plot of sales on product family by date, year, month(part of charts)
  <img width="596" alt="image" src="https://user-images.githubusercontent.com/92767352/209513369-e34cb982-f698-4aea-a1b5-1e57e9010296.png">
  <img width="600" alt="image" src="https://user-images.githubusercontent.com/92767352/209513390-13d30777-cb55-4c09-9648-b35fc5c48be8.png">
  <img width="595" alt="image" src="https://user-images.githubusercontent.com/92767352/209513420-35f87566-e3ce-4ccf-9fe1-032465cc0c86.png">
  
  * We conclude from Average transactions by month/Date that transaction volume is highest at the end of the year
  <img width="969" alt="image" src="https://user-images.githubusercontent.com/92767352/209513443-4b80edf8-a68e-44d3-9920-bb8cfeb54dad.png">
  
  <img width="972" alt="image" src="https://user-images.githubusercontent.com/92767352/209514845-25ff1e87-6b7a-49aa-a293-5966794c2b51.png">
  
  * We also select time window to explore activeness of every product family:
  <img width="994" alt="image" src="https://user-images.githubusercontent.com/92767352/209515272-58c76da0-712d-41ad-9925-57b1c27ce20e.png">


  **2. Wage Effect**
  
  I split the salary days and normal days to see if salary effect sales correspondingly:
  
  <img width="400" alt="image" src="https://user-images.githubusercontent.com/92767352/209515340-dc7b5798-a4bc-4cc8-a417-481dafe666f4.png">
  
  **3. Earthquake Effect**
  
  I ploted sales of every year to see sales change by month and found April to July changed significantly so I plot it and following month's sales:
  
  <img width="911" alt="image" src="https://user-images.githubusercontent.com/92767352/209516216-d6a3c27a-4fb6-4062-9bb8-c7aa1de24067.png">
  
  <img width="934" alt="image" src="https://user-images.githubusercontent.com/92767352/209516469-e90d7957-a5d4-4ca5-ba9a-d2f34160d5f9.png">
  
  They did effect the sales but sales back to normal in 2017.

  **4. Holiday Effect**
  
  * I built a chart to compare sales on holidays and non-holidays:
  
  <img width="383" alt="image" src="https://user-images.githubusercontent.com/92767352/209516645-f618fa88-6b91-4b19-b116-3d6a87bc9f94.png">
 
  * Holiday events did effect sales in most areas so I applied A/B test to see if each national/local/reginal/special events has different effect on sales.


</details>

</details>

</details>

## <div align="center">Contact</div>

email: chenlingyi0924@gmail.com

LinkedIn: https://www.linkedin.com/in/lingyichen97/

<br>

