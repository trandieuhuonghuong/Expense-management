# SalesCost Pro – Ngân sách theo hạng mục

Bản cập nhật bổ sung kiểm soát ngân sách theo hạng mục và liên kết bắt buộc giữa chi phí với ngân sách.

## Chức năng mới

- Ngân sách được quản lý theo bộ phận, hạng mục và kỳ tháng/quý/năm.
- Luồng đăng ký ngân sách yêu cầu chọn hạng mục.
- Luồng điều chỉnh ngân sách chọn trực tiếp ngân sách hạng mục cần tăng/giảm.
- Đăng ký chi phí bắt buộc chọn ngân sách tương ứng.
- Chỉ hiển thị ngân sách cùng loại chi phí còn số dư.
- Không cho lưu chi phí vượt số dư ngân sách của tháng/quý/năm và hạng mục tương ứng.
- Khi tạo chi phí, số tiền được ghi nhận vào phần đã sử dụng của ngân sách liên kết.

## Chạy thử

Mở `index.html` hoặc chạy:

```bash
npm run build
```

Triển khai Vercel với Output Directory là `dist`.
