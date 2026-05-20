# 🎈 Balloon Game - Chinh phục bầu trời

Chào mừng bạn đến với **Balloon Game** – một trò chơi né tránh chướng ngại vật đòi hỏi sự tập trung và phản xạ nhanh nhạy. Bạn sẽ điều khiển một chiếc khinh khí cầu vượt qua những hiểm nguy lơ lửng trên bầu trời.

## 🕹️ Cách chơi chi tiết
Trò chơi được thiết kế để bạn làm chủ khinh khí cầu một cách dễ dàng:
* **Di chuyển:** Ở phần dưới cùng của màn hình, bạn sẽ thấy hai nút bấm chuyên dụng: **◀ (Trái)** và **▶ (Phải)**. Chỉ cần nhấn (hoặc giữ) các nút này để điều hướng khinh khí cầu né tránh các chướng ngại vật từ trên rơi xuống.
* **Quy luật sinh tồn:**
    * **Chướng ngại vật (Gai):** Nếu khinh khí cầu va chạm phải bất kỳ gai nào, trò chơi sẽ kết thúc ngay lập tức.
    * **Thu thập điểm số:** Trên đường đi, hãy cố gắng "hứng" các quả cầu xuất hiện ngẫu nhiên. Mỗi loại quả cầu sẽ mang lại hiệu ứng khác nhau.

## 🌈 Các vật phẩm hỗ trợ (Power-ups)
Đừng chỉ né tránh, hãy tận dụng các quả cầu để đạt điểm cao hơn:
* **Quả cầu bình thường (Xanh):** Cộng trực tiếp điểm số vào tài khoản của bạn.
* **Nam châm (Magnet - Vàng/Đỏ):** Kích hoạt khả năng hút tất cả các quả cầu trong phạm vi gần, giúp bạn thu thập tài nguyên nhanh chóng.
* **Cầu vồng (Rainbow):** Đây là vật phẩm đặc biệt! Khi chạm vào, bạn sẽ bước vào "Rainbow Mode" – khinh khí cầu của bạn sẽ tỏa sáng rực rỡ và ghi điểm thưởng lớn liên tục trong một khoảng thời gian nhất định.

## 🛠 Công nghệ & Đặc điểm kỹ thuật
Balloon Game được xây dựng với sự tối ưu hóa cao độ:
* **Lõi Engine:** Sử dụng `HTML5 Canvas` để dựng hình và `JavaScript` để quản lý luồng game (Game Loop) cực mượt mà.
* **Cơ chế va chạm:** Hệ thống kiểm tra khoảng cách giữa tâm khinh khí cầu và vật thể (`Math.sqrt`) được tính toán chính xác để đảm bảo độ công bằng.
* **Độ khó tăng dần:** Dựa trên thời gian sống sót của người chơi (`difficulty = 1 + elapsed / 40`), game sẽ tự động tăng tốc độ rơi của vật thể, khiến thử thách trở nên gay cấn hơn theo thời gian.
* **Tối ưu trải nghiệm:** Giao diện `Glassmorphism` kết hợp cùng khả năng lưu trữ cài đặt (`localStorage`) cho phép game ghi nhớ chế độ tối (Dark Mode) của bạn mỗi lần quay lại.

## 🖥️ Mẹo để có trải nghiệm "Pro"
Để không bị vướng bởi giao diện trình duyệt, hãy biến nó thành một ứng dụng riêng biệt:
1. **Trên trình duyệt (Chrome/Edge):** Nhấn **(⋮)** > **Lưu và chia sẻ** > **Cài đặt trang này dưới dạng ứng dụng**.
2. **Phím tắt:** Nhấn **F11** (Windows) hoặc **Control + Command + F** (macOS) để vào chế độ toàn màn hình tức thì.

---
*Phát triển bởi **Oops Hano (Oka Hiru)**. Hãy cùng xem bạn có thể tồn tại được bao lâu trước khi độ khó lên đến đỉnh điểm nhé!*
