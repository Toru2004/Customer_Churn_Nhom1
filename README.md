project-name/
│
├── data/                     # (Không upload dữ liệu raw lớn nếu có)
│
├── notebooks/
│   └── notebook.ipynb        # File notebook để exploratory analysis, thử code
│
├── src/                      # Source code chính của project
│   ├── preprocessing.py      # Code xử lý dữ liệu (cleaning, transform)
│   ├── modeling.py           # Code huấn luyện mô hình, lưu mô hình
│   └── predict.py            # Code load model + dự đoán mới
│
├── demo/
│   └── app.py                # Demo giao diện (Streamlit hoặc Flask)
│
├── models/
│   └── model.pkl             # File mô hình đã train, lưu bằng pickle/joblib
│
├── requirements.txt          # Danh sách thư viện cần cài (pip install -r)
│
├── README.md                 # Hướng dẫn chạy project, mô tả project
│
└── report.pdf                # Báo cáo cuối (phân tích, mô hình, kết quả)
