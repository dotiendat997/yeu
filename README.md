# Quà 20/10 cho vợ

Trang quà tặng cá nhân, một file `index.html` (HTML/CSS/JS thuần), có
màn hình nhập mật khẩu nhẹ trước khi xem, nhạc nền tự tổng hợp bằng Web
Audio (không dùng file nhạc có bản quyền), hiệu ứng tim/lấp lánh bay.

**Lưu ý về quyền riêng tư**: GitHub Pages ở gói Free yêu cầu repo phải
public và trang đã publish thì ai có link cũng xem được — không có cách
nào giới hạn người xem ở gói Free. Trang này giảm thiểu bằng:
- `robots.txt` chặn hết crawler, `<meta name="robots" content="noindex">`
  trong `index.html` → không bị Google index.
- Màn hình nhập mật khẩu — chỉ mang tính ngăn người tình cờ vào xem,
  không phải bảo mật thật (ai đọc được source vẫn thấy nội dung).

## Chạy thử trên máy

```bash
cd src/qua-20-10
python3 -m http.server 8000
# rồi mở http://localhost:8000
```

## Deploy

Repo riêng (không chung với `games`), domain riêng `yeu.concavang.me`
qua CNAME trỏ về `dotiendat997.github.io`.
