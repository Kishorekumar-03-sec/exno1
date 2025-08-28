# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
            import pandas as pd
            df=pd.read_csv("/Data_set.csv")
            df
<img width="1446" height="743" alt="Screenshot 2025-08-28 140501" src="https://github.com/user-attachments/assets/0918622f-a2cb-4b95-b975-b4c7221e2065" />
            
            df.isnull()
<img width="1367" height="527" alt="Screenshot 2025-08-28 141039" src="https://github.com/user-attachments/assets/872594ce-bb86-401e-8ec4-8c6670efc772" />

            df.isnull().sum()
<img width="538" height="467" alt="Screenshot 2025-08-28 141324" src="https://github.com/user-attachments/assets/925666cd-167b-4b36-abe7-dc9cbf53f120" />

            df.notnull()
<img width="1369" height="520" alt="Screenshot 2025-08-28 142143" src="https://github.com/user-attachments/assets/3907813b-b8d7-4abd-948e-18bc60a044be" />

            df.dropna(axis=1)
<img width="1001" height="525" alt="Screenshot 2025-08-28 142822" src="https://github.com/user-attachments/assets/a884c806-2a3f-4cab-8146-6fe4ffa76718" />

            df.dropna(axis=0)
<img width="1446" height="802" alt="Screenshot 2025-08-28 141641" src="https://github.com/user-attachments/assets/d07efc79-ec8f-43ca-8e4a-cf45e6327082" />


# Result
          <<include your Result here>>
