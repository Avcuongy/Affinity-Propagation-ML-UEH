# Affinity-Propagation-ML-UEH

## 📦 Yêu Cầu
- Python 3.10 trở lên (khuyên dùng Python 3.10)
- pip đã được cài đặt
- (Tùy chọn) virtualenv hoặc conda để tạo môi trường ảo

## 🛠️ Tạo môi trường ảo (khuyến khích)
Với virtualenv:
```
python -m venv venv
# Kích hoạt môi trường:
source venv/bin/activate       # Trên macOS/Linux
venv\Scripts\activate          # Trên Windows
```

Hoặc với conda:
```
conda create -n affinity-env python=3.10
conda activate affinity-env
```

## 📥 Cài đặt các thư viện từ requirements.txt
Sau khi đã kích hoạt môi trường ảo, chạy lệnh sau để cài đặt các thư viện từ file requirements.txt:

```
pip install -r requirements.txt
```

## 📁 Cấu trúc thư mục dự án

```
Affinity-Propagation-ML-UEH/
├── data/
├── notebooks/
│   ├── Affinity Propagation/
│   └── Comparision/
├── requirements.txt
├── README.md
└── .gitignore
```
