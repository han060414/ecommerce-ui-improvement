# Vương Quốc Đồ Chơi – Bài tập cá nhân Buổi 2

## 1. Giới thiệu dự án
Dự án tiếp tục phát triển giao diện website thương mại điện tử đồ chơi từ bài tập Buổi 1 của học phần **Phát triển ứng dụng WEB/TMĐT**. Website tham khảo là [MyKingdom](https://www.mykingdom.com.vn/).

Phạm vi thực hành gồm Header và thanh tìm kiếm, menu điều hướng, khu vực **Xu Hướng Sản Phẩm** với 4 thẻ sản phẩm. Tên cửa hàng trong giao diện mẫu là **Vương Quốc Đồ Chơi**.

## 2. Cấu trúc dự án
```text
ecommerce-ui-improvement/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── image1.jpg
│   ├── image2.jpg
│   ├── image3.jpg
│   └── image4.jpg
├── README.md
└── AI_USAGE.md
```

## 3. Nội dung đã thực hành ở Buổi 2
- **HTML5 có ngữ nghĩa:** `header`, `nav`, `main`, `section`, `article`, thứ bậc tiêu đề, ảnh có `alt`.
- **CSS ngoài:** tách CSS trong thẻ `<style>` sang `css/style.css`.
- **CSS Selector và Box Model:** `img`, `.product-card`, `.product-card .btn-add-cart`; `margin`, `padding`, `border`, `border-radius`, `box-sizing`.
- **Flexbox:** căn chỉnh Header và menu bằng `display: flex`, `justify-content`, `align-items`, `gap`.
- **CSS Grid:** thử nghiệm danh sách sản phẩm 2 cột và 3 cột; phiên bản cuối dùng 2 cột ở màn hình lớn.
- **Hover và Focus:** hiệu ứng `:hover`, `:focus-visible` cho nút “Thêm vào giỏ”.
- **Kiểm tra responsive:** dùng Chrome DevTools; bổ sung `@media (max-width: 480px)` để chuyển danh sách thành 1 cột trên điện thoại nhỏ.

## 4. Cách chạy website
Mở `index.html` bằng Chrome, Edge hoặc dùng Live Server trong VS Code. Không cần cài đặt thư viện JavaScript hay công cụ build.

## 5. Cách kiểm tra
1. Xác nhận 4 ảnh từ thư mục `images/` được hiển thị và tệp `css/style.css` tải đúng.
2. Dùng Chrome DevTools kiểm tra chiều rộng 1366px, 768px và 390px.
3. Tại 390px, danh sách sản phẩm chuyển thành 1 cột nhờ Media Query.
4. Di chuột lên “Thêm vào giỏ” để thử `hover`; dùng Tab để kiểm tra `focus-visible`.
5. Đối chiếu báo cáo Word và ảnh minh chứng trước/sau cho từng bước thực hành.

## 6. Phạm vi và giới hạn
Đây là **giao diện tĩnh HTML/CSS**. Biểu tượng camera chỉ mở hộp thoại chọn tệp ảnh; chưa triển khai thuật toán tìm kiếm bằng hình ảnh. Các nút “Thêm vào giỏ”, tài khoản và giỏ hàng chưa có xử lý bằng JavaScript; các mục menu còn dùng `href="#"` làm liên kết minh họa.

Các ý tưởng như nhãn giảm giá “-50%” và nút “Xem tất cả” được ghi trong phần rà soát Bước 1 nhưng **chưa triển khai** ở phiên bản Buổi 2.

## 7. Sử dụng AI và kiểm chứng
Đã sử dụng ChatGPT và Gemini để gợi ý và giải thích HTML/CSS, rà soát cấu trúc, thực hành Selector/Box Model, Flexbox, Grid và Media Query. Các đề xuất được đối chiếu với mã nguồn thật, thử trên trình duyệt và điều chỉnh phù hợp. Ví dụ: tinh chỉnh `padding` của ô tìm kiếm để tránh icon che chữ; sửa lưới hai cột bị chật ở 390px bằng Media Query.

Chi tiết prompt, kết quả và tự điều chỉnh: [AI_USAGE.md](AI_USAGE.md).

## 8. Repository
https://github.com/han060414/ecommerce-ui-improvement

Nội dung Buổi 2 dựa trên bài Buổi 1 và tiếp tục làm nền tảng cho thực hành JavaScript ở Buổi 3.
