# E-commerce UI Improvement

## 1. Giới thiệu
Dự án cải tiến giao diện cho website thương mại điện tử chuyên bán đồ chơi. Cụ thể, bổ sung tính năng "Tìm kiếm bằng hình ảnh" (Camera Icon) vào thanh tìm kiếm gốc để tăng cường trải nghiệm người dùng, giúp phụ huynh và trẻ em dễ dàng tìm sản phẩm qua ảnh chụp.

## 2. Website tham khảo
- Tên website: MyKingdom
- URL: https://www.mykingdom.com.vn/
- Khu vực đã khảo sát: Thanh tìm kiếm (Header) và Lưới sản phẩm.

## 3. Chức năng
- Hiển thị thanh tìm kiếm có tích hợp icon Camera cho phép chọn file ảnh.
- Hiển thị danh sách 4 sản phẩm mẫu với thông tin giá gốc, giá giảm.
- Bố cục hỗ trợ responsive hiển thị tốt trên cả máy tính và thiết bị di động.

## 4. Công nghệ
- HTML5
- CSS3

## 5. Cách chạy
Mở file `index.html` trực tiếp bằng trình duyệt web (Chrome, Edge, Safari...).

## 6. Cải tiến đã thực hiện
- Vấn đề ban đầu: Nhập từ khóa dài hoặc tên tiếng Anh của đồ chơi gây khó khăn cho tệp khách hàng trẻ em/phụ huynh.
- Thay đổi: Tích hợp icon tìm kiếm bằng hình ảnh vào ngay bên trong ô input text, căn lề hợp lý để không bị lẹm chữ khi gõ dài.

## 7. Hỗ trợ từ AI
- Sử dụng Gemini/ChatGPT để lên ý tưởng bố cục HTML và viết cấu trúc CSS ban đầu.
- Bản thân tự kiểm tra responsive bằng Chrome DevTools, tự điều chỉnh thuộc tính `padding` của `.search-input` để tối ưu vùng an toàn cho text và các icon.
# Vương Quốc Đồ Chơi – Bài tập cá nhân Buổi 2 (HTML5 & CSS3)

## Giới thiệu
Dự án tiếp tục từ Buổi 1 của học phần Phát triển ứng dụng WEB/TMĐT. Website tham khảo: [MyKingdom](https://www.mykingdom.com.vn/). Phạm vi thực hành: thanh tìm kiếm/Header, menu điều hướng và danh sách 4 sản phẩm đồ chơi.

## Cấu trúc thư mục
```text
ecommerce-ui-improvement-buoi2/
├── index.html
├── css/style.css
├── images/image1.jpg ... image4.jpg
├── README.md
└── AI_USAGE.md
```

## Nội dung thực hành Buổi 2
- **HTML5 có ngữ nghĩa:** `header`, `nav`, `main`, `section`, `article`; tiêu đề theo cấp, ảnh có `alt`.
- **CSS ngoài:** Chuyển CSS khỏi thẻ `<style>` và liên kết `css/style.css`.
- **CSS Selector & Box Model:** `img`, `.product-card`, `.product-card .btn-add-cart`; `margin`, `padding`, `border`, `border-radius`, `box-sizing`.
- **Flexbox:** Căn chỉnh header, thanh menu và các phần tử trong thẻ sản phẩm.
- **Grid:** Bố trí 2 cột ở màn hình rộng; đã thử nghiệm 3 cột.
- **Hover / Focus:** Hiệu ứng `:hover`, `:focus-visible` cho nút Thêm vào giỏ.
- **Responsive:** Với màn hình rộng tối đa 480px, `.product-grid` chuyển sang 1 cột.

## Cách chạy
Mở `index.html` bằng trình duyệt (hoặc dùng Live Server trong VS Code). Không cần cài đặt thêm thư viện.

## Cách kiểm tra
1. Kiểm tra bốn ảnh nằm trong `images/` và CSS tải từ `css/style.css`.
2. Mở Chrome DevTools, thử độ rộng 1366px, 768px và 390px.
3. Ở 390px, xác nhận danh sách sản phẩm hiển thị một cột.
4. Di chuột qua nút Thêm vào giỏ để kiểm tra `hover`; dùng phím Tab để kiểm tra `focus-visible`.
5. Kiểm tra liên kết trong menu: hiện đang dùng `href="#"` làm liên kết minh họa.

## Giới hạn hiện tại
Trang đang là giao diện tĩnh HTML/CSS: biểu tượng camera cho phép mở hộp thoại chọn ảnh nhưng chưa tìm kiếm bằng hình ảnh; nút Thêm vào giỏ chưa xử lý giỏ hàng; liên kết danh mục chưa có trang đích. Các chức năng tương tác dự kiến phát triển bằng JavaScript ở buổi sau.

## AI hỗ trợ
Đã sử dụng ChatGPT để gợi ý và giải thích HTML/CSS. Xem `AI_USAGE.md` để biết mục đích, ví dụ prompt và các thay đổi được rà soát.

## Repository GitHub
https://github.com/han060414/ecommerce-ui-improvement.git
