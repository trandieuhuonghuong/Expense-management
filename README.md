# SalesCost Pro – Bản final chạy trên Vercel

## Module đầy đủ
- Tổng quan
- Dữ liệu gốc
- Doanh thu
  - Doanh thu mục tiêu
  - Báo cáo bán hàng
- Chi phí
  - Ngân sách và điều chỉnh ngân sách
  - Đăng ký chi phí theo ngân sách/hạng mục
  - Phê duyệt: người nộp đơn → trưởng bộ phận → tài vụ
- Tài liệu
  - Liên kết một hoặc nhiều chi phí trong cùng bộ tài liệu
  - Danh mục hồ sơ bắt buộc theo từng loại chi phí
  - Tải nhiều tệp, kiểm tra, hoàn trả và phê duyệt
  - Chi phí chỉ hoàn thành khi toàn bộ hồ sơ bắt buộc đã được phê duyệt
- Báo cáo
- Cấu hình

## Sửa lỗi triển khai
Bản này đã thêm cấu hình SPA cho Vercel. Các đường dẫn như `/file`, `/revenue`, `/cost`, `/reports` đều mở trực tiếp được và không còn lỗi 404.

## Đưa lên Vercel
1. Xóa toàn bộ file cũ trong repository hoặc tạo repository mới.
2. Tải toàn bộ file bên trong thư mục này lên thư mục gốc.
3. Vercel: Framework Preset `Other`.
4. Build Command: `npm run build`.
5. Output Directory: `dist`.
6. Deploy lại và nên chọn Clear build cache nếu đang cập nhật project cũ.
