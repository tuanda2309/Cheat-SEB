[English](#english) | [Tiếng Việt](#tiếng-việt)


# English

# Cheat Safe Exam Browser using Virtual Machine

## 🔹 Step 1: Prepare a Virtual Machine

* Download and install a virtual machine software (**VMware** or **VirtualBox**).  
* **IMPORTANT:** Remember where your VM is installed — especially the folder containing the `.vmx` file.  
* Download an **ISO file** for your preferred OS (Windows 10/11, etc.).

> Tip: You just need an OS with a **web browser (Chrome, Edge, etc.)** to download files from GitHub.


## 🔹 Step 2: Configure Network Settings

* After creating the VM, open **Network Settings** and configure as shown below 👇  

<img width="1920" height="1080" alt="Network" src="https://github.com/user-attachments/assets/ab8cb243-b879-4d19-a617-728f81173191" />

>💡Goal: Ensure the virtual machine has **stable Internet access** for downloading and updating files.


## 🔹 Step 3: Extract and Install Safe Exam Browser

* Extract the folder you downloaded in **Step 2**.  
* Inside that folder, run the **Safe Exam Browser installer** and follow the setup instructions.


## 🔹 Step 4: Edit the `.vmx` File

* Open your VM’s `.vmx` file using **Notepad** or **VS Code** (on the **host machine**, not the VM).  
* Locate the line pointing to your ISO file and replace it with your correct path, for example:

  ```text
  ide1:0.fileName = "D:\Tuan\Win10_22H2_English_x64v1.iso"
  ```

* Save changes.

## 🔹 **Step 5: Restart the virtual machine**

* Restart the virtual machine to update the configuration.
* Done! 🎉

👉 You can now accept any exam with Safe Exam Browser

# Tiếng Việt

# Cheat Safe Exam Browser bằng máy ảo 👇

## 🔹 **Bước 1: Chuẩn bị máy ảo**

* Tải và cài đặt phần mềm máy ảo (VMware hoặc VirtualBox đều được, QUAN TRỌNG: PHẢI NHỚ CÀI MÁY ẢO Ở ĐÂU, Ở THƯ MỤC NÀO, ĐỂ DỄ TÌM FILE .VMX).
* Tải về **file ISO** của hệ điều hành tùy ý (Windows 10/11,...).

> Lưu ý: Chỉ cần hệ điều hành có **trình duyệt web (Google Chrome, Edge, v.v.)** để tải file từ GitHub này là được.


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
