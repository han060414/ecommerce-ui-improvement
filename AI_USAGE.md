# AI Usage Log

## 1. Công cụ AI
Tên công cụ: Gemini (Google) / ChatGPT (OpenAI)

## 2. Mục đích sử dụng
- Phân tích UX/UI của khu vực tìm kiếm trên MyKingdom.
- Đề xuất bố cục HTML5 và tạo bộ khung CSS3 cho thanh tìm kiếm và thẻ sản phẩm.

## 3. Prompt đã sử dụng
- "Tôi muốn cải tiến khu vực: TÌM KIẾM, T MUỐN THÊM TÍNH NĂNG TÌM KIẾM BẰNG HÌNH ẢNH, BIẾT RẰNG GIAO DIỆN NHƯ ẢNH T GỬI..."
- "Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3..."

## 4. Kết quả AI đề xuất
- Đề xuất cấu trúc dùng `<div class="search-wrapper">` bọc ngoài ô `<input type="text">` và dùng `position: absolute` để đặt các thẻ `<svg>` (icon kính lúp, camera) vào hai đầu.
- Sinh ra đoạn mã CSS responsive với `display: grid` cho khu vực hiển thị thẻ sản phẩm.

## 5. Kiểm tra và điều chỉnh
- Đã kiểm tra chức năng ẩn của input file: Thẻ `<label for="image-search-upload">` hoạt động tốt, kích hoạt được cửa sổ duyệt file của máy tính.
- Đã chỉnh sửa lề chữ: Thay đổi thuộc tính `padding` của ô input để text không trôi đè lên icon camera khi gõ quá dài.

## 6. Phần tôi hiểu và có thể giải thích
- Hiểu cách hoạt động của Flexbox (`display: flex; align-items: center;`) để căn giữa các phần tử trong thanh header.
- Nắm rõ cách dùng `position: absolute; right: 15px;` để cố định icon camera luôn nằm sát mép phải của thanh tìm kiếm bất chấp kích thước màn hình bị thu nhỏ hay phóng to.