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