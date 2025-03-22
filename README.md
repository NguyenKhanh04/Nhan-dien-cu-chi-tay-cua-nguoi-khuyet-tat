<h1 align="center">🖐 Hệ thống nhận diện cử chỉ tay của người khuyết tật ! 🚀</h1>
<div align="center">

<p align="center">
  <img src="logoDaiNam.png" alt="DaiNam University Logo" width="200"/>
  <img src="LogoAIoTLab.png" alt="AIoTLab Logo" width="170"/>
</p>

[![Made by AIoTLab](https://img.shields.io/badge/Made%20by%20AIoTLab-blue?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Fit DNU](https://img.shields.io/badge/Fit%20DNU-green?style=for-the-badge)](https://fitdnu.net/)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-red?style=for-the-badge)](https://dainam.edu.vn)
</div>

Dự án này sử dụng **sử dụng Mạng Neural Nhân tạo (ANN) với kiến trúc Sequential**  **TensorFlow**, **OpenCV** để nhận diện cử chỉ tay  thông qua webcam. **Mô hình ANN** được huấn luyện để nhận diện **10 cử chỉ tay** khác nhau 

## 🎯 Tính năng chính
-Ghi lại video cử chỉ tay và lưu keypoints vào CSV.
-Khi camera hiển thị lên màn hình và nhận diện các cử chỉ được lưu sẵn trước đó.

## 📥 Cài đặt

### 🛠 Điều kiện cần

- 🐍 **Python** `3.7+` - Ngôn ngữ lập trình python
- 💾 **RAM** `8GB+` - Được đề xuất cho hiệu suất tối ưu
- 🖥 **CPU** `4+ cores` - Để xử lý song song
- 📷 **Webcam** - Để sử dụng tính năng nhận diện cử chỉ ( **Webcam** hoặc **Camera** hoạt động tốt )


## 🎥 Thiết lập dự án
#### 1.📦 Clone Dự án
```bash
(https://github.com/NguyenKhanh04/Nhan-dien-cu-chi-tay-cua-nguoi-khuyet-tat.git)
```
#### 2.📚 Tải các thư viện python cần thiết
```bash
pip install opencv-python mediapipe numpy tensorflow pandas scikit-learn matplotlib pyautogui pygetwindow
```
## 🎥 Cách sử dụng
#### 1️⃣ Chạy chương trình thu thập dữ liệu
```bash
python getdata.py
```
#### 2️⃣ Huấn luyện mô hình
```bash
python train_model.py
```
#### 3️⃣ Chạy chương trình nhận diện cử chỉ
```bash
python hand_run.py
```
## 🖐 Các cử chỉ hỗ trợ
- ✅ **Call** - Màn hình đen (tạm dừng trình chiếu)
- ✅ **Finger_Gun** - Chuyển đến slide đầu tiên
- ✅ **Left** - Quay lại slide trước
- ✅ **OK** - Tiếp tục trình chiếu
- ✅ **Open** - Mở PowerPoint và bắt đầu trình chiếu
- ✅ **Right** - Chuyển slide tiếp theo
- ✅ **Stop** - Thoát trình chiếu
- ✅ **Thumbs_Up** - Chuyển đến slide cuối cùng
## 📌 Ghi chú
- Nhấn **'q'** để thoát chương trình nhận diện.
- Đảm bảo webcam hoạt động bình thường.
## 📝 License

© 2025 **Nhóm 4 - Lớp CNTT 1603** 🎓  
🏫 **Trường Đại học Đại Nam** 

