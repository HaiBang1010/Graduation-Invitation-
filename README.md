# Thiệp mời tốt nghiệp — Trần Phan Hải Bằng

Thiệp mời online, phong cách vintage (paper texture + ribbon).
Toàn bộ code trong 1 file `index.html` — không cần build.

## Cách dùng

1. Bỏ file nhạc nền vào `./assets/bgm.mp3` (loop, tự chuẩn bị).
2. Mở `index.html` bằng trình duyệt, hoặc deploy như static site.

## URL param

Truyền tên khách qua param `?name=...` (đã `encodeURIComponent`):

```
index.html?name=Nguy%E1%BB%85n%20V%C4%83n%20A
```

Nếu không có param → fallback `Quý khách quý mến`.

## Deploy

Static site bất kỳ:

- **GitHub Pages**: push lên repo, bật Pages từ branch `main`.
- **Netlify / Vercel**: drag-and-drop thư mục.
- **Cloudflare Pages**: connect repo, không cần build command.

## RSVP

Form đẩy về Formspree endpoint `https://formspree.io/f/maqkkadk`.
Đổi endpoint trong `index.html` nếu muốn dùng form khác.
