# SalesCost – Quản lý chi phí bán hàng

Bản web mẫu quản lý chi phí bán hàng, chính sách chiết khấu, chương trình, đề nghị chi phí, hồ sơ chứng từ và báo cáo.

## Chạy trên máy tính

Có thể mở trực tiếp file `index.html`, hoặc chạy:

```bash
npm run dev
```

Sau đó mở `http://localhost:3000`.

## Đưa lên GitHub

Tải toàn bộ **các file bên trong thư mục này** lên thư mục gốc của repository. File `package.json` và `index.html` phải nằm ngay ở cấp đầu tiên, không để lồng thêm một thư mục khác.

## Đưa lên Vercel

1. Chọn **Add New → Project**.
2. Import repository GitHub.
3. Framework Preset: **Other**.
4. Root Directory: để trống nếu các file nằm ở thư mục gốc.
5. Build Command: `npm run build`.
6. Output Directory: `dist`.
7. Chọn **Deploy**.

## Lưu ý

Đây là bản demo giao diện dùng dữ liệu mẫu. Chưa kết nối cơ sở dữ liệu, đăng nhập hoặc lưu file thực tế. Giai đoạn tiếp theo có thể kết nối Supabase để đồng bộ tài khoản, dữ liệu và hồ sơ giữa nhiều thiết bị.
