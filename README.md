# Phân tích doanh thu và lợi nhuận bằng Power BI

## 1. Giới thiệu

Dự án thực hành phân tích dữ liệu bán hàng từ bộ dữ liệu **Microsoft Financial Sample**, nhằm đánh giá hiệu quả kinh doanh và tìm hiểu các giao dịch có lợi nhuận âm.

Dự án gồm hai trang báo cáo:
- **Sales Overview:** Tổng quan doanh thu và lợi nhuận.
- **Profitability & Discounts:** Phân tích các khoản lỗ theo sản phẩm và nhóm giảm giá.

## 2. Công cụ sử dụng

- **Power BI Desktop:** Xây dựng báo cáo tương tác.
- **Power Query:** Kiểm tra và xử lý dữ liệu.
- **DAX:** Tạo các chỉ số doanh thu, lợi nhuận, tỷ suất lợi nhuận và tỷ lệ giao dịch lỗ.

## 3. Dữ liệu

- Nguồn: Microsoft Financial Sample.
- Quy mô: 700 dòng dữ liệu, 16 cột.
- Giai đoạn: 2013–2014.
- Nội dung: Sản phẩm, quốc gia, phân khúc khách hàng, doanh thu, chi phí, giảm giá và lợi nhuận.

## 4. Các chỉ số chính

- **Tổng doanh thu:** Khoảng 118,73 triệu.
- **Tổng lợi nhuận:** Khoảng 16,89 triệu.
- **Tỷ suất lợi nhuận:** 14,23%.
- **Số giao dịch có lợi nhuận âm:** 58 dòng (8,29%).

## 5. Phát hiện chính

1. Nhóm giảm giá **High** chiếm khoảng **80,1% tổng giá trị lỗ** của các giao dịch có lợi nhuận âm.
2. **Carretera** là sản phẩm có tổng giá trị lỗ lớn nhất, khoảng **231.110**.
3. Nhóm **Carretera + High + Enterprise** có 10 giao dịch lỗ, với tổng giá trị lỗ **221.192,50**.

## 6. Đề xuất

Rà soát các giao dịch có mức giảm giá cao, đặc biệt với sản phẩm Carretera trong phân khúc Enterprise. Đồng thời, cân nhắc theo dõi ngưỡng tỷ suất lợi nhuận tối thiểu khi phê duyệt giảm giá.

Các phát hiện trên phản ánh mối liên hệ trong dữ liệu mẫu, không chứng minh rằng giảm giá là nguyên nhân duy nhất gây lỗ.

## 7. Dashboard

### Tổng quan kinh doanh

![Sales Overview](screenshots/sales_overview.png)

### Phân tích lợi nhuận và giảm giá

![Profitability & Discounts](screenshots/profitability_discounts.png)

## 8. Ghi chú

Đây là dự án thực hành có hướng dẫn trong quá trình học Data Analytics, sử dụng bộ dữ liệu mẫu do Microsoft cung cấp.