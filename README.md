# Mẫu quản lý bán hàng cho cửa hàng, tạp hóa, quán ăn

Ba mẫu bảng tính bằng Excel, dùng ngay cho cửa hàng nhỏ, tạp hóa, quán ăn,
tiệm giặt sấy và quán cafe. Tải về, mở bằng Excel hoặc Google Trang tính là
dùng được ngay. Không cần đăng ký, không cần để lại số điện thoại.

## Mẫu trong repo này

| File | Dùng cho | Cột chính |
|---|---|---|
| `bang-tinh-gia-von.csv` | Tính lãi gộp từng món | Giá nhập, định lượng, giá vốn, giá bán, lãi gộp |
| `mau-bien-nhan-giat.csv` | Tiệm giặt sấy ghi đơn nhận | Mã đơn, ngày nhận, số ký, loại giặt, ngày hẹn trả |
| `bang-cham-gio-ca.csv` | Chấm giờ ca nhân viên | Giờ vào, giờ ra, tổng giờ, doanh thu ca |

## Cách dùng

### Bảng tính giá vốn món

Nhập giá nhập và định lượng nguyên liệu cho một phần ăn, bảng ra giá vốn và
lãi gộp từng món. Nếu giá nhập thay đổi, sửa cột giá nhập là các dòng phía
dưới tự cập nhật.

### Mẫu biên nhận giặt

Mỗi món giặt một dòng. Mã đơn nên dán tem lên từng món, lúc trả khách quét
mã đối chiếu với bảng để khỏi nhầm.

### Bảng chấm giờ ca

Mỗi ngày một dòng cho mỗi người. Tổng giờ nên tính bằng công thức để không
phải cộng tay.

## Muốn dùng ở nhiều máy, theo dõi tồn kho và doanh thu tự động?

Website chính thức có hướng dẫn cho từng ngành và các mẫu mới:
https://www.biz-vn.com/tai-lieu/

Bài hướng dẫn theo ngành: https://www.biz-vn.com/blog/

## Ghi chú

- File `.csv` mở bằng Excel trên Windows có thể hiện lỗi dấu tiếng Việt nếu
  chưa bật UTF-8. Vào **Dữ liệu → Từ Text/CSV**, chọn mã hóa **UTF-8**.
- Hoặc mở bằng Google Trang tính, không cần cài gì.
