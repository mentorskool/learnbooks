## <font color="019aff">Learning Objective</font>

After a successfull attempt at the scenrio you will be able to

1. Understand **Migration** from on-premise to AWS cloud.

2. Architect an **Batch ETL pipeline** to move data to a **warehouse**.

3. Express the importance of **5 pillars of architecture**

<hr style="height:1px;border-width:0;color:#cfcfcf;background-color:#cfcfcf">

## <font color="019aff">Problem Statement</font>

GlobalMart is one of the leading E-Commerce giants with presence in the North America and Europe region. It has presence across 120 markets and primarily deals with 3 lines of business:

* Technology
* Office Supplies
* Furniture

With a rapid increase in business, GlobalMart is seeing a huge jump in the number of customers registering on their website across countries. This sudden increase in reach of their
business is putting a huge pressure on their current IT infrastructure. GlobalMart would also like to make use of their long collected data to develop data-driven strategies.

Following is the as-is IT infrastructure / Challenges at GlobalMart:

* Company has a front end application where customers can log in, browse products, place orders, track and return them if needed (<font color="#66CDAA">Don't worry about migrating applicatione</font>)
* An on-premise relational database is located in san-francisco which stores orders, customers, vendors, transactions and products information (<font color="#66CDAA">Do you think moving relational database to cloud is a good idea?</font>)
* The company is poised to expand its product footprint where it wishes to add more variety to the existing line of products. With the variety of products increasing, going
ahead with the same table structure for new products is no longer feasible.
  * The data structure (<font color="#66CDAA">Schema</font>) to store products information needs to be more flexible to be able to accommodate changing product information (<font color="#66CDAA">Would you still go with relational database for this requirement?</font>)
* The company does not have a clean and processed store of data. There is no single source of truth. With growing dependency on data, GlobalMart wishes to have a single source of truth developed and deployed for their analysts to refer and track the KPI's. (<font color="#66CDAA">What is the best possible solution to have a single source of truth?</font>)

So if you are to be assigned as a data engineerig manager how would you go about to solve these requirements:

* Suggest how AWS Cloud can help them address their infrastructure issues in order to cope up with the business demand
* How will you implement pipeline security, resource monitoring ?
* Finally. Architect the whole system to demonstrate POC?

<hr style="height:1px;border-width:0;color:#cfcfcf;background-color:#cfcfcf">

## <font color="019aff">Help you can use !!</font>

* Access to diagramming tool [draw.io](https://app.diagrams.net/) for architecture design .  You can hand draw on a paper if you prefer
* [Well-Architected-Framework](https://aws.amazon.com/blogs/apn/the-5-pillars-of-the-aws-well-architected-framework/) from AWS
* Please share your solution and thoughts [here](https://forms.gle/wtFEUExpGZFHTM9D6)

Wish to discuss the solution to this problem and solve more interesting problems?

Join us on [Slack](https://join.slack.com/t/mentorclass/shared_invite/zt-cridbd9y-FZxvAZo4fqV5l1YRA3C05A) today!
