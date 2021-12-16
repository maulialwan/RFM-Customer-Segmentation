# RFM-Customer-Segmentation
A notebook of clustering tasks uses the Recency, Frequency, Monetary (RFM) method.

This project focuses on customer analysis and segmentation, which help generate specific marketing strategies targeting different groups. RFM analysis was conducted on a UK-based online retail transaction dataset with 541.909 rows of records hosted on the UCI Machine Learning Repository.

RFM Analysis
RFM is a marketing analysis tool to identify a company's customers by analyzing their spending habits. This method is commonly used in marketing and has received particular attention in the retail and professional services industries.

RFM stands for:

- Recency: When is the last time a customer purchases?
- Frequency: How often does a customer purchase?
- Monetary: How much does a customer spend?

According to the RFM analysis, customers can be divided into four main segments, which are:

|Segment|RFM Score|
|---|---|
|Bronze|3-5|
|Silver|6-8|
|Gold|9-10|
|Platinum|11-12|

Ultimately, the table below depicts the mean value of RFM and the number of customers of each segment:

                       Recency   Frequency   Monetary    RFMSegment
    Customer Segment
			
          Platinum      13.82     278.14      5990.12     757
          Gold          40.55     94.42       1849.02     761
          Bronze        190.95    14.76       257.98      1175
          Silver        80.09     40.32       790.22      1226
          

**Action Plan**

**1. Platinum**

Since platinum is the best group of customers, this group generates a high percentage of overall revenues. Therefore, we have to maintain a great relationship with this group of customers and make them feel appreciated and valued. We can give them a loyalty program or reward point as a treatment. Furthermore, new products recommendation, offer of luxury goods, and another kind of cross or upselling strategy is worth doing to this group.

**2. Gold**

This group has a little bit lower than platinum group characteristics, consisting of customers who spent a lot of money. The main difference with the platinum group is in the recency value. Thus, we can give them a loyalty program or reward point, an offer of luxury goods, and a regular limited attractive offer with a discount or cashback voucher via email.

**3. Silver**

This group consists of various customers characteristics, including new-joined customers who purchased a high amount. We can regularly give discounts and cashback vouchers, and another kind of reactivation and retention strategy such as limited offer via email and ads to maintain relationships.

**4. Bronze**

This group is a 'lost customer' group. We can treat them with a reactivation strategy, such as an email campaign to make them aware and ask them to give feedback to us. If they provide us with feedback, we can know their preferences and why they are inactive. 
