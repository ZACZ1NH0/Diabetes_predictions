# 🏥 Diabetes Predictions - Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24%2B-orange) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## 📌 Giới Thiệu
Dự án này sử dụng các thuật toán Machine Learning để chẩn đoán bệnh tiểu đường dựa trên dữ liệu y tế. Mục tiêu chính là phát triển một mô hình chính xác để hỗ trợ bác sĩ trong việc đưa ra quyết định.

## 📂 Cấu Trúc Dự Án
```
📁 Diabetes_predictions
│── 📂 data            # Thư mục chứa dữ liệu
│── 📂 models          # Thư mục lưu các mô hình đã train
│── 📂 notebooks       # Jupyter Notebook phân tích dữ liệu
│── 📂 src             # Mã nguồn chính
│── requirements.txt   # Danh sách thư viện cần cài đặt
│── README.md         # Tài liệu mô tả dự án
```

## 📝 Dataset
Bộ dữ liệu sử dụng: **Pima Indians Diabetes Dataset** từ UCI Machine Learning Repository.
- **Số lượng mẫu**: 768
- **Số lượng đặc trưng**: 8
- **Nhãn mục tiêu**: `1` (Có tiểu đường), `0` (Không có tiểu đường)

## 🏆 Mô Hình Sử Dụng
Dự án thử nghiệm với nhiều mô hình khác nhau:
✅ **Logistic Regression** (Mô hình chính)
✅ **Random Forest**
✅ **Neural Network** (MLPClassifier)

## 🔧 Cách Chạy Dự Án
### 1️⃣ Cài đặt thư viện
```bash
pip install -r requirements.txt
```

### 2️⃣ Chạy mô hình trên Jupyter Notebook
```bash
jupyter notebook
```
Mở file [`notebooks/Diabetes_Prediction.ipynb`](./notebooks/Diabetes_Prediction.ipynb) và chạy từng cell.

### 3️⃣ Chạy trên giao diện Tkinter (GUI)
```bash
python src/gui.py
```

## 📊 Kết Quả
- Logistic Regression đạt **78% accuracy** sau khi tối ưu siêu tham số.
- Neural Network đạt **81% accuracy**, nhưng yêu cầu thời gian huấn luyện lâu hơn.

## 🚀 Cải Tiến Trong Tương Lai
- Áp dụng kỹ thuật xử lý dữ liệu mất cân bằng (`SMOTE`, `Class Weights`)
- Thử nghiệm với **XGBoost** để nâng cao độ chính xác
- Tối ưu giao diện người dùng cho trải nghiệm tốt hơn

## 📜 License
Dự án này được phát hành dưới giấy phép **MIT License**.

📬 Nếu bạn có câu hỏi, hãy liên hệ qua email: **your.email@example.com**

---
**💖 Star repo này nếu bạn thấy hữu ích!** ⭐
** Mới làm nên nhờ AI viết READ.ME :)**
