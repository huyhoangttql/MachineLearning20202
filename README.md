# MachineLearning20202
## Giới thiệu bài toán
### Bài toán phân loại review phim
- Mục tiêu : Chia đánh giá của khách hàng thành 2 loại tích cực và tiêu cực
- Mục đích : Phục vụ cho việc đánh giá phim, cân nhắc về việc dừng lại hay chiếu tiếp ở các rạp
- Hướng giải quyết bài toán
    - **Naive Bayes**
    - **Mạng noron nhân tạo**
### Tiền xử lý dữ liệu
- Tập dữ liệu : [IMDB Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Đầu vào: Tập các comment của khách hàng đã được gán nhãn 
- Đầu ra: Mỗi comment sẽ được biểu diễn dưới dạng vector
- Xóa thẻ HTML, xóa dấu câu và số, xóa kí tự đơn, xóa nhiều khoảng trắng (space)

### Xây dựng mô hình 
* Xây dựng mô hình Naive Bayes( Multinomial Naive Bayes)
* Xây dựng mạng nơ ron 
### Kết quả
* Mô hình Naive Bayes: đạt độ chính xác tầm 86%, chưa phải kết quả tốt 
* Mô hình mạng nơ ron: đạt độ chính xác cao hơn Naive Bayes, tầm 89%
* Hiện nay, có rất nhiều mô hình đạt kết quả cao lên đến 97% với tập dữ liệu này