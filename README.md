# Nhiễm Sắc Thể – Nhóm 6

Website học tập tương tác giúp người xem khám phá cấu trúc ADN bằng mô hình 3D. Người dùng có thể quan sát ADN ở nhiều cấp độ, xoay và phóng to mô hình, tìm hiểu cách các bazơ liên kết với nhau và thử tạo mạch ADN bổ sung.

Mã nguồn website trong repository được **Agent lập trình của nhóm chuẩn bị**. Nhóm sử dụng repository này để lưu trữ, chia sẻ và triển khai sản phẩm. Bản đang công bố đã được Việt hóa giao diện và nội dung hiển thị.

## Nội dung và tính năng

- **Khám phá cấu trúc theo 4 cấp độ:** nhiễm sắc thể → nuclêôxôm → chuỗi xoắn kép → nuclêôtit.
- **Quan sát mô hình 3D:** xoay, phóng to/thu nhỏ và chuyển đổi giữa các cấp độ cấu trúc.
- **Tìm hiểu cấu trúc ADN:** hai mạch, chiều 5′–3′, khung đường–phosphate, các cặp bazơ và rãnh của chuỗi xoắn kép.
- **Thử với trình tự ADN:** nhập chuỗi gồm A, T, G, C và tạo mạch bổ sung.
- **Kiểm tra bắt cặp bazơ:** xem các cặp bazơ phù hợp, không phù hợp và liên kết hiđrô.
- **Quan sát thông số:** chiều dài, số vòng xoắn và tỉ lệ G–C của trình tự.

## Sử dụng website

### Xem trực tiếp

Sau khi bật GitHub Pages, website có thể được truy cập tại:

**https://baobao-creator.github.io/NhiemSacTheNhom6/**

### Chạy trên máy tính

Có thể chạy website bằng một máy chủ web tĩnh. Mở Terminal/PowerShell tại thư mục chứa các tệp và chạy:

```powershell
py -m http.server 8000
```

Sau đó mở http://localhost:8000 trên trình duyệt.

Không cần cài đặt Node.js hay tải thêm thư viện qua CDN để chạy bản đã đóng gói trong repository.

## Cấu trúc tệp

| Tệp | Nội dung |
|---|---|
| `index.html` | Trang web chính, giao diện và nội dung tiếng Việt |
| `vendor.bundle.gz` | Các thư viện dùng cho hiển thị 3D và công thức |
| `assets.bundle.gz` | Mã mô hình, nội dung và logic tương tác của website |
| `README.md` | Giới thiệu dự án và hướng dẫn sử dụng |
| `LICENSE` | Giấy phép MIT cho phần mã nguồn thuộc quyền cấp phép của chủ repository |
| `THIRD_PARTY_NOTICES.md` | Thông tin giấy phép và lưu ý về thành phần bên thứ ba |

Hai gói `*.bundle.gz` được trang web giải nén trong trình duyệt khi khởi chạy.

## Triển khai bằng GitHub Pages

1. Mở **Settings → Pages** trong repository.
2. Ở mục **Build and deployment**, chọn **Deploy from a branch**.
3. Chọn nhánh `main` và thư mục `/(root)`.
4. Nhấn **Save** và chờ GitHub Pages hoàn tất triển khai.
5. Mở đường dẫn website được hiển thị tại trang Pages.

## Giấy phép

Phần mã nguồn và tài liệu gốc do **BaoBao-creator** sở hữu trong repository này được cấp phép theo **MIT License**. Bạn có thể sử dụng, sao chép, chỉnh sửa, kết hợp, phân phối và sử dụng thương mại phần được cấp phép, với điều kiện giữ lại thông báo bản quyền và nội dung giấy phép.

**Lưu ý:** MIT License của repository không tự động áp dụng cho thư viện, tài nguyên hoặc thành phần của bên thứ ba mà chủ repository không sở hữu. Hãy đọc [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) trước khi tái sử dụng hoặc phân phối các thành phần đó.
