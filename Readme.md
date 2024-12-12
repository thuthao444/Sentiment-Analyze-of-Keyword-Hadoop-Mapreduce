# **Chủ đề: Phân tích cảm xúc bình luận dựa trên từ khóa.**
Bài toán phân tích cảm xúc dựa trên từ khóa với MapReduce và PySpark nhằm phân loại cảm xúc (tích cực, tiêu cực, trung lập) của một bình luận. Dữ liệu đầu vào bao gồm một tập văn bản và một từ điển cảm xúc chứa các từ được gán nhãn tích cực hoặc tiêu cực. Mô hình xử lý dựa trên MapReduce, trong đó giai đoạn Map sẽ đọc từng dòng, trích xuất id và bình luận từ mỗi dòng. Giai đoạn Reduce sẽ nhận các bình luận, kiểm tra từ khóa, đếm từ tích cực/tiêu cực, xác định cảm xúc cho từng bình luận và ghi kết quả ra file. Sử dụng PySpark, quá trình này được triển khai hiệu quả trên dữ liệu lớn nhờ khả năng xử lý phân tán, giúp nhanh chóng phân tích các xu hướng cảm xúc trong tập dữ liệu, hỗ trợ đưa ra các quyết định dựa trên cảm xúc tổng thể của người dùng.
## **Các thành viên:**

1. Dương Thị Thu Thảo.
2. Cao Xuân Nguyên.
3. Đỗ Thị Thùy Trang.
4. Nguyễn Duy Minh Lâm.
5. Cao Tuấn Anh.
