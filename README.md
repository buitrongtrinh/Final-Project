# Final Project

Tiền xử lý và phân tích trên bộ dữ liệu "Customer Personality Analysis" của kaggle
(https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## Cài đặt

Hướng dẫn cài đặt dự án trên máy của người dùng.

### Yêu cầu

- 3.7<=python<=3.10
- VS Code
- Hệ điều hành: Windows

### Cài đặt

1. Clone dự án về máy tính của bạn:
   ```bash
   git clone https://github.com/buitrongtrinh/Final-Project.git
   ```
2. ```bash
   cd Final-Project/
   ```
2. Tạo môi trường ảo (venv):
   ```bash
   py -version -m venv project_venv
   ex: py -3.10 -m venv project_venv
   ```
2. Kích hoạt môi trường ảo venv:
   ```bash
    .\project_venv\Scripts\activate
   ```
4. Cập nhật pip:
   ```bash
   python.exe -m pip install --upgrade pip
   ```
5. Cài đặt các thư viện cần:
  ```bash
  python.exe -m pip install -r requirements.txt
  ```
6. Chạy file source:
   ```bash
   jupyter nbconvert --to notebook --execute --inplace Final_Project.ipynb
7. Mở souce codee bằng VS Code:
   ```bash
   code .
   ```
