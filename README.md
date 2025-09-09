# Dự án Thực hành An ninh mạng

Repository này bao gồm các bài thực hành về an ninh mạng, tập trung vào triển khai tường lửa, hệ thống phát hiện xâm nhập và honeypot.  
Các nội dung được thực hiện trong quá trình học tập và thực hành.

---

## 📌 Nội dung

### 1. Triển khai Tường lửa với **Iptables & pfSense**
- Xây dựng các kịch bản lọc gói tin:
  - Cho phép LAN ping ra Internet
  - Cho phép truy vấn DNS từ LAN ra Internet
  - Cho phép truy cập HTTP/HTTPS
  - Cho phép gửi/nhận mail (SMTP/IMAP/POP3)
  - Triển khai **DMZ** cho Web/Mail Server
- Cấu hình chính sách firewall để kiểm soát truy cập giữa mạng nội bộ và Internet.

---

### 2. Hệ thống phát hiện xâm nhập với **Snort**
- Cài đặt và cấu hình rule để phát hiện các tấn công:
  - Quét cổng (Port scanning)
  - Quét dịch vụ
  - ICMP Ping of Death (DoS)
- Thực hành phân tích log và xử lý cảnh báo tấn công.

---

### 3. Honeypot với **HoneyDrive**
- Cài đặt môi trường Honeypot bằng HoneyDrive.  
- Mô phỏng các kịch bản tấn công:
  - Quét IP và dịch vụ
  - SSH brute-force
- Ghi nhận và phân tích hành vi của kẻ tấn công để nâng cao khả năng phòng thủ.

---

## ⚙️ Công nghệ sử dụng
- **Iptables**
- **pfSense**
- **Snort**
- **HoneyDrive**
- Công cụ ảo hóa (VMware/VirtualBox)

---



## 📂 Cấu trúc thư mục
