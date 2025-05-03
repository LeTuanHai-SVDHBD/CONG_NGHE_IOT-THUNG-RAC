# ĐỀ TÀI: THÙNG RÁC THÔNG MINH

# Platform triển khai: FUXA thông qua giao thức MQTT

# CONG_NGHE_IOT-THUNG-RAC
## Nhóm 4 (Sáng thứ 7):
--------------------------------------------
### Lê Tuấn Hải - 23050116
### Nguyễn Minh Cang - 23050120
--------------------------------------------
## Nội Dung Trong File 
### Tài Liệu Code Arduino
### Docker Compose
#### docker-compose.yml (File cấu hình Docker Compose)
→ Cấu hình Docker Compose để triển khai Mosquitto Broker và các dịch vụ khác qua Docker.
#### Thư Mục: config/ (Thư mục Docker volume)
→ Chứa config, dữ liệu và log nếu chạy Mosquitto bằng Docker.

---------------------------------------------
### - fuxa-devices.json (File của FUXA)
→ File chứa thông tin cấu hình thiết bị cho FUXA
### - Thư Mục: mosquitto/ & Các File: .exe, .dll, .conf (File Mosquitto tải về từ web)
→ Dùng để chạy Mosquitto broker trực tiếp trên Windows.
