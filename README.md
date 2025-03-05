**Ứng Dụng Phân Tích Thống Kê Trong Dự Báo Giá Chứng Khoán**

Giới thiệu

Dự án này được phát triển bởi Nhóm 11 trong khuôn khổ môn "Phân Tích Dữ Liệu Cho Quản Lý" tại Trường Đại học Khoa học Xã hội và Nhân văn, ĐHQG TP.HCM.

Ứng dụng sử dụng các phương pháp phân tích thống kê để dự báo xu hướng giá chứng khoán, giúp nhà đầu tư đưa ra quyết định chính xác hơn. Các mô hình dự báo bao gồm:

Moving Average (MA)

Weighted Moving Average (WMA)

Exponential Smoothing (ES)

Holt (Double Exponential Smoothing)

Holt-Winters

Dữ liệu sử dụng trong dự án được lấy từ Yahoo Finance và tập trung vào các công ty thuộc ba lĩnh vực:

Thời trang: NIKE (NKE), ADIDAS (ADDYY), VF Corporation (VFC)

Kỹ thuật: TESLA (TSLA)

Công nghệ: NOKIA (NOK)

Mục tiêu nghiên cứu

Phát triển mô hình dự báo chính xác dựa trên phân tích thống kê.

Đánh giá hiệu quả của các mô hình dự báo trên các ngành có đặc điểm khác nhau.

Xây dựng một nền tảng trực quan giúp nhà đầu tư dễ dàng sử dụng.

Công nghệ sử dụng

Ngôn ngữ lập trình: Python

Thư viện: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, SciPy, Streamlit

Công cụ hỗ trợ: Power Query, Microsoft Excel

Cấu trúc dự án

├── data/                # Dữ liệu đầu vào
├── models/              # Các mô hình dự báo
├── notebooks/           # Notebook phân tích và thử nghiệm
├── src/                 # Mã nguồn chính
│   ├── data_processing.py   # Tiền xử lý dữ liệu
│   ├── forecasting.py       # Các mô hình dự báo
│   ├── visualization.py     # Trực quan hóa dữ liệu
│   └── app.py               # Ứng dụng chính chạy trên Streamlit
├── README.md            # Tài liệu dự án
└── requirements.txt      # Danh sách thư viện cần cài đặt

Cách sử dụng

Cài đặt thư viện cần thiết:

pip install -r requirements.txt

Chạy ứng dụng:

streamlit run src/app.py

Nhập mã chứng khoán, chọn mô hình dự báo và xem kết quả trực quan.

Đóng góp

Mọi đóng góp từ cộng đồng đều được hoan nghênh. Hãy tạo một issue hoặc pull request nếu bạn có ý tưởng cải thiện dự án.

Liên hệ

Nhóm 11 - Trường ĐH KHXH&NV, ĐHQG TP.HCM

Giảng viên hướng dẫn: ThS. Trần Đình Anh Huy

📌 Demo ứng dụng: Stock Prediction App
📌 GitHub Repository: Stock Prediction GitHub
