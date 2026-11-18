# Booth games – Event Club of BUV

Hai mini game web cho booth giới thiệu Event Club of BUV. Web tĩnh thuần HTML/CSS/JS, không cần build, không cần cài gì.

| Đường dẫn | Game |
|---|---|
| `/` | Trang chủ, chọn game |
| `/dap-chuot/` | Đập Chuột: gắn mặt bạn bè lên chuột, chơi 30 giây |
| `/dung-san-khau/` | Dựng Sân Khấu: làm trưởng ban tổ chức trong khoảng 2 phút (staff chỉnh được thời gian ở màn bắt đầu) |

## Chạy thử trên máy

```bash
python3 -m http.server 8000
# mở http://localhost:8000
```

## Deploy lên Vercel

1. Push repo này lên GitHub.
2. Trên vercel.com chọn **Add New → Project**, rồi import repo.
3. Framework Preset: **Other**. Để trống Build Command và Output Directory.
4. Bấm **Deploy**.

## Ghi chú

- Bảng xếp hạng được lưu bằng `localStorage` trên trình duyệt của máy đang chạy game. Đổi máy hoặc đổi trình duyệt là bảng trống.
- Ảnh khuôn mặt chỉ nằm trong bộ nhớ trang: không upload đi đâu, và mất khi tải lại trang.
- Font chữ được tải từ Google Fonts, nên máy cần có mạng. Nếu không có mạng, game vẫn chạy nhưng dùng font hệ thống.
# EC-games
