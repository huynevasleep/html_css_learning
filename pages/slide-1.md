## 🌐 Làm Quen Với Web Và HTML

<br/>

# Mục Tiêu Bài Học

<v-clicks class="space-y-3">

1. Hiểu **website là gì** và cách website hoạt động.
2. Phân biệt vai trò của **HTML, CSS và JavaScript**.
3. Hiểu cách trình duyệt đọc và hiển thị file HTML.
4. Tạo và chạy file **`index.html`** đầu tiên.
5. Nắm được cấu trúc cơ bản của một trang HTML.
6. Xây dựng trang web giới thiệu bản thân đơn giản.

</v-clicks>

---

# Cần chuẩn bị

<v-clicks>

- Máy tính
- Trình duyệt: `Chrome`, `Edge`, `Cốc cốc`, ...
- Code editor: `VS Code`, ...

</v-clicks>

---

# Website là gì?

<v-clicks>

- là một **tập hợp** các trang web mà người dùng có thể xem bằng trình duyệt.

| Thành phần     | Vai trò                  | Ví dụ dễ hiểu          |
| ---------------| ------------------------ | ---------------------- |
| ``HTML``       | Tạo nội dung và cấu trúc | Khung xương            |
| ``CSS``        | Trang trí giao diện      | Quần áo, màu sắc       |
| ``JavaScript`` | Tạo tương tác            | Hành động, chuyển động |

- Một căn nhà có:
    - Khung nhà: giống HTML.
    - Sơn tường, nội thất: giống CSS.
    - Công tắc đèn, cửa tự động: giống JavaScript.

</v-clicks>

---

# Trình duyệt hoạt động như thế nào?

<img
  v-click.none
  src="/images/image-1.png"
  alt="Trình duyệt hoạt động như thế nào"
  class="w-full max-h-[70vh] object-contain mx-auto"
/>

---

<v-clicks>

- ``HTML`` không phải là ngôn ngữ lập trình theo nghĩa tạo logic phức tạp.
- ``HTML`` là ngôn ngữ đánh dấu, dùng để mô tả nội dung trên trang web.

</v-clicks>

---

# HTML là gì?

<v-clicks>

- HTML là viết tắt của: ``HyperText Markup Language``.
- Là ngôn ngữ dùng để tạo cấu trúc nội dung cho trang web.
- HTML dùng các thẻ để đánh dấu nội dung.

```html
<h1>Xin chào</h1>
<p>Tôi đang học HTML.</p>
```

<br/>

### ✅ Ghi nhớ

HTML sử dụng các **thẻ** để mô tả cấu trúc nội dung:

- `<h1>` → tiêu đề
- `<p>` → đoạn văn


</v-clicks>

---

# Khái niệm thẻ HTML

<v-clicks>

**Cấu trúc một thẻ HTML**

- Một thẻ HTML thường có dạng: ``<tên-thẻ>Nội dung</tên-thẻ>``

- Ví dụ: ``<h1>Đây là tiêu đề</h1>``

| Thành phần       | Ý nghĩa |
| ---------------- | ------- |
| `<h1>`           | Thẻ mở |
| `Đây là tiêu đề` | Nội dung |
| `</h1>`          | Thẻ đóng |

</v-clicks>

---

# Bài tập

<v-clicks>

Viết đoạn HTML giới thiệu về bản thân, tên sử dụng **thẻ tiêu đề chính**, ngày tháng năm sinh sử dụng **thẻ tiêu đề phụ** và 1 phần paragraph giới thiệu ngắn về sở thích.

```html
<h1>Tiêu đề chính</h1>
<h2>Tiêu đề phụ</h2>
<p>Đây là một đoạn văn.</p>
```

</v-clicks>

---

# Cấu trúc cơ bản của một trang HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Trang web đầu tiên</title>
  </head>

  <body>
    <h1>Xin chào mọi người</h1>
    <p>Đây là trang web đầu tiên của tôi.</p>
  </body>
</html>
```

---

# Giải thích cấu trúc HTML

<div class="text-[25px] leading-relaxed">

<v-clicks>

<div>

`<!DOCTYPE html>`

Dòng này báo cho trình duyệt biết đây là tài liệu HTML phiên bản hiện đại.

</div>

<div>

`<html></html>`

Đây là thẻ bao ngoài toàn bộ trang HTML.

</div>

<div>

`<head></head>`

Phần `head` chứa thông tin mô tả về trang web.

> Nội dung trong `head` thường không hiển thị trực tiếp trên trang.

</div>

</v-clicks>

</div>

---

# Giải thích cấu trúc HTML

<div class="text-[25px] leading-relaxed">

<v-clicks>

<div>

`<title></title>`

Nội dung trong `title` được hiển thị trên tab của trình duyệt.

</div>

<div>

`<body></body>`

Phần `body` chứa nội dung hiển thị trên trang web.

> Những gì người dùng nhìn thấy thường được đặt trong `body`.

</div>

<div class="mt-5 p-4 rounded-xl bg-blue-500/10 border border-blue-500/30">

### 💡 Ghi nhớ

- `head` chứa thông tin **về trang web**.
- `body` chứa nội dung **hiển thị trên trang web**.

</div>

</v-clicks>

</div>

---

# Thực hành

Đề bài

Tạo trang web có nội dung:

Tiêu đề chính: tên của học viên.
Một đoạn giới thiệu bản thân.
Một tiêu đề phụ: “Sở thích của tôi”.
Một đoạn văn nói về sở thích.
Một tiêu đề phụ: “Mục tiêu học HTML”.
Một đoạn văn nói về mục tiêu.

---

# Ví dụ

```html {1|2-6|8-28|all}{lines:true,maxHeight:'68vh'}
<!DOCTYPE html>
<html>
  <head>
    <title>Giới thiệu bản thân</title>
  </head>

  <body>
    <h1>Nguyễn Văn A</h1>

    <p>
      Xin chào, tôi là Nguyễn Văn A.
      Tôi đang bắt đầu học HTML.
    </p>

    <h2>Sở thích của tôi</h2>

    <p>
      Tôi thích nghe nhạc, đọc sách,
      chơi thể thao và tìm hiểu công nghệ.
    </p>

    <h2>Mục tiêu học HTML</h2>

    <p>
      Tôi muốn hiểu cách trang web được tạo ra
      và xây dựng trang giới thiệu cá nhân.
    </p>
  </body>
</html>
```

---

# Bài tập về nhà

- Tạo một trang HTML giới thiệu bản thân với tên file: ``about-me.html``

Trang cần có:

- Tiêu đề trang trên tab trình duyệt.
- Họ tên.
- Một đoạn giới thiệu bản thân.
- Sở thích.
- Mục tiêu học lập trình.
- Một câu châm ngôn yêu thích.

---

# Các lỗi thường gặp

<v-clicks>

## 1. Quên thẻ đóng

**❌ Sai**

``<h1>Xin chào``

**✅ Đúng**

```html
<h1>Xin chào</h1>
```
</v-clicks>

---

<v-clicks>

## 2. Viết sai tên thẻ

**❌ Sai**

``<tilte>Trang web</tilte>``

**✅ Đúng**

```html
<title>Trang web</title>
```
</v-clicks>

---
<v-clicks>

## 3. Lưu sai đuôi file

- ❌ Sai: `index.html.txt`

- ✅ Đúng: `index.html`

</v-clicks>

---

# ⚠️ Các lỗi học viên thường gặp

<v-clicks>

## 4. Sửa code nhưng trình duyệt chưa cập nhật

### ✅ Cách xử lý

1. Lưu file bằng `Ctrl + S`.
2. Quay lại trình duyệt.
3. Nhấn `F5` hoặc nút **Reload**.

</v-clicks>

---

<v-clicks>

## 5. Viết nội dung ngoài thẻ `body`

**❌ Không nên**

```html
<html>
  <head>
    <title>Trang web</title>
  </head>

  Xin chào mọi người

  <body>
    <h1>HTML</h1>
  </body>
</html>
```

</v-clicks>

---

<v-clicks>

# ✅ Cách viết đúng

```html
<html>
  <head>
    <title>Trang web</title>
  </head>

  <body>
    <h1>HTML</h1>
    <p>Xin chào mọi người</p>
  </body>
</html>
```

> 💡 Nội dung muốn hiển thị trên trang web nên được đặt bên trong thẻ `body`.

## Ghi nhớ

- Luôn kiểm tra **thẻ mở** và **thẻ đóng**.
- Viết đúng **tên thẻ HTML**.
- Lưu file với đuôi `.html`.
- Nhấn `Ctrl + S` trước khi tải lại trình duyệt.
- Đặt nội dung hiển thị bên trong `body`.

</v-clicks>