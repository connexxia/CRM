# Presentation
Don't start from scratch to develop your Business Intelligence applications! Custics offer ready-to-use dashboards for Finance, CRM and Customers Service. 
Each template is free. We only charge for the development of specific features, the support to deploy, etc...
And to get an idea of ​​the dashboards contained in our Qlik Template for the CRM, here are the Release Notes.
# Product description
Qlik Template for the CRM is a BI application that provides dashboards for CRM analytics powered by Qlik. 
This app is divided into 2 parts :
The section [A] provides an overview of the Sales performances.
The section [B] provides specific dashboards for analyzing the Customer lifecycle.
# Release Notes CRM V2
## **[A] The Sales point of view**
The section [A] provides an overview of the Sales performances. Follow all your Key Performance Indicators from Captured Sales, Linked Sales, Quantity, Frequency, Average basket, IPT, Cross-sell... For each KPI, you have its definition, value and evolutions MTD and YTD.
1. **Sales** MTD, YTD, Evolution over time: The total amount of sales from transactions with real customers
2. **Customers** MTD, YTD, Evolution over time: The total distinct count of customers with at least one positive transactions per month and with the cumulative count over one year
3. **Sales evolution** per dimension: The sales performance across various dimensions such as regions, products or POS
4. **Sales evolution** per customers segment: The total amount of sales from transactions with real customers splited into 3 segments : New, Existing and Winback
5. **KPIs evolution**: The volume of sales over time and a KPI over the same period of time
6. **Correlations** between KPIs and attributes: The volume of sales and a KPI distributed over most predictive purchase attributes
7. **Top Items**: Top n items in sales all axis, per axis and Top 10 items contribution in the total Sales
8. **Gap analysis**: View of sales disparities between the current and previous year per dimension
## **[B] The Customer lifecycle**
The section [B] provides specific dashboards for analyzing the Customer lifecycle.These dashboards explore the different customer behaviors such as segmentation, risk, recruitment, repeaters, customer journey and satisfaction. By mastering the customer lifecycle, businesses can manage and hopefully improve their customer relation to drive lasting loyalty.
1. **Pareto analysis**: Customers segmentation of the 80/20 principle suggests that a significant portion of a revenue often comes from a small percentage of its customers
2. **LMH segmentation**: Dividing customers database into 3 groups (Low, Medium and High) based on annual spending basis
3. **LMH segmentation levers**: What is the most important lever for value creation in your context?
4. **Basket analysis**: As an introduction to MBA, this view sheds light on shopper behavior by uncovering patterns of frequently co-purchased items.
5. **Buy and Stop analysis**: The Top Items in transactions in descending order of sales in a classic histogram but with Buy & Stop risk for each item
6. **Next transaction analysis**: Customer behavior views describe how customers shop, from their first purchase, to how often they make a purchase...
7. **Quality Of Service and Customer Satisfaction**: The Quality of Service graph displays the number of customers per segment and the QoS delivered by the Customer Service on each segment.
8. **Recruitment analysis**: This sankey view provides a Marketing Manager with insights into the effectiveness of for example, hiring strategies for acquiring new customers.
9. **Recruitment of Rank(n)**: Recruitment is based on the percentage of transactions of rank 1 or higher in the sales evolution timeframe with a detail per POS.
10. **Customer journey**: View of the key elements of the customer journey while keeping an eye on customer satisfaction
11. **Repeaters rate**: Repeaters rate or Repeater Purchase Rate (RPR) is a key metric used in business to measure the percentage of customers who return to make a second purchase.
12. **Customers Satisfaction**: The customer satisfaction (NPS) over time and a KPI over the same period of time
13. **Impact of Marketing actions on KPIs**: One effective method for measuring the impact of actions is to compare KPIs of the customers exposed to the actions to those who are not (Control Group).
14. **Top Items selling with one selected Item**: To get the top N items that are bought together with a specific and selected item.
15. **Contribution and Penetration**: To find out the most-selling items in terms of Recruitment, Contribution and Penetration.
16. **Customers clustering**: This is useful for grouping together customers and visually separate samples in n groups of equal variance like the Average Basket versus Satisfaction.
# Files description
1. **README.md**: In simple words, the README file gives you a detailed description of the project with Product description till how to use it...
2. **CRM version.indice.qvf**: This QVF file is essential as it serves as the container for the entire Qlik application, encapsulating data, script and visualizations. This files can be shared with others, allowing collaborative data analysis and exploration within the Qlik environment.
3. **crm_data.xlsx**: This file contains the sample data used in the dashboards but also all the details you need to know about the Project, from the Team to UAT.
4. **LICENSE.md**: A short and simple permissive license with conditions only requiring preservation of copyright 2024 Custis and license notices attached with the QVF file
# How to use it
1. Upload the file.qvf under the QMC environment: _Add existing apps and scripts_
2. Because the file.qvf already contains the data, there is no need to _Reload now_ the app.   
3. But before any reloading of the script, _Create new connection_ with the file.xlsx.
4. Create a data connection for example to Google Drive
5. In the script editor section _Connect to the data_ let a Data_Source='[lib://Template:Google_Drive - sebastien.parmentier@gmail.com/ ...
6. Then _Reload now_ the app to update the data, ETL, variables...
7. For a better experience, switch off the _Touch screen mode_
8. To get the full app, contact Sébastien at sebastien.parmentier@gmail.com
# Tested configurations
## Qlik Sense Entreprise and Cloud
1. May 2024
2. February 2024
3. ...
4. February 2023
## Desktop browser
1. Google Chrome
2. Microsoft Edge
# Backlog
1. Top contributions analysis: Introduction to ML to detect the most profitable customers
2. Cross Selling: Overview of the Cross Selling
3. Gifting analysis: Measure the impact of gifting on Sales
4. Customer Service: Customer Service template for BI is a new Qlik app.
# Roadmap
1. If you have a good idea, you can submit it to our Support.
2. Please clarify the why and the KPI defintion. This will help prioritising against other things.
# Support
For any question, please contact Sébastien at sebastien.parmentier@gmail.com
# Screenshots
![A01](https://github.com/user-attachments/assets/3a56e4e3-c629-4347-a873-b4db99b52ab5)
![A02](https://github.com/user-attachments/assets/6c2bce3d-e22a-4ccb-821e-4957a8dbb02e)
![A03](https://github.com/user-attachments/assets/5527d132-0959-4370-8b94-f395b8f978a0)
![A04](https://github.com/user-attachments/assets/390f3453-daca-4344-b309-645c2ba4c2c2)
![A05](https://github.com/user-attachments/assets/eabf9b5e-2863-48ad-8f19-5b71f0985518)
![A06](https://github.com/user-attachments/assets/7a7bce37-c95e-4b39-9989-562eb6b9ddef)
![A07](https://github.com/user-attachments/assets/63c4805a-7d76-4d78-9742-10d724a0e2f4)
![A08](https://github.com/user-attachments/assets/7a0741b8-630b-4855-a005-a0e1e513e97e)

![B01](https://github.com/user-attachments/assets/a5acc964-12d0-41ed-97bb-08cd54e191a4)
![B02](https://github.com/user-attachments/assets/e5fb9897-0aad-4ca6-ae9c-6511a532da6b)
![B03](https://github.com/user-attachments/assets/40ac2e08-8378-47c2-b5e7-85fa400e418c)
![B04](https://github.com/user-attachments/assets/98d1b2d6-3b9a-4d0c-a2b7-c75c1dd29809)
![B05](https://github.com/user-attachments/assets/12771621-73c8-4be2-9c00-f280dd34beb6)
![B06](https://github.com/user-attachments/assets/146149d0-2030-4e9a-89e6-de5a8b206700)
![B07](https://github.com/user-attachments/assets/726a3e4e-fc14-4f6c-aa37-a27db9ff6017)
![B08](https://github.com/user-attachments/assets/6d874a43-adca-4973-b1eb-389a863d24e5)
![B09](https://github.com/user-attachments/assets/037c8e7b-c3b4-4495-95c0-2a1b3fc2c026)
![B10](https://github.com/user-attachments/assets/450782f2-a0e0-4a7e-b27a-3e03383a6e66)
![B11](https://github.com/user-attachments/assets/6d46e57d-a0ff-46bf-987b-d52a68339a22)
![B12](https://github.com/user-attachments/assets/0774a2f8-677a-41ed-bbbc-0ed2eeae2a72)
![B13](https://github.com/user-attachments/assets/b535158a-4247-4efa-a765-44fc120c5a4d)
![B14](https://github.com/user-attachments/assets/52193a18-a635-4d91-a467-f1e99991b15b)
![B15](https://github.com/user-attachments/assets/927c9e3c-ff1c-41ae-9c1c-e5dd9796355e)
![B16](https://github.com/user-attachments/assets/7df4c166-bc3e-4c4b-9b7d-aeb6bbabd3a1)
