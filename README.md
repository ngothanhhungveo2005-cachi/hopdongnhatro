# Hợp đồng thuê trọ – quét CCCD tự điền

Trang web một file (`index.html`), chạy trên iPhone, Android và máy tính. Chụp hoặc chọn ảnh CCCD của khách thuê, hợp đồng tự điền họ tên, ngày sinh, số CCCD, ngày cấp, nơi cấp, nơi thường trú rồi tải về file Word (.docx).

- Đọc mã QR trên CCCD gắn chip / Thẻ căn cước ngay trên máy. Ảnh CCCD không được tải đi đâu.
- Không cần máy chủ, không cần mạng sau khi mở trang (thư viện đã nhúng sẵn).
- Điều khoản: thuê tối thiểu 6 tháng (chỉnh được), trả phòng sớm thì mất cọc.

## Đăng lên GitHub Pages

1. Tạo repo mới trên GitHub, tải lên 3 file: `index.html`, `README.md`, `.nojekyll`.
2. Vào **Settings → Pages**. Ở mục Source chọn **Deploy from a branch**, nhánh `main`, thư mục `/ (root)`, bấm Save.
3. Sau 1–2 phút, trang có địa chỉ `https://<tên-github>.github.io/<tên-repo>/`.
4. Trên iPhone mở địa chỉ đó bằng Safari, bấm Chia sẻ → **Thêm vào Màn hình chính**.

## Thiết lập lần đầu

Mở trang, vào mục **Bên cho thuê (Bên A)**, nhập thông tin chủ nhà, chỉnh giá thuê và điều khoản, rồi bấm **Lưu Bên A và điều khoản làm mặc định**. Dữ liệu này chỉ nằm trong trình duyệt của máy đó, không nằm trong repo.

## Lưu ý

- Không ghi số CCCD hay thông tin cá nhân vào `index.html` trước khi đưa lên repo công khai.
- Quét QR được trên CCCD gắn chip và Thẻ căn cước. Thẻ cũ không có QR thì nhập tay.
- Mẫu hợp đồng chỉ mang tính tham khảo, nên có người hiểu pháp lý xem lại trước khi dùng lâu dài.
