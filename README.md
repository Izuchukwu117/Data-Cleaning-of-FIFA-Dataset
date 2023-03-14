# Data-Cleaning-of-FIFA-Dataset
Data was gotten from from Kaggle with the link: https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring

Here is the link to a class on Google Meet where I was invited to share tutor fellow data analysts on data cleaning with Power Query: https://drive.google.com/file/d/1Qcuo4eFSsnKBp2YGUVO7QvYQQNHB39I4/view?usp=share_link

Data cleaning was carried out using Power Query Editor in Microsoft Excel. This works with the use of M programming language which has been extracted and saved as 'M language Editor' in text format.

What this means is that once the content of the M language editor is applied on other Excel or Power BI Query Editors and the raw FIFA file is connected to either Excel or Power BI, all the steps will be applied and the dirty dataset will be cleaned in no time.

Some of the steps carried out in data cleaning include the following:
1. Loading the dataset into Power Query Editor using UTF 8 encoding. This automatically removed some non-printable characters in Players name column.
2. Trimming the Club column to remove excess gaps.
3. Creating conditional columns where numerical data ending with M was assigned 10000000, data ending with K was assigned 1000 and others were assigned the value of 1.
4. Using 'find and replace' function to remove 'Euro' signs and letters M and K from Value, Wage, Release_Clause and Hits. Then changing their data types to decimal numbers.
5. Multiplying these columns by their corresponding conditional columns to give actual value.
6. Converting Height and weight columns containing two different measures to single measures using some metric conversion methods.

In conclusion, data cleaning is one of the most important tasks in data analysis and machine learning in that a wrong and messy data can produce wrong results and could be a danger to the organization.

Thank you for your time as you explore the files uploaded.
