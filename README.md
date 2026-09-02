# 🤖 Phicomm R1 - Loa Trợ Lý Ảo Thông Minh

Chào mừng bạn đến với phần mềm biến loa Phicomm R1 thành một trợ lý ảo AI thông minh!

Chỉ cần cắm điện và kết nối Wi-Fi, loa sẽ sẵn sàng lắng nghe, trò chuyện, mở nhạc và phục vụ bạn hằng ngày.

---

## 🚀 Cài Đặt (Installation)

**V1.0.4**:
```sh
wget -qO- https://github.com/thuonglt/phicomm-r1-ai-assistant/releases/download/v1.0.4/setup-r1.shssss | sh
```
📺 **Video hướng dẫn chi tiết:** *[https://www.youtube.com/watch?v=xqwhQPWjLs4](https://www.youtube.com/watch?v=xqwhQPWjLs4)*

[![Hướng dẫn cài đặt](https://img.youtube.com/vi/xqwhQPWjLs4/maxresdefault.jpg)](https://www.youtube.com/watch?v=xqwhQPWjLs4)

---

## ✨ Tính Năng Nổi Bật

- 🗣️ **Trò chuyện cùng AI:** Hỏi đáp, tâm sự, nhờ tư vấn mọi chủ đề bằng tiếng Việt tự nhiên.
- 🎵 **Mở nhạc bằng giọng nói:** Chỉ cần nói *"Mở bài hát..."* hoặc *"Mở nhạc của..."*, loa sẽ tự tìm và phát nhạc chất lượng cao.
- ⏰ **Báo thức thông minh:** Đặt báo thức bằng giọng nói hoặc giao diện web, tự phát bài hát yêu thích khi báo thức.
- 🌐 **Tra cứu thông tin trực tuyến:** Tìm kiếm thời tiết, tin tức, giá vàng, tỷ số bóng đá theo thời gian thực.
- 📱 **Giao diện Web Dashboard:** Mở trình duyệt gõ `http://phicomm-r1.local:8080` (hoặc IP của loa) để chọn bài, chỉnh âm lượng, đặt báo thức và cấu hình loa.
- 🎧 **Chế độ Loa Bluetooth:** Bấm nút 3 lần hoặc nói *"Bật Bluetooth"* để biến thành loa Bluetooth thông thường.
- 💡 **Đèn LED thông minh:** Đèn đổi màu trực quan khi loa đang nghe, đang suy nghĩ hoặc phát biểu.
- 🔘 **Thao tác nút bấm đỉnh loa:**
  - **Bấm 1 lần:** Gọi AI / Ngắt lệnh / Tắt báo thức.
  - **Bấm 3 lần:** Bật / tắt chế độ Bluetooth.
  - **Giữ 6 giây:** Bật chế độ phát Wi-Fi để đổi mạng mới.

---

## 🔑 Hướng Dẫn Cấu Hình Web Search API (Tìm Kiếm Trực Tuyến)

Để trợ lý ảo có thể tra cứu thông tin mới nhất trên Internet (như tin tức hôm nay, thời tiết, giá cả...), bạn có thể cấu hình API tìm kiếm miễn phí theo các bước sau:

### 1. Lấy API Key miễn phí
Bạn có thể chọn 1 trong 2 dịch vụ sau (hoặc nhập cả hai):
- **Tavily (Khuyên dùng):** Truy cập [tavily.com](https://tavily.com), đăng ký tài khoản miễn phí và sao chép API Key (có dạng `tvly-...`).
- **Serper:** Truy cập [serper.dev](https://serper.dev), đăng ký tài khoản miễn phí để nhận API Key.

### 2. Cài đặt vào Loa
1. Kết nối cùng mạng Wi-Fi với loa, mở trình duyệt và truy cập: `http://phicomm-r1.local:8080` (hoặc địa chỉ IP của loa).
2. Chuyển sang tab **AI**.
3. Cuộn xuống mục **Web Search API Keys**, dán key đã lấy vào ô **Tavily API Key** hoặc **Serper API Key**.
4. Nhấn nút **Lưu cấu hình API**.

### 3. Trải nghiệm
Bây giờ bạn có thể thử hỏi loa những câu hỏi cần dữ liệu trực tuyến:
- *"Giá vàng hôm nay bao nhiêu?"*
- *"Thời tiết Hà Nội hôm nay thế nào?"*
- *"Tin tức công nghệ nổi bật gần đây là gì?"*
