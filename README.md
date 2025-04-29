# 🚢 Battleship AI - Python Game 🎮

**Battleship AI** là trò chơi hải chiến cổ điển được xây dựng bằng Python, nơi bạn sẽ đối đầu với **trí tuệ nhân tạo (AI)** ở nhiều cấp độ.  
Người chơi có thể tùy chỉnh số lượng tàu, kích thước bàn cờ và tận hưởng trải nghiệm sống động với hiệu ứng âm thanh.

---

## 🎥 Demo
> ![Battleship Gameplay](images/demo.gif)  
> *(Thêm ảnh GIF/video minh họa gameplay nếu có)*


---

## 🧠 Tính năng nổi bật
- 🧩 Chơi với AI có 3 chế độ:
  - **Dễ** – AI chọn ô ngẫu nhiên
  - **Trung bình** – AI có logic dò tìm xung quanh
  - **Khó** – AI sử dụng chiến lược thông minh hơn (xác suất, pattern)
- ⚙️ Tùy chỉnh:
  - Số lượng tàu
  - Kích thước bàn cờ
- 🔊 Hệ thống âm thanh (bắn trúng, bắn hụt, chiến thắng...)
- 👁️ Giao diện người dùng đơn giản, dễ chơi


---

## 🛠️ Công nghệ sử dụng
- `Python 3.x`
- `pygame` (cho giao diện và âm thanh)
- `random` (xử lý AI cơ bản)
- `tkinter` (nếu dùng giao diện đơn giản với cửa sổ)

---

## ⚙️ Cài đặt và chạy game
```bash
# Clone repository
git clone https://github.com/heechanh/GameBattleShip.git
cd GameBattleShip

# Cài đặt pygame nếu chưa có
pip install pygame

# Chạy game
python menu.py
