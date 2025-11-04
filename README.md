# Cheat Safe Exam Browser bằng máy ảo 👇

## 🔹 **Bước 1: Chuẩn bị máy ảo**

* Tải và cài đặt phần mềm máy ảo (VMware hoặc VirtualBox đều được, QUAN TRỌNG: PHẢI NHỞ CÀI MÁY ẢO Ở ĐÂU).
* Tải về **file ISO** của hệ điều hành tùy ý (Windows 10/11,...).

> ⚠️ Lưu ý: Chỉ cần hệ điều hành có **trình duyệt web (Google Chrome, Edge, v.v.)** để tải file từ GitHub này là được.


## 🔹 **Bước 2: Cấu hình mạng cho máy ảo**

* Sau khi tạo máy ảo xong, mở phần **Network settings** và cấu hình như hình minh họa dưới đây 👇
  
<img width="1920" height="1080" alt="Network" src="https://github.com/user-attachments/assets/ab8cb243-b879-4d19-a617-728f81173191" />

> 💡 Mục tiêu: Đảm bảo máy ảo có thể **truy cập Internet ổn định** để tải file và cập nhật.


## 🔹 **Bước 3: Giải nén và cài đặt Safe Exam Browser**

* Giải nén thư mục đã tải về ở **Bước 2**.
* Trong thư mục đó, chạy file cài đặt **Safe Exam Browser** và làm theo hướng dẫn.


## 🔹 **Bước 4: Chỉnh sửa file `.vmx`**

* Mở file `.vmx` của máy ảo bằng trình soạn thảo (Notepad hoặc VS Code) trong thư mục đã cài MÁY ẢO Ở BƯỚC 1 (BƯỚC NÀY Ở MÁY THẬT).
* Tìm dòng đường dẫn tới file ISO và **thay bằng đường dẫn ISO của bạn**, ví dụ:

  ```text
  ide1:0.fileName = "D:\Tuan\Win10_22H2_English_x64v1.iso"
  ```
* Lưu lại thay đổi.

## 🔹 **Bước 5: Khởi động lại máy ảo**

* Restart máy ảo để cập nhật cấu hình.
* Hoàn tất! 🎉

👉 Bây giờ bạn đã có thể chấp mọi bài thi có Safe Exam Browser 
