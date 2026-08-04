# SalesCost Pro – Bản tách luồng ngân sách và chi phí

Bản cập nhật gồm hai luồng nghiệp vụ độc lập trong module Quy trình:

- Đăng ký ngân sách
- Đăng ký chi phí

Module Tài liệu có danh mục hồ sơ bắt buộc riêng cho từng loại chi phí: chiết khấu nhà phân phối, chiết khấu bán hàng, thưởng nhà phân phối và hội chợ.

## Chạy thử
Mở trực tiếp `index.html` hoặc chạy `npm run dev`.

## Triển khai Vercel
- Framework Preset: Other
- Build Command: `npm run build`
- Output Directory: `dist`

## Cập nhật luồng đăng ký ngân sách
- Ngân sách được phân theo bộ phận.
- Người nộp đơn mặc định là Trần Diệu Hương; bộ phận tự động lấy theo người nộp đơn.
- Chọn kỳ ngân sách: Tháng, Quý hoặc Năm.
- Nội dung tự sinh theo kỳ, ví dụ: Ngân sách tháng 6/2026, Ngân sách quý 2/2026, Ngân sách năm 2027.
