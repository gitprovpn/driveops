# DriveOps Cloud Web Demo

Demo tĩnh dùng để trải nghiệm trước trên website mobile và PC.

## Đăng nhập

- Username: `test`
- Password: `test`

## Chạy local

Mở trực tiếp file `index.html`, hoặc chạy:

```bash
python -m http.server 8080
```

Sau đó mở `http://localhost:8080`.

## Deploy GitHub Pages

1. Tạo repository mới, ví dụ `driveops-demo`.
2. Upload toàn bộ nội dung thư mục này lên repo.
3. Vào `Settings` → `Pages`.
4. Source chọn `Deploy from a branch`.
5. Branch chọn `main`, folder chọn `/root`.
6. Mở link GitHub Pages được cấp.

## Deploy Cloudflare Pages

1. Vào Cloudflare Dashboard → Workers & Pages → Create application → Pages.
2. Connect GitHub repo chứa source này.
3. Framework preset: `None` hoặc `Static HTML`.
4. Build command: để trống.
5. Output directory: `/`.
6. Deploy.

## Cấu trúc

```text
index.html
styles.css
app.js
assets/screens/*.png
```

Bản demo dùng dữ liệu giả lập theo các màn hình đã thiết kế: Student App, Teacher App, Academic Staff, Exam, Sales, Accounting, Vehicle, Director, Architecture và Gallery ảnh mockup.
