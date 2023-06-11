Để tránh bị xung đột phiên bản xin hãy sử dụng đúng những phiên bản sau:
+ Visual Studio 2022 Community
+ SQL Server 2022 Developer

+ Để chạy code làm sạch dữ liệu bằng python trong Code/LamSachDuLieu.ipynb vui lòng sửa lại đường dẫn có trong code đến thư mục Data:
df_credit = pd.read_csv('./credit_record.csv') -> df_credit = pd.read_csv('../Data/credit_record.csv')
df_application = pd.read_csv('./application_record.csv') -> df_application = pd.read_csv('../Data/application_record.csv')

