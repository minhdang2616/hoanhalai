# Hoa Nhà Lài

Trang demo bán hoa một trang, dùng HTML, CSS và JavaScript thuần.

Mở `hoa.html` để xem. Font và ảnh minh họa tải từ Internet.

Cloudflare Workers: cấu hình `wrangler.toml` trỏ static assets vào thư mục `site/`. Dùng lệnh deploy `npx wrangler deploy`; không cần build command. URL `/` và `/hoa` sẽ chuyển đến `/hoa.html`.

Sản phẩm, thông tin liên hệ và form đặt hoa chỉ là dữ liệu demo, chưa kết nối backend.
