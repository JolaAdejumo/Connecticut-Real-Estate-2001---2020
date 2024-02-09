### Connecticut-Real-Estate-2001---2020

#### Background
This is an analysis of all listings of real estate sales with a sales price of $2,000 or greater, that occurred between 2001 and 2020 in Connecticut, as collected and maintained by The Office of Policy and Management.
This dataset was provided by Quantum Analytics, and it includes records such as the town, property address, date of sale, assessed value, sale amount, sales ratio, property type, and more, offering a rich source of insights into the real estate landscape.

#### Problem Statement
Preprocess, analyze, and visualize the real estate sales data, thereby exploring property assessment and generating meaningful insights for informed decision-making.
Expected outcomes include:
•	Uncover insights into the accuracy of property assessments, identifying areas where adjustments may be necessary.
•	Gain a nuanced understanding of market trends, allowing stakeholders to make informed decisions based on current and historical data.
•	Provide localized insights for different towns, assisting in regional planning and investment decisions.
•	Understand the impact of property type on assessment outcomes, helping to tailor strategies for different segments of the real estate market.
•	Investigate the role of non-use codes in property assessment, identifying patterns and potential areas for policy refinement.
•	Utilize assessor and OPM remarks to improve communication and transparency in the assessment process.

#### Dataset Features
The columns included in the file were:
1.	Serial Number: Integer, A unique identifier assigned to each record in the dataset.
2.	List Year: Integer or Date, the year in which the property information was listed or assessed.
3.	Date Recorded: Date, the date when the property information was recorded or updated.
4.	Town: String, the name of the town or locality where the property is located.
5.	Address: String, the specific address, or location details of the property.
6.	Assessed Value: Integer, the assessed monetary value of the property, typically determined by a local assessor for taxation purposes.
7.	Sale Amount: Integer, the amount for which the property was sold, if applicable.
8.	Sales Ratio: float, the ratio of the sale amount to the assessed value, providing an indication of the property's market value.
9.	Property Type: Categorical, the general category or classification of the property (e.g., residential, commercial, industrial).
10.	Residential Type: Categorical, further classification specifying the residential type (e.g., single-family, multi-family) if applicable.
11.	Non-Use Code: Categorical, a code indicating the non-use status of the property, which might include information about exemptions or special classifications.
12.	Assessor Remarks, String, additional remarks, or comments provided by the assessor related to the property assessment.
13.	OPM Remarks; String, remarks or comments from the Office of Policy and Management (OPM) related to the property data, providing additional context or information.

#### Data Exploration
Here, I:
•	Handled the missing values.
•	Converted the 'Date Recorded' column to a datetime dtype.
•	Changed 'address' and 'Assesor remarks' columns to proper case.
•	Changed column-header 'OPM reMARKS' to 'OPM Remarks'.

#### Key Insights
Assessment Accuracy.
Market Trends.
Generated localized insights.
Analyzed the impact of the various property types.
Explored the significance of non use codes in property assessment.
Compared Assessor Remarks and OPM Remarks.


#### Recommendations
Stakeholders in the real estate sector can be empowered for better decision-making and improved accuracy in property assessments through the following key strategies:
•	Firstly, giving real estate professionals access to comprehensive and up-to-date data, including market trends, market research reports, real-time property data, property transactions, and comparable sales, is crucial for informed decision-making.
•	Investing in data analytics tools and technology can help stakeholders analyze and interpret data effectively, enabling them to identify market trends, assess property values accurately, and make informed investment decisions based on current market conditions and future projections.
•	Additionally, fostering collaboration and knowledge-sharing among stakeholders, including real estate agents, appraisers, lenders, and policymakers, can enhance collective expertise and promote best practices in property valuation.
•	Moreover, promoting transparency and accountability in the assessment process, along with adherence to professional standards and ethical guidelines, is essential for building trust and confidence among stakeholders.
•	Finally, ongoing education and training programs tailored to the needs of different stakeholders(real estate professionals, appraisers, and assessors) can enhance their skills, knowledge, and competency in property valuation, decision-making processes and achieve greater accuracy in property assessments, ultimately driving better outcomes for all parties involved.

