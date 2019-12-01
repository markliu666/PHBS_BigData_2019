# Homework 1
## 1. Big Data Problem:
For retailing companies, like Walmart, how to forecast the sales of next day/month to keep high inventory turnover?

There is always an important question for retailing companies to know how to forecast what items customers are most likely to buy next day/month. If you are doing a good job, your company will have a high inventory turnover and eventually beat the competitors.

Although it is not an easy job, we find that some datasets have great impact on this problem. For example, the internal daily sales data during Walmart’s lifetime can provide strong clues to the next period’s sales performance. We can use these datasets to make a big data analysis to solve this problem.
## 2. The Intrinsic Big Data Properties:
There are quantities of data that are qualified as inputs. First of all, the internal daily sales data during Walmart’s lifetime. Second, the external sales data of Walmart’s competitors, complementors and the whole industry. Third, the discussions and rumors on the websites of all the items related. Fourth, the feedback from customers and investors.

There are three factors to check whether a problem can be recognized as a big data problem.

(1)	Volume: Sales data and public opinion analysis are all data of high volumes, which can reach billions of entries of information.

(2)	Velocity: It is important to gather sales data and public opinions every day or even every second. The data are growing so rapidly that we need to handle them in a higher and higher speed. It is a huge challenge for the big data system.

(3)	Variety: In our dataset, there are not only relational data, like sales data, but also non-relational data, like public opinion data. For non-relational data, there are also a lot of forms, texts, pictures, video streams and others.
## 3. Propose a Workflow to Solve This Problem:
![Workflow](https://github.com/markliu666/PHBS_BigData_2019/blob/master/Workflow.jpg)
## 4. Decide What Kind of Database Can be Used:
For sales data, we can use relational database, like MySQL. Because sales data are structured data which has clear relationship with each feature.

For public opinion data, we can use non-relational database, like mongoDB. Because public opinion data are non-structured data and they can be stored with methods of document method, columnar method and others.
