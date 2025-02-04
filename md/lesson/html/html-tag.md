### Tổng Quan về Thẻ HTML

HTML là một ngôn ngữ đánh dấu được sử dụng để cấu trúc nội dung trên web. Các thẻ trong HTML được bao bọc trong dấu ngoặc nhọn (`< >`). Hầu hết các thẻ đều có thẻ mở và thẻ đóng, nhưng một số thẻ (như `<img>`) là thẻ tự đóng.

#### Các Thẻ HTML Thường Gặp:

|**Số Thứ Tự**|**Thẻ & Mô Tả**|
|---|---|
|**1**|`<DOCTYPE>`Định nghĩa loại tài liệu và phiên bản HTML sử dụng (ví dụ: `<!DOCTYPE html>` cho HTML5).|
|**2**|`<html>`Bao bọc toàn bộ tài liệu HTML, bao gồm các phần `<head>` và `<body>`.|
|**3**|`<head>`Chứa metadata về tài liệu, như tiêu đề, bộ ký tự, liên kết đến các tệp stylesheet, v.v.|
|**4**|`<title>`Chỉ định tiêu đề của tài liệu, được hiển thị trên thanh tiêu đề hoặc tab của trình duyệt.|
|**5**|`<body>`Đại diện cho nội dung chính của tài liệu. Tất cả các phần tử hiển thị (văn bản, hình ảnh, liên kết, v.v.) được đặt trong đây.|
|**6**|`<h1>` đến `<h6>`Định nghĩa các tiêu đề, trong đó `<h1>` là tiêu đề lớn và quan trọng nhất, còn `<h6>` là tiêu đề nhỏ nhất.|
|**7**|`<p>`Định nghĩa một đoạn văn bản. Thẻ này tự động thêm khoảng cách trước và sau đoạn văn.|

### Điểm Chính:

- **Thẻ**: Các thẻ không phân biệt chữ hoa chữ thường, nhưng W3C (Tổ Chức W3C) khuyến khích sử dụng thẻ chữ thường trong HTML (đặc biệt là HTML5).
- **Thẻ Lồng Nhau**: Các thẻ có thể lồng nhau để cấu trúc các tài liệu phức tạp.
- **Thẻ Tự Đóng**: Một số thẻ như `<img>`, `<br>`, và `<input>` không yêu cầu thẻ đóng.

#### Ví Dụ Tài Liệu HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Trang HTML Đầu Tiên Của Tôi</title>
  </head>
  <body>
    <h1>Chào Mừng Đến Với Website Của Tôi</h1>
    <p>Đây là một đoạn văn bản.</p>
  </body>
</html>
```

Học HTML khá đơn giản vì nó liên quan đến việc hiểu cách các thẻ này tương tác để tạo ra các tài liệu có cấu trúc tốt, là nền tảng của bất kỳ trang web nào.
