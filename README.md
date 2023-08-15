
# Customer Segmentation and prediction for Bertelsmann Arvato

The project's primary goal is to identify the descriptive profile of the
possible client and the likelihood that a new individual from a new potential customer can sign up as a result of the targeted mailout effort.
Arvato has made available a number of dataset files with data on the demographics
of the general German population, existing Arvato clients, the results of a previously targeted
mailout campaigns, and two files with a description of the demographic traits.
The project contains the following parts:
1. Data Analysis and Preprocessing;
2. Customer Segmentation Report;
3. Supervised Learning Predictive Model

## Domain Background
Arvato is a wholly-owned subsidiary of Bertelsmann. It is a global services
company that provides a wide range of services such as customer relationship
management, supply chain management, financial services, and IT services1.
Arvato has over 70,000 employees in more than 40 countries worldwide.
Arvato provides mail services such as direct mail marketing, transactional mail,
and hybrid mail. They also provide e-commerce fulfillment services such as
warehousing, order management, and shipping. Arvato’s mail services are designed
to help businesses manage their customer communications more efficiently and
effectively.
In order to help its clients make business choices, Arvato provides them with
useful data insights. One of the industries that is expanding is customer-centric
marketing. analyzing the data to find hidden trends and client behavior. Arvato is
offering insightful information to businesses engaged in customer-centric
marketing. Nowadays, data science and machine learning are widely employed to
achieve company objectives and please consumers.
In this project, Arvato is working with a mail-order business that offers organic
items in Germany to better understand its consumer demographics and find
potential new customers. To better comprehend the various client categories,
demographic information about the German population will be analyzed, and a
system will then be built to forecast whether or not an individual would become a
customer based on that information.
## Datasets and Inputs
Four datasets are provided for the completion of the project along with an additional two
metadata about the attributes of the datasets.

• AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons(rows) x 366 features (columns).

• CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).

• MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).

• MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366
(columns).

#### 2 metadata files have been provided to give attribute information:

• DIAS Information Levels - Attributes 2017.xlsx: top-level list of attributes and descriptions, organized by informational category

• DIAS Attributes - Values 2017.xlsx: detailed mapping of data values for each
feature in alphabetical order

