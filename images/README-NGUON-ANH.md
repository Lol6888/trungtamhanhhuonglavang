# Nguồn hình ảnh & bản quyền

Tất cả ảnh đã tải về dưới đây lấy từ **Wikimedia Commons** (giấy phép tự do – Creative Commons / Public Domain).
Khi đăng tải công khai, nên ghi credit tác giả theo trang gốc để đúng quy định.

| File | Nội dung | Section dùng | Nguồn (Wikimedia Commons – File:) |
|---|---|---|---|
| `quang-truong-toan-canh.jpg` | Toàn cảnh Quảng trường La Vang (ảnh ngang rộng) | Hero + Công trình #5 | `Toàn cảnh quảng trường La Vang.JPG` |
| `duc-me-la-vang.jpg` | Tượng Đức Mẹ La Vang (áo dài, bồng Chúa Hài Đồng) | Lịch sử + Cẩm nang | `Ducme Lavang.JPG` |
| `linh-dai-ba-cay-da.jpg` | Linh đài – ba cây đa | Công trình #1 | `Ba cây đa ở La Vang.JPG` |
| `thap-co-la-vang.jpg` | Tháp cổ / tháp chuông nhà thờ cũ | Công trình #2 | `Tháp chuông La Vang.JPG` |
| `nha-tho-cu-1967.jpg` | Nhà thờ La Vang cũ, ảnh 1967 (trước khi bị phá 1972) | Lịch sử | `La Vang Church (Built 1928, Destroyed 1972) September, 1967.jpg` |
| `thanh-gia-la-vang.jpg` | Đàng Thánh Giá | Công trình #6 | `Thánh giá La Vang.JPG` |
| `la-vang-cay.jpg` | Lá vằng (cây thuốc) | Giới thiệu | `Lá La Vang.JPG` |

Cách mở trang gốc để xem giấy phép/tác giả:
`https://commons.wikimedia.org/wiki/File:<tên_file>`

## Ảnh CẦN BỔ SUNG (đang để placeholder trang nhã trong trang)

Wikimedia chưa có ảnh chất lượng cho mục này. Đề nghị dùng **ảnh chụp riêng** của Trung tâm để đảm bảo bản quyền và độ mới:

1. **Vương cung Thánh đường MỚI** → lưu thành `vuong-cung-thanh-duong-moi.jpg`

Sau khi có ảnh, mở `index.html`, tìm khối có class `ph placeholder` (Công trình #3) và thay bằng:
```html
<div class="ph"><span class="num">3</span><img src="images/vuong-cung-thanh-duong-moi.jpg" alt="Vương cung Thánh đường Đức Mẹ La Vang mới" /></div>
```

> Khuyến nghị: dùng ảnh ngang tỷ lệ ~4:3, tối thiểu 1200px chiều rộng cho thẻ; ảnh Hero nên ≥1600px.
