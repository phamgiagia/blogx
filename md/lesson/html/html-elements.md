Here’s the content converted to GitHub Markdown and translated into Vietnamese:  

---

### HTML - Elements  

Một phần tử (element) HTML được xác định bởi một thẻ mở. Nếu phần tử chứa nội dung khác, nó kết thúc bằng một thẻ đóng, trong đó tên phần tử được đặt trước bởi dấu gạch chéo (`/`) như trong các thẻ sau:  

```html
<p>Đây là nội dung của đoạn văn.</p>
<h1>Đây là nội dung tiêu đề.</h1>
<div>Đây là nội dung của một khối.</div>
<br />
```

Như vậy, `<p>...</p>` là một phần tử HTML, `<h1>...</h1>` là một phần tử HTML khác. Một số phần tử HTML không cần thẻ đóng, chẳng hạn như `<img ... />`, `<hr />`, và `<br />`. Những phần tử này được gọi là **void elements** (phần tử rỗng).  

Tài liệu HTML bao gồm một **cây các phần tử**, chúng xác định cách cấu trúc tài liệu HTML và loại nội dung nào nên được đặt vào đâu trong tài liệu.  

---

### Thẻ HTML vs. Phần tử HTML  

- Một phần tử HTML được xác định bởi một thẻ mở và một thẻ đóng (nếu có).  
- Ví dụ, `<p>` là thẻ mở của một đoạn văn, `</p>` là thẻ đóng của đoạn văn đó. Nhưng `<p>Đây là một đoạn văn</p>` mới là một phần tử đoạn văn đầy đủ.  

---

### Phần tử HTML lồng nhau (Nested HTML Elements)  

Hoàn toàn có thể đặt một phần tử HTML bên trong một phần tử HTML khác, ví dụ:  

```html
<div>
  <h1>Tiêu đề</h1>
  <p>Đây là một đoạn văn bên trong một div.</p>
</div>
```

Tính năng này giúp tổ chức nội dung trên trang web một cách rõ ràng và hợp lý hơn.

```html
<!DOCTYPE html>
<html>

   <head>
      <title>Nested Elements Example</title>
   </head>
	
   <body>
      <h1>This is <i>italic</i> heading</h1>
      <p>This is <u>underlined</u> paragraph</p>
   </body>
	
</html>
```
