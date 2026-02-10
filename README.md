# Pickleball Quote Generator

 một ứng dụng web đơn giản để tạo và quản lý báo giá đặt sân Pickleball.

## Tính năng

-   **Quản lý dịch vụ**: Thêm, sửa, xóa các dòng dịch vụ (Sân, Giờ, Giá).
-   **Cộng dồn thông minh**: Tự động cộng dồn số lượng thời gian nếu trùng ngày và dịch vụ.
-   **Tính toán tự động**: Tự động tính thành tiền và tổng tiền.
-   **Lưu trữ cục bộ**: Dữ liệu được lưu trong LocalStorage của trình duyệt, không bị mất khi tải lại trang.
-   **In ấn chuyên nghiệp**: Chế độ in (Ctrl+P) ẩn các nút bấm, chỉ hiện hóa đơn.
-   **Chỉnh sửa trực tiếp**: Có thể sửa tên khách hàng, số điện thoại, và thông tin ngân hàng trực tiếp trên giao diện.

## Cách sử dụng

1.  Mở trang web.
2.  Nhấn nút **"+ Thêm dòng"** để nhập thông tin đặt sân.
3.  Nhập thông tin Ngày, Giờ, Dịch vụ... và nhấn **Lưu**.
4.  Nhấn vào tên khách hàng hoặc thông tin ngân hàng để sửa nếu cần.
5.  Nhấn **Ctrl + P** để in hoặc lưu dưới dạng PDF.

## Cài đặt (Dành cho lập trình viên)

Dự án này là một file HTML đơn (`index.html` trong thư mục `dist`) kèm theo hình ảnh `qr.png`. Không cần cài đặt phức tạp.

## Deployment

Trang web này được thiết kế để chạy trên GitHub Pages.
Vào **Settings** > **Pages** > Chọn branch **main** > Chọn folder **/dist** (hoặc root) > **Save**.
