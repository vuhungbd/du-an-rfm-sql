# du-an-rfm-sql
Dùng MySQL để phân loại khách hàng
Mục tiêu:Chia nhỏ tệp khách hàng để tối ưu chi phí Marketing và nhắc lịch mua thuốc định kỳ.
Truy vấn SQL này thực hiện phân tích RFM để phân khúc khách hàng dựa trên hành vi mua hàng. 
Dữ liệu được tổng hợp theo từng khách hàng, tính các chỉ số Recency, Frequency và Monetary, sau đó sử dụng hàm NTILE để chấm điểm và phân loại khách hàng thành các nhóm như VIP, trung thành hoặc rời bỏ.
