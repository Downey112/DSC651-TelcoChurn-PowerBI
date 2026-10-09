**FACULTY OF COMPUTER AND MATHEMATICAL SCIENCES BACHELOR OF SCIENCE (HONS) STATISTICS** 

**DATA REPRESENTATION AND REPORTING TECHNIQUES** 

**(DSC651)** 

**GROUP PROJECT** 

**TITLE:** 

**CUSTOMER CHURN ANALYSIS USING POWER BI DASHBOARD: A STUDY OF IBM TELCO CUSTOMER CHURN DATASET** 

**GROUP: CDCS2415A** 

## **PREPARED BY:** 

|**PREPARED BY:**||
|---|---|
|**NAME**|**STUDENT ID**|
|**NURUL AMIRA AINNA BINTI ABDULLAH**|****|
|**ADRIANA MAISARAH BINTI MOHD ZAMRI**|****|
|**MUHAMMAD LUQMAN HAKIM BIN SYAHRULNIZAM**|****|
|**MUHAMMAD LUQMAN HAQIMI BIN SHAHMIZAN**|****|



**PREPARED FOR:** 

**DR AMRI BIN AB. RAHMAN** 

|**Table**|<br>**of Contents**|
|---|---|
|1.0|INTRODUCTION ........................................................................................................................... 3|
|1.1|BACKGROUND OF STUDY ......................................................................................................... 3|
|1.2|PROBLEM STATEMENT ............................................................................................................... 4|
|1.3|RESEARCH OBJECTIVES ............................................................................................................ 5|
|1.4|RESEARCH QUESTIONS ............................................................................................................. 6|
|2.0|LITERATURE REVIEW ................................................................................................................. 7|
|2.1|AN OVERVIEW OF CUSTOMER CHURN .................................................................................. 7|
|2.2|CUSTOMER CHURN IN THE TELECOMMUNICATION INDUSTRY ..................................... 8|
|2.3|FACTORS AFFECTING CUSTOMER CHURN ............................................................................ 9|
|3.0|METHODOLOGY .........................................................................................................................11|
|3.1|RESEARCH DESIGN ....................................................................................................................11|
|3.2|DATA SOURCE AND DATA DESCRIPTION ..............................................................................11|
|3.3|VARIABLES .................................................................................................................................. 12|
|3.4|DATA PREPARATION AND TRANSFORMATION ................................................................... 13|
|3.5|DASHBOARD DEVELOPMENT AND VISUALIZATION ........................................................ 14|
|3.6|EXPLORATORY DATA ANALYSIS (EDA) ................................................................................ 15|
|4.0|RESULTS AND DISCUSSION ..................................................................................................... 17|
||4.1 Horizontal Bar Chart of Top Reasons Contributing to Customer Churn|
||4.2 Donut Chart of Customer Churn Distribution|
||4.3 Bar Chart of Customer Churn by Internet Service|
||4.4 Horizontal Bar Chart of Churned Customers by Payment Method|
||4.5 Line Chart of Churned Customers by Tenure Group|
||4.6 Bar Chart of Customers Churn by Contract Type|
|5.0|CONCLUSION .............................................................................................................................. 23|
|REFERENCES ........................................................................................................................................... 24||



## **1.0 INTRODUCTION** 

## **1.1 BACKGROUND OF STUDY** 

The telecommunications industry is one of the most competitive and data-driven industries in the world. As digital communication services become increasingly important in daily life, telecommunication companies continuously face challenges in retaining their customers. One of the major challenges is customer churn, which refers to customers discontinuing or switching from a service provider. High customer churn rates can negatively affect company revenue, profitability, and customer lifetime value. Therefore, understanding customer churn behaviour has become an important aspect for telecommunication companies in developing effective customer retention strategies (Ahmad et al., 2022). 

Customer churn has gained increasing attention among researchers and business organizations due to its significant impact on business performance. Acquiring new customers is generally more costly than retaining existing customers. According to Ahmad et al. (2022), customer retention has become a strategic priority for telecommunication companies because reducing churn can significantly improve profitability and long-term business sustainability. As a result, organizations are increasingly focusing on analysing customer behaviour and identifying factors associated with customer churn. 

The IBM Telco Customer Churn Dataset is widely used in customer churn analysis studies as it contains comprehensive customer information, including demographic characteristics, service subscriptions, account information, and customer churn status. The dataset consists of 7,043 customer records and provides valuable information for analysing customer churn patterns across different customer segments (Huang et al., 2022). By analysing this dataset, researchers can identify the characteristics of customers who are more likely to churn and explore the relationships between demographic, service, and financial factors and customer churn behaviour. 

Nowadays, various business intelligence and data analytics tools are available to support effective data analysis and visualization. One of the most widely used tools is 

Microsoft Power BI. According to Al-Fattah and Ibrahim (2023), Power BI enables organizations to transform raw data into meaningful visual representations through interactive dashboards and reports. The platform integrates data preparation, data modelling, visualization, and reporting capabilities within a single environment. Through interactive dashboards, complex analytical findings can be communicated more effectively to stakeholders and support data-driven decision-making processes. 

In conclusion, customer churn analysis is important for understanding customer behaviour and identifying factors associated with customer attrition. The use of interactive visualization tools such as Power BI can improve the accessibility and interpretation of customer information. Therefore, this study utilizes the IBM Telco Customer Churn Dataset and Microsoft Power BI to analyse and visualize customer churn patterns through interactive dashboards and reporting techniques, thereby supporting effective data representation. 

## **1.2 PROBLEM STATEMENT** 

Customer churn remains one of the major challenges faced by telecommunication companies. The loss of existing customers can negatively affect company revenue, profitability, and customer lifetime value. Despite the increasing availability of customer data, many organizations still face difficulties in identifying churn patterns and understanding the factors that contribute to customer attrition. Although customer information is widely available, the challenge lies in transforming large volumes of customer data into meaningful insights that can support effective decision-making (Ahmad et al., 2022). 

The current approach to customer churn analysis often relies on spreadsheets, static reports, and technical analytical outputs. These methods frequently require manual interpretation and may not effectively communicate important findings to non-technical stakeholders. Furthermore, customer datasets usually contain numerous variables related to demographics, services, contracts, and financial information, making it difficult to 

identify relationships and trends without appropriate data visualization and reporting techniques (Han et al., 2023). 

Despite the availability of business intelligence tools, there are still limitations in presenting customer churn information in a clear, interactive, and user-friendly manner. Users may find it difficult to compare churn behaviour across different customer segments and identify the factors most associated with customer attrition. As a result, valuable insights may not be fully utilized for customer retention planning and business improvement initiatives (Pouyanfar et al., 2021). 

To address these issues, this study proposes the development of an interactive customer churn dashboard using the IBM Telco Customer Churn Dataset and Microsoft Power BI. Through data preparation, visualization, and reporting techniques, the proposed dashboard will transform raw customer data into meaningful visual insights. The dashboard will allow users to explore churn patterns based on demographic, service, contract, and financial factors, thereby supporting effective data representation, reporting, and decisionmaking processes. 

## **1.3 RESEARCH OBJECTIVES** 

Customer churn analysis is important in helping telecommunication companies understand customer behaviour and improve customer retention strategies. Through the application of data representation and reporting techniques using Microsoft Power BI, this study aims to transform customer data into meaningful insights that support decision-making processes. The research objectives are as follows: 

- a) To identify the main reasons contributing to customer churn. 

- b) To analyze the overall distribution of customer churn in the telecommunication industry. 

- c) To analyze customer churn patterns based on internet service types, payment methods, and customer tenure. 

- d) To examine the relationship between contract type and customer churn 

## **1.4 RESEARCH QUESTIONS** 

To achieve the research objectives, several research questions have been formulated to guide this study. These questions focus on the analysis and visualization of customer churn patterns using Microsoft Power BI. The research questions are as follows: 

- a) What are the main reasons contributing to customer churn? 

- b) What is the overall distribution of customer churn among telecommunication customers? 

- c) How do customer churn patterns vary across different internet service types, payment methods, and customer tenure groups? 

- d) How does contract type affect customer churn? 

## **2.0 LITERATURE REVIEW** 

## **2.1 AN OVERVIEW OF CUSTOMER CHURN** 

Customer churn refers to the loss of customers when they discontinue a service or switch to another service provider. It is considered one of the most important indicators of customer retention and business performance, particularly in highly competitive industries such as telecommunications. According to Ahmad et al. (2022), customer churn can significantly affect company profitability because the cost of acquiring new customers is often higher than the cost of retaining existing customers. 

Customer churn can occur due to various factors, including dissatisfaction with services, pricing issues, poor customer support, attractive offers from competitors, and changing customer preferences. As competition within the telecommunications industry continues to increase, understanding customer churn behaviour has become increasingly important for organizations seeking to maintain their customer base and improve long-term sustainability (Huang et al., 2022). 

The growing availability of customer data has encouraged organizations to adopt datadriven approaches in analysing customer behaviour and churn patterns. By examining customer demographics, service subscriptions, contract information, and financial characteristics, companies can identify factors associated with customer attrition and develop more effective customer retention strategies. Therefore, customer churn analysis plays a crucial role in supporting business decision-making and improving customer relationship management (Ahmad et al., 2022). 

In recent years, customer churn analysis has become one of the most widely studied topics in business analytics and data science. The application of analytical and visualization tools enables organizations to transform large volumes of customer data into meaningful insights that can support strategic planning and customer retention initiatives. Consequently, customer churn analysis remains an essential component of modern business intelligence practices (Al-Fattah & Ibrahim, 2023). 

## **2.2 CUSTOMER CHURN IN THE TELECOMMUNICATION INDUSTRY** 

Customer churn is a major concern in the telecommunication industry due to the highly competitive nature of the market and the availability of alternative service providers. As telecommunication services have become an essential part of daily life, customers can easily switch to competitors that offer better pricing, service quality, or promotional packages. As a result, telecommunication companies continuously seek effective strategies to retain existing customers and reduce churn rates (Ahmad et al., 2022). 

According to Huang et al. (2022), customer churn has significant financial implications for telecommunication companies because customer acquisition costs are substantially higher than customer retention costs. High churn rates may lead to revenue loss, reduced customer lifetime value, and increased marketing expenses. Therefore, understanding the factors associated with customer churn is essential for maintaining long-term business sustainability and competitiveness. 

Telecommunication companies collect large volumes of customer data, including demographic information, service subscriptions, contract details, payment methods, and usage behaviour. These data provide valuable opportunities for organizations to analyze customer behaviour and identify patterns associated with churn. Through effective analysis, companies can better understand customer needs and implement targeted retention strategies to reduce customer attrition (Bhuse et al., 2022). 

In recent years, business intelligence and data analytics techniques have been widely applied in the telecommunication industry to support customer churn analysis. Interactive dashboards and visualization tools enable organizations to monitor customer behaviour, identify high-risk customer segments, and communicate analytical findings more effectively. Consequently, customer churn analysis has become an important component of strategic decision-making within the telecommunication sector (Al-Fattah & Ibrahim, 2023). 

## **2.3 FACTORS AFFECTING CUSTOMER CHURN** 

Customer churn is influenced by various factors that are associated with customer characteristics, service usage, contractual agreements, and financial commitments. Understanding these factors is important because it helps organizations identify customer segments that are more likely to discontinue their services and develop appropriate retention strategies (Huang et al., 2022). 

Demographic factors are commonly examined in customer churn studies. Variables such as gender, age group, senior citizen status, partner status, and dependents may influence customer behaviour and service preferences. Different customer groups often exhibit different levels of satisfaction and loyalty, which may affect their likelihood of leaving a service provider (Ahmad et al., 2022). 

Service-related factors also play a significant role in customer churn. The quality of services, internet subscriptions, technical support, online security services, and additional service features can influence customer satisfaction. Customers who experience service limitations or do not perceive value from the services provided may be more likely to switch to alternative providers (Bhuse et al., 2022). 

Contract-related factors are another important determinant of customer churn. Customers with shorter contract periods, particularly month-to-month contracts, generally have greater flexibility to switch service providers compared to customers who are committed to longer contract agreements. Therefore, contract type is frequently identified as one of the strongest factors associated with customer churn in the telecommunication industry (Huang et al., 2022). 

Financial factors such as monthly charges, total charges, and payment methods may also influence customer retention. Higher service costs or perceived lack of value may encourage customers to discontinue their subscriptions. Consequently, analyzing financial factors can provide valuable insights into customer behaviour and help organizations develop more effective retention strategies (Ahmad et al., 2022). 

In summary, demographic, service, contract, and financial factors are among the key determinants of customer churn. Understanding the relationships between these factors and 

customer churn is essential for supporting effective customer retention initiatives and improving business performance. 

## **3.0 METHODOLOGY** 

## **3.1 RESEARCH DESIGN** 

This study adopts a quantitative analytical research design that focuses on customer churn analysis using the IBM Telco Customer Churn Dataset. The study applies descriptive and diagnostic analytics to examine customer churn patterns and identify factors associated with customer attrition. Descriptive analytics is used to summarize customer characteristics and churn behaviour through statistical summaries and data visualization, while diagnostic analytics is used to explore the relationships between customer churn and various demographic, service, contract, and financial factors (Davenport & Harris, 2022). 

The study utilizes Microsoft Power BI as the primary analytical and visualization tool. Power BI provides capabilities for data preparation, transformation, analysis, and dashboard development within a single environment. Through interactive dashboards and visual representations, users are able to explore customer churn patterns and gain meaningful insights from the dataset (Al-Fattah & Ibrahim, 2023). 

The findings of this study are presented through an interactive dashboard that supports effective data representation and reporting. The dashboard is designed to facilitate data exploration, trend identification, and decision-making by transforming raw customer data into meaningful visual information. 

## **3.2 DATA SOURCE AND DATA DESCRIPTION** 

The dataset used in this study is the IBM Telco Customer Churn Dataset obtained from Kaggle. The dataset is widely used in customer churn analysis studies and contains customer information from a telecommunication company. It consists of 7,043 customer records and 33 variables that describe customer demographics, service subscriptions, account information, and customer churn status. 

The dataset provides comprehensive information that enables the analysis of customer behaviour and factors associated with customer attrition. The variables included in the 

dataset can be categorized into several dimensions, namely demographic factors, servicerelated factors, contract-related factors, financial factors, and customer churn status. These variables allow researchers to identify patterns and relationships that may influence customer churn behaviour (Huang et al., 2022). 

The target variable of this study is Churn, which indicates whether a customer has discontinued the service or remained with the company. By utilizing this dataset, the study aims to explore customer churn patterns and develop an interactive dashboard that supports effective data representation and reporting of customer churn insights. 

## **3.3 VARIABLES** 

The IBM Telco Customer Churn Dataset contains various variables related to customer demographics, service subscriptions, account information, and financial characteristics. These variables are used to analyze and visualize customer churn patterns based on demographic, service, contract, and financial factors. 

Table 3.1 presents the selected variables used in this study and their descriptions. 

|**Variable**|**Description**|**Type **|**Category**|
|---|---|---|---|
|Gender|Customer gender|Categorical|Demographic|
|SeniorCitizen|Senior citizen status|Categorical|Demographic|
|Partner|Partner status|Categorical|Demographic|
|Dependents|Dependent status|Categorical|Demographic|
|Tenure|Number of months<br>the customer has<br>stayed with the<br>company|Numeric|Contract|
|InternetService|Type of internet<br>service subscribed by<br>the customer|Categorical|Service|
|TechSupport|Technical support<br>subscription status|Categorical|Service|



|OnlineSecurity|Online security<br>subscription status|Categorical|Service|
|---|---|---|---|
|Contract|Type of customer<br>contract|Categorical|Contract|
|PaymentMethod|Method used by the<br>customer for payment|Categorical|Financial|
|MonthlyCharges|Monthly amount<br>charged to the<br>customer|Numeric|Financial|
|TotalCharges|Total amount charged<br>to the customer|Numeric|Financial|
|Churn|Customer churn<br>status (Yes/No)|Categorical|Target Variable|



## **3.4 DATA PREPARATION AND TRANSFORMATION** 

Data preparation is an important process to ensure that the dataset is accurate, consistent, and suitable for analysis. In this study, the IBM Telco Customer Churn Dataset is imported into Microsoft Power BI for data cleaning, transformation, and preparation before visualization and dashboard development. 

The data preparation process begins with data profiling to examine the structure and quality of the dataset. This process is used to identify missing values, inconsistent data formats, and potential data quality issues. Variables are reviewed to ensure that the data types are correctly assigned according to their respective attributes. According to Han et al. (2023), data profiling and quality assessment are essential steps in ensuring reliable analytical outcomes. 

Subsequently, data cleaning and transformation are performed using Power Query Editor in Power BI. The transformations include correcting data types, handling missing values, removing unnecessary fields, and standardizing categorical variables to ensure 

consistency throughout the dataset. These processes help improve data quality and reliability for further analysis (Han et al., 2023; Verbeke et al., 2023). 

After the cleaning process, selected variables are organized and transformed into a structured format suitable for visualization and reporting purposes. The prepared dataset is then utilized for exploratory data analysis and dashboard development. Microsoft Power BI provides an integrated environment for data preparation, transformation, and visualization, enabling users to generate meaningful insights through interactive dashboards and reports (Al-Fattah & Ibrahim, 2023). 

Through these preparation and transformation processes, the dataset becomes more suitable for identifying customer churn patterns and generating meaningful insights through interactive visualizations. 

## **3.5 DASHBOARD DEVELOPMENT AND VISUALIZATION** 

The dashboard is developed using Microsoft Power BI to provide an interactive platform for analyzing and visualizing customer churn patterns. The dashboard is designed to transform raw customer data into meaningful visual information that supports effective data representation and reporting. Through interactive visualizations, users can explore customer behaviour and identify factors associated with customer churn. 

The dashboard incorporates various visualization components, including KPI cards, bar charts, donut charts, line charts, and slicers. KPI cards are used to present key performance indicators such as total customers, total churned customers, churn rate, and average monthly charges. These indicators provide users with a quick overview of customer churn performance. 

In addition, interactive charts are used to analyze customer churn across different dimensions. These include churn distribution by contract type, internet service, payment method, and demographic characteristics. Line charts and comparative visualizations are also utilized to examine churn patterns based on customer tenure and financial factors. 

The dashboard includes filtering and data exploration capabilities through slicers and cross-filtering functions. Users can filter the data according to customer characteristics and service attributes to obtain more detailed insights. The interactive features enable users to compare customer segments and identify trends associated with customer churn. 

Overall, the dashboard is designed to enhance data accessibility, improve analytical understanding, and support decision-making processes. By utilizing Microsoft Power BI, the dashboard provides an effective platform for communicating customer churn insights through interactive and visually appealing reports (Al-Fattah & Ibrahim, 2023). 

## **3.6 EXPLORATORY DATA ANALYSIS (EDA)** 

Exploratory Data Analysis (EDA) is conducted to understand the characteristics of the dataset and identify customer churn patterns before dashboard development. EDA helps summarize the data, identify trends, and discover relationships between variables that may influence customer churn behaviour. 

The analysis begins with a univariate analysis to examine the distribution of individual variables, including demographic, service, contract, and financial factors. Descriptive statistics and frequency distributions are used to provide an overview of customer characteristics within the dataset. 

Subsequently, bivariate analysis is performed to compare customer churn status across different variables. This analysis focuses on identifying variations in churn behaviour based on factors such as contract type, internet service, payment method, tenure, and monthly charges. Comparative visualizations are used to highlight differences between churned and retained customers. 

In addition, multivariate analysis is conducted through interactive Power BI visualizations to explore the relationships among multiple variables simultaneously. The analysis enables users to identify customer segments with higher churn tendencies and gain deeper insights into customer behaviour. 

The findings obtained from the exploratory data analysis are used as the foundation for dashboard development and visualization. Through EDA, important patterns and trends can be identified and effectively communicated through interactive reports and dashboards. 

## **4.0 RESULTS AND DISCUSSION** 

## **4.1 Horizontal Bar Chart of Top Reasons Contributing to Customer Churn** 

The chart presents the top reasons why customers leave the company. The most common reason is Attitude of Support Person, which was reported by 192 customers. This indicates that negative experiences with customer support staff can strongly influence a customer’s decision to leave. 

The second and third most common reasons are Competitor Offered Higher Download Speeds (189 customers) and Competitor Offered More Data (162 customers). These findings show that customers are attracted to competitors that provide better internet performance and more attractive service packages. 

Other important reasons include Competitor Made Better Offer (140 customers), Attitude of Service Provider (135 customers), Network Reliability (103 customers), Product Dissatisfaction (102 customers), and Price Too High (98 customers). 

Overall, the results show that customer churn is mainly influenced by two factors: poor customer service and strong competition. To reduce churn, the company should 

improve customer support quality, enhance service reliability, and offer more competitive plans that meet customer needs. 

## **4.2 Donut Chart of Customer Churn Distribution** 

The donut chart shows the overall distribution of customer churn among 7,043 customers. Out of the total customers, 73.46% did not churn, while 26.54% churned and stopped using the company’s services. 

The blue section of the chart is much larger than the orange section, showing that most customers decided to stay with the company. This is a positive sign because it indicates that the company is able to retain the majority of its customers. 

However, the churn rate of 26.54% is still quite high because more than one out of every four customers chose to leave. Losing customers can reduce the company’s revenue and increase the cost of acquiring new customers. 

Therefore, it is important for the company to understand the reasons behind customer churn and develop effective retention strategies to improve customer loyalty. 

## **4.3 Bar Chart of Customer Churn by Internet Service** 

The bar chart shows the churn rate for different internet service types, including Fiber Optic, DSL, and customers with no internet service. 

Among all categories, Fiber Optic customers recorded the highest churn rate at 41.9%. This means that approximately four out of ten Fiber Optic customers left the company. Meanwhile, DSL customers recorded a churn rate of 19.0%, while customers without internet service had the lowest churn rate at 7.4%. 

The large difference between Fiber Optic and other service types indicates that Fiber Optic customers are more likely to discontinue their services. One possible reason is that Fiber Optic customers may have higher expectations regarding internet speed, service quality, and customer support. If these expectations are not met, customers may decide to switch to another provider. 

In conclusion, the company should pay special attention to Fiber Optic customers by improving service quality and customer satisfaction to reduce churn. 

## **4.4 Horizontal Bar Chart of Churned Customers by Payment Method** 

The chart displays the number of churned customers according to their payment methods. 

The highest number of churned customers comes from Electronic Check users, with 1,071 customers leaving the company. This number is significantly higher than other payment methods such as Mailed Check (308 customers), Bank Transfer (258 customers), and Credit Card (232 customers). 

This result indicates that customers using Electronic Check are more likely to churn than customers using automatic payment methods. Customers who use automatic payments may find it more convenient to continue their subscriptions, making them less likely to leave the company. 

The company may consider promoting automatic payment options to improve customer retention and reduce churn rates. 

## **4.5 Line Chart of Churned Customers by Tenure Group** 

The chart shows customer churn based on different tenure groups, which represent the length of time customers have stayed with the company. 

The 0–12 months group recorded the highest number of churned customers, with 1,037 customers leaving the company. This number is much higher than all other tenure groups. After the first year, the number of churned customers drops significantly. 

This pattern suggests that new customers are more likely to leave the company during their first year of service. During this period, customers are still evaluating whether the service meets their expectations. If they experience poor service quality, high costs, or better offers from competitors, they may decide to leave. 

Therefore, the company should focus on improving customer experience during the first 12 months because this is the most critical period for customer retention. 

## **4.6 Bar Chart of Customer Churn by Contract Type** 

The bar chart illustrates customer churn based on different contract types, namely Month-to-Month, One Year, and Two Year contracts. 

Customers with Month-to-Month contracts recorded the highest churn rate at 42.71%. This means that almost half of the customers with this contract type decided to leave the company. In comparison, customers with One Year contracts had a significantly lower churn rate of only 11.27%, while customers with Two Year contracts recorded the lowest churn rate at 2.83%. 

This pattern suggests that contract length has a strong influence on customer retention. Customers who subscribe to longer contracts are less likely to leave because they are committed to the service for a longer period. On the other hand, Month-to-Month customers have greater flexibility and can switch to competitors more easily. 

Therefore, encouraging customers to choose longer contract plans may help the company reduce churn and improve customer retention. 

**5.0 CONCLUSION** 

This study analyzed customer churn patterns using the IBM Telco Customer Churn Dataset and Microsoft Power BI. Through data preparation, visualization, and exploratory data analysis, several factors associated with customer churn were identified, including contract type, internet service type, payment method, customer tenure, and customerreported churn reasons. 

The findings revealed that customers with Month-to-Month contracts recorded the highest churn rate compared to customers with longer contract periods. In addition, Fiber Optic customers showed the highest churn rate among internet service types. Electronic Check users contributed the largest number of churned customers, while the highest number of churned customers was observed within the first 12 months of service. Furthermore, customer support issues and attractive competitor offerings were identified as the most common reasons contributing to customer churn. 

Overall, the Power BI dashboard successfully transformed raw customer data into meaningful visual insights that support effective data representation and reporting. The interactive visualizations enable users to better understand customer churn behaviour and identify important patterns associated with customer attrition. The findings of this study may assist telecommunication companies in developing more effective customer retention strategies and improving decision-making processes. 

## **REFERENCES** 

IBM. (n.d.). Telco customer churn. IBM Documentation. Retrieved from: https://www.ibm.com/docs/en/cognos-analytics/12.0.x?topic=samples-telco-customer-churn TanKY. (n.d.). Telco customer churn: IBM dataset. Kaggle. Retrieved from: https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset 

Microsoft. (2026). What is Power BI? Microsoft Learn. Retrieved from: https://learn.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview Microsoft. (2026). Download Power BI. Microsoft Power Platform. Retrieved from: https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads 

Microsoft. (2026). Microsoft Power BI. Retrieved from: https://www.microsoft.com/en-us/power-platform/products/power-bi 

Microsoft. (2026). Training for Power BI. Microsoft Learn. Retrieved from: https://learn.microsoft.com/en-us/training/powerplatform/power-bi 

Han, J., Kamber, M., & Pei, J. (2011). Data Mining: Concepts and Techniques (3rd ed.). Morgan Kaufmann. Retrieved from: https://www.sciencedirect.com/book/9780123814791/data-mining-concepts-and-techniques Davenport, T. H., & Harris, J. G. (2017). Competing on Analytics: The New Science of Winning. Harvard Business Review Press. Retrieved from: https://store.hbr.org/product/competing-on-analytics-the-new-science-of-winning/10313 IBM. (2024). IBM Telco Customer Churn Prediction. GitHub. Retrieved from: https://github.com/IBM/telco-customer-churn-on-icp4d 

Ahmed Shahriar. (n.d.). IBM Telco Customer Churn Prediction. GitHub. Retrieved from: https://github.com/ahmedshahriar/Customer-Churn-Prediction 

