# SalesCost Pro – Bản cập nhật cấu trúc menu

## Điều chỉnh chính
- Không tách Chính sách chiết khấu, Chương trình bán hàng và Ngân sách thành module riêng.
- Ba nhóm dữ liệu này được quản lý tập trung trong trang Dữ liệu gốc.
- Đổi module Phê duyệt thành Đăng ký.
- Giữ phần ngân sách theo tháng tại Tổng quan và trong Dữ liệu gốc.

## Chạy thử
Mở `index.html` trực tiếp hoặc chạy:

```bash
npm run dev
```

## Triển khai Vercel
- Framework Preset: Other
- Build Command: `npm run build`
- Output Directory: `dist`


## Cập nhật quy trình
- Module Đăng ký đổi thành Quy trình.
- Trạng thái: Tạo mới → Chờ phê duyệt → Đã phê duyệt → Đang thực hiện → Chờ bổ sung hồ sơ → Hoàn thành.
- Hỗ trợ phê duyệt nhiều cấp.
- Module Hồ sơ & chứng từ đổi thành Tài liệu.
