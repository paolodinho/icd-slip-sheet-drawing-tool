# Tool tạo bản vẽ slip sheet từ thông số

Biến thông số slip sheet (chất liệu, màu sắc, độ dày, kích thước lòng trong, số tai kéo, kiểu góc) thành **bản vẽ kỹ thuật chính xác** kèm bảng thông số, xuất ảnh PNG gửi khách hoặc in A4.

## Cách dùng
- Mở `index.html` bằng trình duyệt (double-click, không cần cài gì).
- Nhập thông số bên trái → bấm **Vẽ lại bản vẽ**.
- Bấm **Tải ảnh PNG gửi khách** để xuất ảnh, hoặc **In bản vẽ (A4)**.

## Vì sao chính xác hơn ChatGPT
Bản vẽ là **hình học tham số** (vẽ bằng JavaScript, canvas 2D): nhập 2 tai → luôn ra đúng 2 tai đúng vị trí, chọn kiểu góc nào → ra đúng kiểu góc đó, mỗi lần như nhau. Kích thước, dimension arrows tự tính chính xác theo mm nhập vào.

## Chất liệu & thông số
Bảng thông số (độ dày, g/m2, tải trọng, độ ẩm, ma sát) lấy từ dữ liệu nhà máy thực tế, không tự bịa:
- **Giấy Kraft** — 1 màu vàng nâu, 4 mức độ dày 0.6-1.5mm.
- **Nhựa** — 2 màu: đen (tái sinh - Recycle HDPE) / trắng-xám (nguyên sinh - Virgin HDPE), 4 mức độ dày 0.6-1.2mm mỗi màu.
- **Giấy chống tĩnh điện** — 3 mức trọng lượng 130/160/240g.
- Hỗ trợ nhập độ dày tuỳ chỉnh ngoài bảng có sẵn.

## Tai kéo & kiểu góc
- 0-4 tai kéo (preset nhanh hoặc tick tay từng cạnh).
- 5 kiểu góc khi 2 tai liền kề gặp nhau: vuông / cắt chéo / cắt vuông bậc / bo tròn / khóa góc.

*Tạo 2026-07-24.*
