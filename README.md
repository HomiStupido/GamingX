# GamingX
Giao diện máy chơi game kèm giả lập cho Windows
# 🧩 Mục lục
- [Tải xuống](#-tải-xuống)
- [Cài đặt](#-cài-đặt)
- [Tuỳ chọn sử dụng](#-tuỳ-chọn-sử-dụng)
  - [Dùng với Steam](#1️⃣-dùng-với-steam)
  - [Không dùng Steam](#2️⃣-không-dùng-steam)
- [Thêm game & giả lập](#-thêm-game--giả-lập)
- [Tuỳ chỉnh khởi động và theme](#-tuỳ-chỉnh-khởi-động-và-theme)

---

## 📦 Tải xuống

1. Truy cập mục **[Releases](https://github.com/tên-github-của-bạn/tên-repo/releases)**.
2. Tải bản mới nhất.

---

## ⚙️ Cài đặt

Giải nén thư mục vào **ổ C** (ví dụ: `C:\GamingX`).
> ⚠️ **Lưu ý:** Nên đặt ở ổ C để tránh lỗi đường dẫn khi cấu hình giả lập và Steam.

---

## 🕹️ Tuỳ chọn sử dụng

Người dùng có thể chọn **dùng kèm Steam** hoặc **không dùng Steam** tuỳ nhu cầu.

---

### 1️⃣ Dùng với **Steam**

- Ưu điểm:  
  ✅ Hỗ trợ tay cầm  
  ✅ Có thể map nút tắt game, mở menu, v.v.  
- Nhược điểm:  
  ⏳ Thời gian khởi động lâu hơn một chút

#### Các bước:

1. Tìm **shortcut của Steam** và bỏ vào thư mục `Menu`.
2. Thêm **Playnite Fullscreen** trong `Menu` vào thư viện Steam:
   - Mở Steam → Menu “Add a Non-Steam Game” → chọn `Playnite Fullscreen.lnk`.
3. Tạo **shortcut của Playnite Fullscreen trong Steam** rồi bỏ **vào thư mục Menu** (thay thế 2 file cũ có sẵn).
4. Thêm file **GamingX.lnk** vào **Task Scheduler**  
   - Chọn: `Run only when user is logged on`.

> 💡 Mục tiêu: khi bật máy, hệ thống sẽ tự chạy Steam và Playnite Fullscreen ngay.

---

### 2️⃣ Không dùng Steam

Đơn giản hơn, chỉ cần:

1. Bỏ file `Playnite Fullscreen.lnk` vào **Task Scheduler**  
   - Chọn `Run only when user is logged on`.

Là xong — khi khởi động máy, Playnite Fullscreen sẽ tự bật.

---

## 🎮 Thêm game & giả lập

### Thêm game:
Chỉ cần **chép file game vào thư mục `Games\PC`**.

### Giả lập:
- Mỗi giả lập có thư mục riêng trong `Games\Giả lập\Games`.  
- File game giả lập cần được bỏ đúng chỗ tương ứng.

### Thêm giả lập vào Playnite:
1. Mở **Playnite** (chế độ Desktop).
2. Chọn **Add Game → Scanners → chọn hệ máy bạn muốn**.  
   - Mình đã tích hợp sẵn các scanner cho hệ phổ biến (NES, SNES, PS1, PS2, Switch...).
3. Hệ thống sẽ **tự quét và thêm game vào Playnite**.

---

## 🖼️ Tuỳ chỉnh khởi động và theme

### Màn hình khởi động (Intro):

1. Mở thư mục `Intro`, chọn video bạn muốn làm màn hình mở đầu.
2. Copy và dán video đó vào thư mục `Boost`.
3. Đổi tên video thành **`Video.mp4`** (ghi đè lên video đang có).

> 🎬 Video này sẽ phát trước khi mở Playnite Fullscreen.

---

### Thay theme:

1. Mở **Playnite Fullscreen**.  
2. Vào menu **Settings → Visual → Theme**.  
3. Chọn theme: `Xbox`, `PS5`, `Switch`, v.v.

Đã được cài sẵn 3 theme chính:
- ✅ Xbox Style  
- ✅ PlayStation 5 Style  
- ✅ Nintendo Switch Style  

Muốn thêm theme mới:
1. Mở **Playnite bản màu vàng (Desktop)**.  
2. Chọn icon **Playnite** góc trái → **Add-ons → Theme (Fullscreen)**.  
3. Tìm và tải theme bạn muốn.  
4. Quay lại Playnite Fullscreen → **Settings → Visual → Theme → chọn theme mới**.
