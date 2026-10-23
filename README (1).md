


# Dự Án Website Cửa Hàng Văn Phòng Phẩm

Dự án phát triển nền tảng **thương mại điện tử** chuyên cung cấp đồ dùng học tập và thiết bị văn phòng, hỗ trợ *tối ưu hóa quy trình bán hàng và quản trị dữ liệu*.

> ⚠️ **Cảnh báo bảo mật:** Tuyệt đối không tải lên hoặc commit file `.env` lên kho lưu trữ để tránh lộ các khóa bí mật và cấu hình hệ thống.

## Cấu trúc thư mục

| Thư mục | Nội dung |
| :--- | :--- |
| data| Lưu trữ file bảng tính Excel chứa danh mục sản phẩm và đơn bán hàng |
| docs| Tài liệu dự án, đặc tả yêu cầu và danh sách nhập hàng |
| media | Chứa hình ảnh, logo nhận diện thương hiệu và tài nguyên đồ họa |
| logs | Nhật ký hoạt động của hệ thống và các báo cáo lỗi trích xuất |
| backup | Bản sao lưu định kỳ của các tài nguyên quan trọng |

## Kiểm tra cấu trúc thư mục
Chạy lệnh sau tại thư mục gốc dự án để xem cấu trúc và toàn bộ file:

```powershell
Get-ChildItem -Recurse -Force
```
## Tiến độ công việc
- [x] Chuẩn hóa tên file theo quy chuẩn snake_case và sắp xếp thư mục
- [x] Lọc danh sách lỗi hệ thống từ log ra báo cáo ngày
- [ ] Hoàn thiện công thức tính học phí/doanh thu trong bảng tính Excel
