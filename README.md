# E-commerce UI Improvement

## 1. Giới thiệu

Dự án là bản mẫu cải tiến giao diện khu vực giỏ hàng trên website thương mại điện tử, lấy cảm hứng từ website Cocoon Việt Nam. Mục tiêu là giúp khách hàng dễ nhận biết nút giỏ hàng, dễ thao tác để kiểm tra sản phẩm đã chọn và sử dụng thuận tiện trên máy tính lẫn điện thoại.

> Đây là bài tập HTML/CSS tĩnh, không phải website chính thức của Cocoon và không hỗ trợ đặt hàng thật.

## 2. Website tham khảo

- **Tên website:** Cocoon Việt Nam
- **URL:** [https://cocoonvietnam.com/](https://cocoonvietnam.com/)
- **Khu vực khảo sát:** Trang chủ, danh mục sản phẩm, chi tiết sản phẩm, tìm kiếm, giỏ hàng.
- **Lưu ý khảo sát:** Các nhận xét về chức năng tìm kiếm, bộ lọc, giỏ hàng và luồng mua hàng cần được người làm bài mở website thực tế kiểm tra, ghi ngày khảo sát và bổ sung ảnh chụp màn hình. Không xem đề xuất của AI là bằng chứng quan sát.

## 3. Chức năng trong bản mẫu

- Hiển thị khu vực đầu trang với lối vào giỏ hàng dễ nhận biết hơn.
- Sử dụng biểu tượng giỏ hàng kết hợp nhãn chữ để khách hàng nhận ra chức năng.
- Có thể hiển thị huy hiệu số lượng sản phẩm nếu được triển khai trong HTML.
- Hiển thị tối thiểu bốn thẻ sản phẩm mẫu với hình minh họa, tên và giá.
- Bố cục responsive, điều chỉnh theo kích thước màn hình.
- Đây là giao diện minh họa; thao tác thêm sản phẩm hoặc thanh toán không được kết nối backend.

## 4. Công nghệ

- HTML5
- CSS3 (Flexbox, Grid nếu có sử dụng, media queries và biến CSS nếu có sử dụng)
- Không sử dụng backend, cơ sở dữ liệu hoặc thư viện giao diện.

## 5. Cách chạy

1. Tải hoặc giải nén thư mục dự án.
2. Giữ nguyên cấu trúc thư mục, bao gồm `css/` và `images/` nếu có.
3. Mở `index.html` bằng Chrome, Safari, Firefox hoặc trình duyệt hiện đại.
4. Để kiểm tra giao diện điện thoại, mở DevTools → bật Device Toolbar → thử các chiều rộng 320px, 390px, 430px và 768px.

Không cần cài đặt package hoặc chạy máy chủ cục bộ.

## 6. Cải tiến giao diện giỏ hàng

- Làm nổi bật khu vực giỏ hàng trên đầu trang để khách hàng dễ nhận biết.
- Kết hợp biểu tượng giỏ hàng với nhãn “Giỏ hàng” để chức năng không chỉ phụ thuộc vào biểu tượng.
- Tổ chức các thành phần bằng Flexbox để căn chỉnh biểu tượng, nhãn và huy hiệu số lượng.
- Điều chỉnh giao diện bằng media queries để tránh chồng lấn hoặc tràn ngang trên màn hình nhỏ.
- Cân nhắc vùng nhấn đủ lớn và trạng thái `:hover` / `:focus-visible` để hỗ trợ thao tác bằng chuột, cảm ứng và bàn phím.

**Lưu ý:** Chỉ giữ lại những cải tiến thực sự có trong mã nguồn cuối cùng. Nếu huy hiệu số lượng, trạng thái bàn phím hoặc một trong các thuộc tính trên chưa được triển khai, hãy xóa mô tả tương ứng hoặc bổ sung trước khi nộp.

### Việc cần tự kiểm tra trước khi nộp

- Mở trang trên trình duyệt và xác nhận biểu tượng/nhãn giỏ hàng hiển thị đúng.
- Thử nhấn vào khu vực giỏ hàng để kiểm tra đường dẫn hoặc hành vi thực tế.
- Kiểm tra các kích thước 320px, 390px, 430px và 768px.
- Kiểm tra không có nội dung tràn ngang, chữ bị cắt hoặc các thành phần chồng lên nhau.
- Ghi lại ít nhất một vấn đề thực sự đã phát hiện, phần HTML/CSS đã sửa và kết quả sau khi sửa.
- Chụp ảnh màn hình làm minh chứng. Chỉ mô tả lỗi đã trực tiếp kiểm tra được.

## 7. Hỗ trợ từ AI

AI hỗ trợ đề xuất bố cục khu vực giỏ hàng, gợi ý cách tổ chức HTML/CSS và hướng dẫn kiểm thử responsive. Người làm bài cần tự đối chiếu website tham khảo, kiểm tra mã nguồn, thực hiện kiểm thử thật và giải thích được vai trò của các thành phần HTML/CSS đã chỉnh sửa.
