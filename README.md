# Thiết Kế Hệ thống Data Warehouse sử dụng Microsoft Fabric và các công cụ hỗ trợ

+ Sơ đồ kiến trúc thiết kế hệ thống Data Warehouse
  ![image](https://github.com/user-attachments/assets/4ca64696-942c-4f35-acb0-88f69ef4ee24)

+ Biểu đồ quan hệ cơ sở dữ liệu của đồ án
![image](https://github.com/user-attachments/assets/ee32f861-3cdb-4748-84e3-b3bd0f1b6d3b)

# Mô tả
- Data source kết nối đến Microsoft Fabric bao gồm mục Đồng bộ dữ liệu từ Postgres lên Microsoft Fabric thông qua Data gateway
- Prepare and transform: Bao gồm mục khởi tạo một Data Pipelie, Tiến hành kết nối và truyền dữ liệu bằng Data Pipeline và Kết quả thu được sau khi kết nối và truyền dữ liệu lưu dữ liệu trong Lakehouse (raw data)
- Store: Bao gồm trọn vẹn mục 3.7 dữ liệu các bảng được lưu trữ trong Data Warehouse và sử lý ETL
- Analyze: Cuối cùng với mục 3.8 Báo cáo thống kê tổng quan và chi tiết của dữ liệu sử dụng Power BI Desktop và Public trên Service

# Kết quả
- Link: [Demo Warehouse Project Report](https://app.powerbi.com/view?r=eyJrIjoiMzk0YjRiN2UtMTc1My00MWFiLWJlOTctMDlmNWY4MzgxNjZiIiwidCI6ImQwODcxMzNlLTRlMzAtNDkyMi1iNGI5LTViZWM0YzRmZjZiMiIsImMiOjEwfQ%3D%3D)

