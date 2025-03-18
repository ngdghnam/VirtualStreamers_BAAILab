# HƯỚNG DẪN CHẠY N8N MIỄN PHÍ TRÊN LOCALHOST

## 1. CÀI ĐẶT NODE.JS

Để chạy n8n, trước tiên cần cài đặt Node.js.

- Link tải Node.js: [Tải tại đây](https://nodejs.org/en/download)
- Sau khi cài đặt xong, mở terminal và chạy lệnh sau để kiểm tra phiên bản Node.js:
  ```sh
  npm -v
  ```

## 2. CÀI ĐẶT N8N

Cài đặt n8n bằng npm theo hướng dẫn chính thức:

- Chi tiết tham khảo tại: [docs.n8n.io](https://docs.n8n.io/hosting/installation/npm/)
- Cài đặt n8n bằng terminal:
  ```sh
  npm install n8n -g
  ```
- Sau khi cài đặt xong, chạy n8n bằng một trong hai lệnh sau:
  ```sh
  n8n
  ```
  hoặc
  ```sh
  n8n start
  ```
- Mở trình duyệt và truy cập vào: [localhost:5678](http://localhost:5678)

## 3. ĐĂNG KÝ TÀI KHOẢN

- Khi truy cập `localhost:5678`, màn hình đăng ký sẽ xuất hiện.
- Nhập thông tin tài khoản và email để tạo tài khoản.
- N8N sẽ gửi một email chứa **activate-key** (dùng để kích hoạt tài khoản).
- Sau khi kích hoạt, có thể sử dụng n8n bình thường.

## 4. CÁCH TẮT MÁY CHẠY N8N

- Nhấn `Ctrl + C` trên terminal để dừng dịch vụ n8n.

## 5. IDE SỬ DỤNG

- Khuyến nghị sử dụng **Visual Studio Code (VSCode - màu xanh)** để chỉnh sửa và phát triển workflow.

---
