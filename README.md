
# **Final Project**

Tiền xử lý và phân tích trên bộ dữ liệu **Customer Personality Analysis** được lấy từ [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).

---
## **Danh sách sinh viên thực hiện**

1. **Bùi Trọng Trịnh** - 22120390
2. **Nguyễn Lê Phúc Thắng** - 22120332

---

# Hướng dẫn chạy dự án trên Jupyter Notebook (local)

## 1. Cài đặt dự án

### 1.1 Cài đặt các công cụ cần thiết

#### Python
- Đảm bảo Python đã được cài đặt trên máy tính. 
- Nếu chưa, tải Python tại [Python.org](https://www.python.org/).

#### Jupyter Notebook
- Cài đặt Jupyter Notebook bằng lệnh:
  ```bash
  pip install notebook
  ```

#### Virtual Environment (Tuỳ chọn)
- Sử dụng môi trường ảo để quản lý các gói Python trong dự án:
  ```bash
  python -m venv env
  source env/bin/activate  # macOS/Linux
  env\Scripts\activate    # Windows
  ```

### 1.2 Clone dự án từ GitHub
- Thực hiện lệnh sau để tải mã nguồn về máy tính:
  ```bash
  git clone https://github.com/buitrongtrinh/Final-Project.git
  ```

### 1.3 Chuyển vào thư mục dự án
- Di chuyển vào thư mục chứa mã nguồn:
  ```bash
  cd Final-Project/
  ```

### 1.4 Cài đặt môi trường và thư viện

1. **Tạo môi trường ảo**:
   - Dùng lệnh sau để tạo một môi trường ảo:
     ```bash
     py -version -m venv project_venv
     ```
     Ví dụ:
     ```bash
     py -3.10 -m venv project_venv
     ```

2. **Kích hoạt môi trường ảo**:
   - Kích hoạt môi trường ảo trên Windows:
     ```bash
     .\project_venv\Scripts\activate
     ```

3. **Cập nhật công cụ quản lý gói pip**:
   - Cập nhật phiên bản mới nhất của pip:
     ```bash
     python.exe -m pip install --upgrade pip
     ```

4. **Cài đặt các thư viện cần thiết**:
   - Cài đặt các thư viện từ file `requirements.txt`:
     ```bash
     python.exe -m pip install -r requirements.txt
     ```

---

## 2. Mở Jupyter Notebook

1. Mở terminal hoặc Command Prompt.
2. Điều hướng đến thư mục chứa dự án:
   ```bash
   cd đường_dẫn_đến_dự_án
   ```
3. Chạy lệnh để khởi động Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Trình duyệt sẽ tự động mở giao diện Jupyter Notebook. Nếu không, bạn sẽ nhận được một URL trên terminal, hãy copy và dán URL đó vào trình duyệt.

---

## 3. Chạy file Notebook

1. Đảm bảo các file `.ipynb` (file Notebook) nằm trong thư mục dự án.
2. Nhấn vào file cần mở trong giao diện Jupyter để bắt đầu.
3. Mỗi file Notebook được chia thành các *cell* (ô mã lệnh).
4. Nhấn **Shift + Enter** để chạy từng cell tuần tự.
5. Nếu dự án cần nhập dữ liệu, hãy đảm bảo dữ liệu đã được đặt trong thư mục đúng.

---

## 4. Lưu ý

- Kiểm tra các thông báo lỗi trong quá trình chạy và khắc phục nếu có.
- Khi hoàn tất, nhấn **"Quit"** trên giao diện Jupyter hoặc dừng server bằng tổ hợp phím:
  ```bash
  Ctrl + C
  ```
- Nếu gặp lỗi hoặc cần thêm thông tin, hãy kiểm tra file `README.md` trong dự án hoặc liên hệ với tác giả.
---

