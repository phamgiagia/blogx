# HTML - Các Thẻ Cơ Bản

## Thẻ Tiêu Đề (Heading Tags)

Bất kỳ tài liệu nào cũng bắt đầu với một tiêu đề. Bạn có thể sử dụng các kích thước khác nhau cho tiêu đề của mình. HTML cung cấp sáu cấp độ tiêu đề, được biểu thị bằng các thẻ ```<h1>, <h2>, <h3>, <h4>, <h5>, và <h6>.``` Khi hiển thị bất kỳ tiêu đề nào, trình duyệt sẽ tự động thêm một dòng trống trước và sau tiêu đề đó.

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ về Tiêu đề</title>
   </head>
   
   <body>
      <h1>Đây là tiêu đề 1</h1>
      <h2>Đây là tiêu đề 2</h2>
      <h3>Đây là tiêu đề 3</h3>
      <h4>Đây là tiêu đề 4</h4>
      <h5>Đây là tiêu đề 5</h5>
      <h6>Đây là tiêu đề 6</h6>
   </body>
   
</html>
```

Đoạn mã trên sẽ tạo ra kết quả sau:

## Thẻ Đoạn Văn (Paragraph Tag)

Thẻ ```<p>``` cung cấp một cách để cấu trúc văn bản thành các đoạn văn khác nhau. Mỗi đoạn văn bản nên được đặt giữa thẻ mở `<p>` và thẻ đóng `</p>`, như trong ví dụ dưới đây:

Here is the content converted to GitHub Markdown and translated into Vietnamese:  

---

# Ví dụ về Đoạn Văn  

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ về Đoạn Văn</title>
   </head>
	
   <body>
      <p>Đây là đoạn văn thứ nhất.</p>
      <p>Đây là đoạn văn thứ hai.</p>
      <p>Đây là đoạn văn thứ ba.</p>
   </body>
	
</html>
```

## Thẻ Xuống Dòng  

Bất cứ khi nào bạn sử dụng thẻ `<br />`, nội dung theo sau sẽ bắt đầu từ dòng tiếp theo. Thẻ này là một ví dụ về thẻ rỗng, không cần thẻ mở và đóng, vì không có nội dung nằm giữa chúng.  

Thẻ `<br />` có một khoảng trống giữa `br` và dấu gạch chéo (`/`). Nếu bạn bỏ khoảng trống này, các trình duyệt cũ có thể gặp vấn đề khi hiển thị dấu xuống dòng. Nếu bạn chỉ dùng `<br>` mà không có dấu `/`, nó không hợp lệ trong XHTML.  

### Ví dụ  

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ về Xuống Dòng</title>
   </head>
	
   <body>
      <p>Xin chào<br />
         Bạn đã nộp bài đúng hạn.<br />
         Cảm ơn<br />
         Mahnaz</p>
   </body>
	
</html>
```

---

## Căn Giữa Nội Dung  

Bạn có thể sử dụng thẻ `<center>` để đưa nội dung vào giữa trang hoặc giữa một ô bảng.  

### Ví dụ  

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ Căn Giữa Nội Dung</title>
   </head>
	
   <body>
      <p>Đoạn văn này không được căn giữa.</p>
      
      <center>
         <p>Đoạn văn này được căn giữa.</p>
      </center>
   </body>
	
</html>
```

---

## Đường Ngang  

Các đường ngang giúp phân chia trực quan các phần trong tài liệu. Thẻ `<hr>` tạo một đường từ vị trí hiện tại đến mép phải của trang.  

### Ví dụ  

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ Đường Ngang</title>
   </head>
	
   <body>
      <p>Đây là đoạn văn thứ nhất và sẽ nằm trên.</p>
      <hr />
      <p>Đây là đoạn văn thứ hai và sẽ nằm dưới.</p>
   </body>
	
</html>
```

Thẻ `<hr />` cũng là một thẻ rỗng, không cần thẻ đóng.  

---

## Bảo Tồn Định Dạng  

Đôi khi, bạn muốn văn bản hiển thị đúng theo định dạng trong mã HTML. Khi đó, bạn có thể sử dụng thẻ `<pre>`.  

### Ví dụ  

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ Bảo Tồn Định Dạng</title>
   </head>
	
   <body>
      <pre>
         function testFunction( strText ){
            alert (strText)
         }
      </pre>
   </body>
	
</html>
```

Nếu bạn không sử dụng thẻ `<pre>`, trình duyệt sẽ bỏ qua các khoảng trắng thừa và xuống dòng.  

---

## Khoảng Trắng Không Ngắt  

Giả sử bạn muốn hiển thị cụm từ `"12 Angry Men."` mà không muốn trình duyệt chia tách từ `"12,"` và `"Angry Men"` sang hai dòng khác nhau.  

Trong trường hợp này, bạn nên sử dụng ký tự khoảng trắng không ngắt (`&nbsp;`).  

### Ví dụ  

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Ví dụ Khoảng Trắng Không Ngắt</title>
   </head>
	
   <body>
      <p>Một ví dụ về kỹ thuật này xuất hiện trong bộ phim "12&nbsp;Angry&nbsp;Men."</p>
   </body>
	
</html>
```

---
