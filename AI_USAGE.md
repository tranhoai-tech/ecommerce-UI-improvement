# AI Usage Log

## 1. Công cụ AI
- Công cụ: ChatGPT
- Mục đích: hỗ trợ phân tích trải nghiệm người dùng, đề xuất bố cục, giải thích HTML/CSS và tạo bản mẫu ban đầu.

## 2. Mục đích sử dụng
- Lập khung khảo sát website thương mại điện tử.
- Gợi ý cải tiến thẻ sản phẩm và cách trình bày giá.
- Hỗ trợ viết HTML5, CSS3 và danh sách kiểm thử.
- Soạn tài liệu README.

## 3. Prompt đã sử dụng

### Prompt 1 — Phân tích website
> Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử. Tôi đang khảo sát website Cocoon Việt Nam: https://cocoonvietnam.com/. Hãy lập bảng phân tích trang chủ, danh mục sản phẩm, chi tiết sản phẩm, tìm kiếm và giỏ hàng. Với mỗi khu vực, nêu mục đích, thành phần giao diện cần có, điểm thuận tiện, một vấn đề có thể phát sinh và đề xuất cải tiến. Không khẳng định tính năng chưa được kiểm chứng. Phân biệt nhận xét dựa trên quan sát với đề xuất của AI.

### Prompt 2 — Đề xuất giao diện
> Tôi đang làm bài tập phát triển giao diện thương mại điện tử bằng HTML5 và CSS3. Tôi muốn cải tiến thẻ sản phẩm trên website mỹ phẩm, dành cho khách hàng mua sắm trực tuyến tại Việt Nam. Hãy đề xuất bố cục, thành phần HTML, cách tổ chức CSS, hiển thị trên máy tính và điện thoại, cùng các điểm cần kiểm tra về khả năng sử dụng. Trước tiên hãy giải thích phương án thiết kế.

### Prompt 3 — Tạo mã nguồn
> Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3. Có tiêu đề và khu vực sản phẩm; tối thiểu bốn sản phẩm, mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác; responsive cho máy tính và điện thoại; tách CSS riêng; không sử dụng backend hoặc cơ sở dữ liệu; giải thích cách chạy và những phần cần kiểm tra.

## 4. Kết quả AI đề xuất
- Làm rõ tên sản phẩm, nhóm sản phẩm, giá và nút thao tác.
- Dùng lưới sản phẩm và thay đổi số cột theo chiều rộng màn hình.
- Tạo các tệp `index.html`, `style.css`, `README.md` và thư mục `images/`.
- Dùng SVG minh họa cục bộ làm ảnh sản phẩm mẫu.

## 5. Kiểm tra và điều chỉnh
- Nội dung sản phẩm và giá trong bản mẫu được dùng làm dữ liệu minh họa; phải đối chiếu lại với website chính thức trước khi nộp.
- Các nhận xét về lọc/sắp xếp, kết quả tìm kiếm và giỏ hàng không được ghi là quan sát thực tế nếu chưa tự thao tác trên website.
- Mã nguồn cần được mở trong trình duyệt và kiểm tra ở cả desktop lẫn mobile. Ghi lại lỗi thật phát hiện được, sửa lỗi, rồi mô tả thay đổi sau khi kiểm thử.
- Các nút trong bản mẫu chỉ dẫn đến website tham khảo; không có giỏ hàng hay chức năng thanh toán thật.

## 6. Phần tôi hiểu và có thể giải thích
- `header`, `nav`, `main`, `section`, `article` và `footer` giúp cấu trúc trang có ngữ nghĩa.
- CSS Grid (`grid-template-columns`) bố trí các thẻ thành lưới.
- Flexbox (`display: flex`, `flex-direction: column`) sắp xếp nội dung trong từng thẻ.
- `margin-top: auto` đẩy nút xuống cuối thẻ khi thẻ dùng Flexbox theo chiều dọc.
- `@media` thay đổi bố cục trên màn hình nhỏ.
- `alt` trong ảnh hỗ trợ khả năng truy cập khi hình không tải hoặc với công nghệ đọc màn hình.
