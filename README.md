# Dữ liệu
Data: Trong tệp data là dữ liệu các mùa giải từ 2004-2005 đến 2021-2022, file đã tổng hợp và thêm các thuộc tính (0422.csv) và file chứa các thuộc tính sẽ sử dụng trong bài toán (04-22.csv)

Model : Trong tệp model là các mô hình mà nhóm đã lưu trong khi thực hiện bài toán

# Code
Tất cả các file mã nguồn đều là file ipynb (Python Notebook) và được chạy lần lượt từng cell (bằng cách chọn run cell, hoặc để đỡ tốn thời gian có thể run all để hệ thống chạy từng sell một). Những file này có thể chạy trên Jupyter Notebook, Google Colab hay VS Code (miễn là phải có những file dữ liệu trong phần Data và Model)
Nếu chạy trên VS Code cần cài đặt thêm extension (ví dụ iPython)

File 2004-2022.ipynb là file tổng hợp dữ liệu các mùa giải đơn lẻ và tính toán thêm các thuộc tính mới

File Data Preprocessing and Visualization.ipynb là file tiền xử lý dữ liệu và chọn ra các thuộc tính cần dùng cho bài toán

Artificial Neural Network.ipynb, K-Nearest Neighbor.ipynb, XGBoost.ipynb là các file xây dựng mô hình, xử lý tham số và đo kết quả thực nghiệm trên tập valid và tập test ứng với từng thuật toán và lưu các mô hình

Compare all model.ipynb là so sánh các mô hình tốt nhất của 3 thuật toán với nhau

Các thư viện đã được dùng là Numpy, Pandas, Matplotlib, Scikit-learn, XGBoost, Pickle và Tensorflow

Để theo dõi tiến độ làm việc của nhóm, nên chạy file theo thứ tự như thứ tự được giới thiệu
