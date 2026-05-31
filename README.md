# House Price Prediction using Machine Learning

## Giới thiệu
Dự án này xây dựng và đánh giá các mô hình học máy cho bài toán dự đoán giá nhà dựa trên bộ dữ liệu House Prices - Advanced Regression Techniques. Dữ liệu gồm nhiều đặc trưng mô tả căn nhà như diện tích, chất lượng xây dựng, vị trí, gara, tầng hầm và các tiện ích khác.

## Mục tiêu dự án
- Tiền xử lý dữ liệu bất động sản gồm cả biến số và biến phân loại.
- Xử lý giá trị khuyết, mã hóa One-Hot Encoding và chuẩn hóa dữ liệu.
- Áp dụng PCA và TruncatedSVD để giảm chiều dữ liệu.
- Xây dựng và đánh giá các mô hình hồi quy dự đoán SalePrice.
- Thực hiện phân cụm dữ liệu bằng K-Means, GMM và DBSCAN.
- Chuyển bài toán hồi quy sang phân loại bằng cách chia SalePrice thành các khoảng giá.
- So sánh các mô hình phân loại như KNN, Gaussian Naive Bayes và Multinomial Logistic Regression.

## Bộ dữ liệu
Dự án sử dụng bộ dữ liệu House Prices - Advanced Regression Techniques.  
Biến mục tiêu là `SalePrice`, biểu diễn giá bán của căn nhà.

## Các bước thực hiện
1. Khảo sát dữ liệu ban đầu.
2. Xử lý giá trị thiếu.
3. Mã hóa biến phân loại bằng One-Hot Encoding.
4. Chuẩn hóa các biến số bằng StandardScaler.
5. Giảm chiều dữ liệu bằng PCA và TruncatedSVD.
6. Xây dựng mô hình hồi quy.
7. Phân cụm dữ liệu.
8. Chuyển bài toán sang phân loại.
9. Đánh giá và so sánh kết quả.

## Mô hình sử dụng
### Hồi quy
- Linear Regression
- KNN Regression
- Ridge Regression
- MLP Regression

### Phân cụm
- K-Means
- Gaussian Mixture Model
- DBSCAN

### Phân loại
- KNN Classification
- Gaussian Naive Bayes
- Multinomial Logistic Regression

## Kết quả nổi bật
- PCA giúp giảm số chiều dữ liệu nhưng vẫn giữ lại phần lớn thông tin.
- PC1 có mối tương quan mạnh với SalePrice, hỗ trợ tốt cho phân tích và trực quan hóa.
- K-Means cho kết quả phân cụm ổn định hơn so với GMM và DBSCAN trong bài toán này.
- Multinomial Logistic Regression đạt kết quả tốt nhất trong bài toán phân loại khoảng giá nhà.

## Công nghệ sử dụng
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Cách chạy dự án
Cài đặt các thư viện cần thiết:

```bash
pip install -r requirements.txt
