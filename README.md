<h1 align="center">🚀 Hệ thống nhận diện cử chỉ tay của người khuyết tật !🖐 </h1>
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
- Ghi lại video cử chỉ tay và lưu vào file CSV.
- Khi camera hiển thị lên màn hình và nhận diện các cử chỉ được lưu sẵn trước đó.

## 📥 Cài đặt

### 🛠 Điều kiện cần & đủ

- 🐍 **Python** `3.7+` - Ngôn ngữ lập trình python
- 💾 **RAM** `8GB+` - Được đề xuất cho hiệu suất tối ưu
- 🖥 **CPU** `4+ cores` - Để xử lý song song
- 📷 **Webcam** - Để sử dụng tính năng nhận diện cử chỉ ( **Webcam** hoặc **Camera** hoạt động tốt )


## 🎥 Thiết lập dự án
#### 1.📦 Clone Dự án
```bash
git clone https://github.com/NguyenKhanh04/Nhan-dien-cu-chi-tay-cua-nguoi-khuyet-tat.git
```
#### 2.📚 Tải các thư viện python cần thiết
```bash
pip install opencv-python mediapipe numpy tensorflow pandas scikit-learn matplotlib
```
## 🎥 Cách sử dụng
#### 1️⃣ Huấn luyện mô hình
```bash
python train_model.py
```
#### 2️⃣ Chạy chương trình nhận diện cử chỉ
```bash
python hand_run.py
```
## 📝 License

© 2025 **Nhóm 4 - Lớp CNTT 16-03** 🎓  
🏫 **Trường Đại học Đại Nam** 

