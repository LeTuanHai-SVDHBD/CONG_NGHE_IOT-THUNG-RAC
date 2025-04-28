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
#### - Thư Mục: mosquitto (Chi Tiết)
##### mosquitto.exe	
→ File chạy Mosquitto server (broker chính).
##### mosquitto_ctrl.exe	
→ Công cụ điều khiển broker (quản lý security, các rule động).
##### mosquitto_pub.exe	
→ Công cụ gửi (publish) tin nhắn MQTT.
##### mosquitto_sub.exe	
→ Công cụ nhận (subscribe) tin nhắn MQTT.
##### mosquitto_rr.exe	
→ Công cụ gửi request/nhận reply MQTT.
##### mosquitto_passwd.exe	
→ Dùng để tạo file username/password cho xác thực broker.
##### mosquitto_dynamic_security.dll	
→ Thư viện hỗ trợ dynamic security (quản lý người dùng và quyền).
##### mosquitto.dll	
→ Thư viện động cho các chương trình sử dụng MQTT client.
##### mosquittopp.dll	
→ Thư viện động cho MQTT theo hướng lập trình đối tượng (C++).
##### mosquitto.conf	
→ File cấu hình server Mosquitto (port, xác thực, quyền...).
##### acfile.example	
→ File ví dụ cho Access Control List (ACL) - phân quyền người dùng.
##### pwfile.example	
→ File ví dụ cho danh sách user/password.
##### libcrypto-3-x64.dll	
→ Thư viện OpenSSL hỗ trợ mã hóa bảo mật.
##### libssl-3-x64.dll	
→ Thư viện OpenSSL hỗ trợ giao tiếp SSL/TLS.
##### README.md, NOTICE.md, README-letsencrypt.md, README-windows.txt	
→ Các file hướng dẫn sử dụng, thông tin bản quyền và cấu hình.
##### ChangeLog.txt	
→ Ghi chú các thay đổi theo từng phiên bản Mosquitto.
##### cdl-v10, epl-v20	
→ File giấy phép sử dụng phần mềm (license).
##### devel/	
→ Thư mục chứa tài nguyên cho nhà phát triển (developer).
##### devel/ (Chi Tiết)
###### mosquittopp.lib, mosquitto.lib	
→ Thư viện dạng .lib để lập trình C/C++ liên kết (link) với Mosquitto (Static Linking).
###### mosquitto.h, mosquitto_broker.h, mosquitto_plugin.h, mosquittopp.h, mqtt_protocol.h	
→ Các file header (.h) để bạn lập trình ứng dụng C/C++ dùng Mosquitto API.
##### Uninstall.exe	
→ Công cụ gỡ cài Mosquitto khỏi máy.

