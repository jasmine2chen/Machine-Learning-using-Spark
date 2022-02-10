# Machine Learning with Spark

## Binary Customer Churn

#### I created logistic regression model that helps a makerting agency to predict which customers will churn using historial customer data, so that they can correctly assign the customers most at risk to churn an account manager. Then made prediction to the test dataset. 


customer_churn.csv:
- Name : Name of the latest contact at Company
- Age: Customer Age
- Total_Purchase: Total Ads Purchased
- Account_Manager: Binary 0=No manager, 1= Account manager assigned
- Years: Totaly Years as a customer
- Num_sites: Number of websites that use the service.
- Onboard_date: Date that the name of the latest contact was onboarded
- Location: Client HQ Address
- Company: Name of Client Company


## Clustering: number of hackers

#### I created k-means clustering model which helps a tech company to identify the number of hackers using haker data collected by their forensic engineers.

hack_data.csv:
- 'Session_Connection_Time': How long the session lasted in minutes
- 'Bytes Transferred': Number of MB transferred during session
- 'Kali_Trace_Used': Indicates if the hacker was using Kali Linux
- 'Servers_Corrupted': Number of server corrupted during the attack
- 'Pages_Corrupted': Number of pages illegally accessed
- 'Location': Location attack came from (Probably useless because the hackers used VPNs)
- 'WPM_Typing_Speed': Their estimated typing speed based on session logs.
