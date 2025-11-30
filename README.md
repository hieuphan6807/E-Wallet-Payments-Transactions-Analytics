# E-Wallet Payments & Transactions Analytics:

Project phân tích dữ liệu ví điện tử, thực hiện bằng Python trên Google Colab. Mục tiêu là hiểu rõ tình trạng payment, refund và transaction behavior của hệ thống thông qua 3 dataset chính:

1. payment_report.csv

2. product.csv

3. transactions.csv

**🔍 Mục tiêu dự án**

- Khám phá và đánh giá chất lượng dữ liệu (EDA)

- Làm sạch & chuẩn hóa dữ liệu

- Merge và tổng hợp dữ liệu để phân tích performance

- Phân loại transaction types theo business rules

- Tìm hiểu hành vi giao dịch & hiệu suất sản phẩm

**🧪 Phần I — Exploratory Data Analysis**

Thực hiện EDA cho:

- payment_enriched (merge giữa payment_report + product)

- transactions

# Các bước chính:

- 1. Kiểm tra missing values, duplicates, data types

- 2. Phát hiện giá trị bất thường

- 3. Tóm tắt dữ liệu số và kiểm tra tính hợp lệ

**🔧 Phần II — Data Wrangling & Business Analysis
Payments & Product**

1. Xác định Top 3 sản phẩm có volume cao nhất

2. Kiểm tra sản phẩm có vi phạm quy tắc 1 product = 1 team

3. Tìm team có performance thấp nhất từ Q2/2023

4. Xác định category có đóng góp thấp nhất trong team đó

Với refund: tìm source_id đóng góp lớn nhất

Transactions

Phân loại transaction_type dựa trên transType + merchant_id:

**Bank Transfer**

Withdraw

Top Up

Payment

Transfer Money

Split Bill

Invalid transaction

**Với mỗi loại (trừ invalid):**

Số lượng giao dịch

Tổng volume

Số lượng sender

Số lượng receiver

# 🛠️ Công cụ sử dụng
Python, pandas, numpy, matplotlib/seaborn

# 📌 Kết luận

Dự án mô phỏng workflow của một Data Analyst trong lĩnh vực ví điện tử: làm sạch dữ liệu, phân loại giao dịch, đánh giá performance sản phẩm và đưa ra insight thực tế về hành vi người dùng.
