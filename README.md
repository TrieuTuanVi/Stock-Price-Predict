# Dự đoán giá cổ phiếu của Công ty Cổ phần Tập đoàn Hòa Phát (HOSE)

Dự án này sử dụng thư viện vnstock để thu thập dữ liệu giao dịch cổ phiếu HPG từ Sở Giao dịch Chứng khoán TP.HCM (HOSE), với mục tiêu xây dựng mô hình dự đoán xu hướng giá cổ phiếu trong tương lai.  
### Dữ liệu:
Sử dụng thư viện vnstock để lấy dữ liệu giao dịch cổ phiếu của HPG từ sàn chứng khoán.

### Các bước thực hiện:
* Làm sạch dữ liệu: Xử lý dữ liệu thô để loại bỏ các giá trị thiếu và chuẩn hóa dữ liệu.
* Thống kê dữ liệu: Khám phá và phân tích các đặc điểm chính của dữ liệu giao dịch.
* Kiểm tra độ phù hợp của dữ liệu: Đánh giá sự phù hợp của dữ liệu với các mô hình dự đoán tiềm năng.
* Chia dữ liệu: Phân chia dữ liệu thành tập huấn luyện (train) và kiểm tra (test).
* Huấn luyện mô hình: Lựa chọn mô hình dự đoán phù hợp, huấn luyện mô hình và trực quan hóa dữ liệu lịch sử cùng dự đoán.
* Đánh giá mô hình: Đo lường sai số dự đoán bằng các chỉ số như MSE (Mean Squared Error), MAE (Mean Absolute Error), và MASE (Mean Absolute Scaled Error).

### Kết quả:
* Dự đoán cho thấy giá cổ phiếu HPG sẽ tiếp tục tăng trưởng ổn định trong 6 tháng tới.
* Mức tăng trưởng dự đoán tổng cộng khoảng 6,000 đơn vị trong giai đoạn này.
