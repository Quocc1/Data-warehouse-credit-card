To avoid version conflicts, please use the following versions correctly:
+ Visual Studio 2022 Community
+ SQL Server 2022 Developer

+ To run the python data cleaning code in Code/LamSachDuLieu.ipynb, please correct the path included in the code to the Data folder:
df_credit = pd.read_csv('./credit_record.csv') -> df_credit = pd.read_csv('../Data/credit_record.csv')
df_application = pd.read_csv('./application_record.csv') -> df_application = pd.read_csv('../Data/application_record.csv')

