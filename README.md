# Mô hình ADN xoắn kép 3D

Trang web tương tác giúp khám phá cấu trúc ADN ở bốn cấp độ: **nhiễm sắc thể → nuclêôxôm → xoắn kép → nuclêôtit**. Giao diện, nội dung mô tả, nhãn điều khiển và hướng dẫn đã được Việt hóa.

## Tính năng

- Mô hình ADN 3D có thể xoay và phóng to/thu nhỏ.
- Chuyển đổi giữa bốn cấp độ cấu trúc.
- Quan sát hình dạng xoắn kép, rãnh lớn/rãnh nhỏ và kích thước.
- Tạo mạch bổ sung từ trình tự A, T, G, C.
- Kiểm tra bắt cặp bazơ và liên kết hiđrô.

## Chạy trên GitHub Pages

1. Mở **Settings → Pages** của repository.
2. Trong **Build and deployment**, chọn **Deploy from a branch**.
3. Chọn nhánh `main`, thư mục `/(root)`, rồi nhấn **Save**.
4. Chờ GitHub Pages triển khai và mở đường dẫn được hiển thị tại trang Pages.

## Cấu trúc triển khai

- `index.html`: trang chính và giao diện tiếng Việt.
- `vendor.bundle.gz`: thư viện Three.js, OrbitControls, RoomEnvironment và KaTeX.
- `assets.bundle.gz`: mã nguồn mô hình và logic tương tác.
- Hai gói JavaScript được nén gzip và giải nén ngay trong trình duyệt; không phụ thuộc CDN bên ngoài.

## Lưu ý

Đây là bản đóng gói từ bộ mã nguồn được cung cấp trong cuộc trò chuyện. Các thư viện và nội dung bên trong được giữ lại để mô hình hoạt động độc lập trên GitHub Pages.
