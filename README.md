# GamingX
Giao diện máy chơi game kèm giả lập cho Windows
Tui đã có thể bán nó để lấy tiền nhưng tui không, vậy nên bạn có thể ủng hộ tui qua: https://ganknow.com/homii/tip

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

# ⚙️ Cài đặt

Giải nén thư mục vào **ổ C** (ví dụ: `C:\GamingX`).

> ⚠️ **Lưu ý:**
> - Nên đặt ở ổ C để tránh lỗi đường dẫn khi cấu hình giả lập và Steam.  
> - Cài file `VC_redist.x64.exe` (có sẵn trong thư mục) để giả lập hoạt động ổn định. Bạn có thể xóa sau khi cài xong.

---

## 🕹️ Tuỳ chọn sử dụng

Bạn có thể chọn **dùng kèm Steam** hoặc **không dùng Steam** tuỳ theo nhu cầu.

---

### 1️⃣ Dùng với **Steam**

- Ưu điểm:  
  ✅ Hỗ trợ tay cầm  
  ✅ Có thể map nút tắt game, mở menu, v.v.  
- Nhược điểm:  
  ⏳ Thời gian khởi động lâu hơn một chút

#### Các bước:

. Tìm **shortcut của Steam** và bỏ vào thư mục `Menu` (thay thế file `steam.lnk` cũ).  
2. Thêm **Playnite Fullscreen** trong `Menu` vào thư viện Steam:
   - Steam → Add a Non-Steam Game → chọn `Playnite Fullscreen.lnk`.  
   - Đổi tên shortcut trong Steam thành **Playnite Fullscreen**.
3. Tạo **shortcut của Playnite Fullscreen trong Steam** rồi bỏ vào thư mục `Menu` (thay thế file cũ).  
4. Thêm file **GamingX.lnk** vào **Task Scheduler**  
   - Chọn: `Run only when user is logged on`.

> 💡 Mục tiêu: khi bật máy, hệ thống sẽ tự mở Steam và Playnite Fullscreen.

---

### 2️⃣ Không dùng Steam

Đơn giản hơn, chỉ cần:

1. Bỏ file `Playnite Fullscreen.lnk` vào **Task Scheduler**  
   - Chọn `Run only when user is logged on`.

Là xong — khi khởi động máy, Playnite Fullscreen sẽ tự bật.

---

## 🎮 Thêm game & giả lập

### Thêm game
Chỉ cần **chép file game vào thư mục `Games\PC`**.

### Giả lập
- Mỗi giả lập có thư mục riêng trong `Games\Giả lập\Games`.  
- File game giả lập cần được bỏ đúng chỗ tương ứng.

### Thêm giả lập vào Playnite
1. Mở **Playnite (chế độ Desktop)**.  
2. Chọn **Add Game → Scanners → hệ máy bạn muốn**.  
   - Đã tích hợp sẵn các scanner cho NES, SNES, PS1, PS2, Switch...  
3. Hệ thống sẽ tự quét và thêm game vào Playnite.

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
