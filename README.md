# Hoa Nhà Lài

Trang demo bán hoa một trang, dùng HTML, CSS và JavaScript thuần.

Cloudflare Workers: `wrangler.toml` khai báo `site/` làm thư mục static assets. Lệnh deploy là `npx wrangler deploy`; không cần build command. `site/index.html` phục vụ domain gốc; `site/hoa.html` cũng có thể mở trực tiếp.

Font và ảnh minh họa tải từ Internet. Sản phẩm, thông tin liên hệ và form đặt hoa hiện là dữ liệu demo, chưa kết nối backend.
