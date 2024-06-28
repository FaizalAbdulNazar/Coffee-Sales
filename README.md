This is a project showcasing the coffee sales from the year 2019-22.

From this dataset using MS Excel, I found out the total sales over time. Also which country saw the highest sales in coffee.

I also tried to look for the top 5 customers inputting different scenarios like, the coffee size, roast type etc.

Using these datas I created a dashboard to visualize my findings.
![SalesDashboard](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/a7f834b5-5f2d-4c7f-8f28-15a3832ae1f0)

First of all I had to clean the dataset, in this dataset itself you can see it have three sections, Orders, Customers and Products.

Orders data showing the customer ID, product ID, Order ID and Order date and the quantity of coffee.
![Orders_data](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/3c8287a5-8f95-4ed6-b53d-45531c1f4920)

Customers data includes the customer ID, customer name and their email-ID and the country they reside.
![Customers_data](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/14d2a6fe-fcb0-4fb5-a2c6-7cea6bbacc71)

Products data is about the product ID, coffee types, price and profit from the sales.
![Products_data](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/d94303c6-f8fa-4526-8525-d5ddb0580051)

I set the data in a more understandable format by including the order ID, Customer ID, Product ID, Customer Name, Roast Type, Unit Price etc in a single dataset.

To make this happen I used functions like Xlookup, to get the data from the Customers data to the orders data.
<img width="960" alt="Xlookup" src="https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/6017536d-02f9-4a05-9e67-7c3ad7a548df">

Then I used INDEXMATCH to get the data from Products data to Orders dataset.
<img width="960" alt="INDEXMATCH" src="https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/02e14299-5906-4073-993d-2aba88a64417">

This helped me make a much cleaner and visually appealing dataset.

After this then I moved on to creating Pivot Tables to visualize the foundings.

This showing the total sales over time.
![Pivot_Chart1](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/c0e986aa-cc85-458f-8f88-bd8fcb8060c2)

Sales by country.
![Salesbycountry](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/e9ff04e9-7942-4b4f-83d7-4d7c9b5e1a63)

Top 5 Customers.
![Top5customers](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/4bf65b57-c621-4ef3-9bf0-f21104a584fa)

With the help of the Pivot tables I created Pivot charts.

I build a dashboard by cobining all the pivot charts I created.

I have shared the dataset and the dashboard. You can also see the formulas I used in the dataset.
