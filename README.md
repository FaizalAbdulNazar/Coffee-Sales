This is a project showcasing the coffee sales from the year 2021-23.

From this dataset using MS Excel, I found out the total sales over time. Also which country saw the highest sales in coffee.

I also tried to look for the top 5 customers inputting different scenarios like, the coffee size, roast type etc.

Using these datas I created a dashboard to visualize my findings.
![SalesDashboard](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/a7f834b5-5f2d-4c7f-8f28-15a3832ae1f0)

First of all I had to clean the dataset, in this dataset itself you can see it have three sections, Orders, Customers and Products.

Orders data showing the customer ID, product ID, Order ID and Order date and the quantity of coffee.
![Orders](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/2803f45e-541e-4fd3-9f8d-618402543f63)

Customers data includes the customer ID, customer name and their email-ID and the country they reside.
![Customers](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/b2b72520-5856-4394-9e1c-3c7689ff50a1)

Products data is about the product ID, coffee types, price and profit from the sales.
![Products](https://github.com/FaizalAbdulNazar/Coffee-Sales/assets/159605612/7c829e6c-69c1-4bbe-a9ce-955e6129ca40)

I set the data in a more understandable format by including the order ID, Customer ID, Product ID, Customer Name, Roast Type, Unit Price etc in a single dataset.

To make this happen I used functions like Xlookup,  to get the data from the Customers data to the orders data.

Then I used INDEXMATCH to get the data from Products data to Orders dataset.

This helped me make a much cleaner and visually appealing dataset.

After this then I moved on to creating Pivot Tables to visualize the foundings.

With the help of the Pivot tables I created Pivot charts.

I build a dashboard by cobining all the pivot charts I created.

I have shared the dataset and the dashboard. You can see the formulas I used in the dataset.
