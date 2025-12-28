# X/Twitter & Multi-Platform Media Downloader Helper

[Vietnamese version below](#-tiếng-việt)

A tool to easily download Podcasts, Videos, and Audio from X (Twitter) and other platforms by converting browser requests into powerful download commands.

## 🚀 Live Demo
Use the tool online here:
**[https://vutien.github.io/download-podcast-x-twitter/](https://vutien.github.io/download-podcast-x-twitter/)**

## 📖 How to Use

### Step 1: Get the curl command
1. Open the video/audio/podcast on X (Twitter) or another platform.
2. Press `F12` to open **Developer Tools**, go to the **Network** tab.
3. Search for `m3u8` or filter by **Fetch/XHR**.
4. Right-click the request containing the m3u8 URL, select **Copy** -> **Copy as cURL (bash)**.

### Step 2: Convert the command
1. Visit the tool link above.
2. Paste the copied curl command into the **Input cURL** box.
3. The tool automatically extracts the URL and necessary Headers.
4. Customize options like: Save directory, file name, thread count, etc.
5. Click **Copy Result**.

### Step 3: Run the download
1. Ensure you have [N_m3u8DL-RE](https://github.com/nilaoda/N_m3u8DL-RE) installed.
2. Open Terminal (or CMD/PowerShell), paste the copied command, and press Enter.

## ✨ Features
- Extracts URL and Headers from cURL automatically.
- Generates clean multi-line commands.
- Modern Glassmorphism UI with Dark Mode support.
- Real-time conversion.

---

# 🇻🇳 Công cụ hỗ trợ tải Video & Audio từ X (Twitter) và đa nền tảng

Dễ dàng tải Podcast, Video, Audio trên X (Twitter) và các nền tảng khác bằng cách chuyển đổi lệnh curl từ trình duyệt thành lệnh tải mạnh mẽ.

## 🚀 Live Demo
Bạn có thể sử dụng tool trực tuyến tại đây:
**[https://vutien.github.io/download-podcast-x-twitter/](https://vutien.github.io/download-podcast-x-twitter/)**

## 📖 Hướng dẫn sử dụng

### Bước 1: Lấy lệnh curl từ trình duyệt
1. Mở nội dung bạn muốn tải trên X (Twitter) hoặc nền tảng khác.
2. Nhấn `F12` để mở **Developer Tools**, chọn tab **Network**.
3. Tìm kiếm từ khóa `m3u8` hoặc lọc theo loại **Fetch/XHR**.
4. Nhấn chuột phải vào request có chứa URL m3u8, chọn **Copy** -> **Copy as cURL (bash)**.

### Bước 2: Chuyển đổi lệnh
1. Truy cập vào trang web của tool (Link ở trên).
2. Dán lệnh curl vừa copy vào ô **Input cURL**.
3. Tool sẽ tự động trích xuất URL và các Headers cần thiết.
4. Tùy chỉnh các thông số như: Thư mục lưu, tên file, số luồng tải (threads)...
5. Nhấn **Copy kết quả**.

### Bước 3: Chạy lệnh tải
1. Đảm bảo bạn đã cài đặt công cụ [N_m3u8DL-RE](https://github.com/nilaoda/N_m3u8DL-RE) trong máy.
2. Mở Terminal (hoặc CMD/PowerShell), dán lệnh vừa copy và nhấn Enter.

## ✨ Tính năng
- Tự động trích xuất URL và Headers từ cURL.
- Tạo lệnh đa dòng (multi-line) dễ quan sát.
- Giao diện hiện đại, hỗ trợ Dark Mode, thiết kế theo phong cách Glassmorphism.
- Tự động chuyển đổi ngay khi dán dữ liệu.

---
Created by **Tien Vu (witi.vn)**
