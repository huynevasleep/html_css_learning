# Buổi 2: Các Thẻ HTML Cơ Bản

<v-clicks>

1. Sử dụng thành thạo các thẻ tiêu đề: ``h1``, ``h2``, ``h3``.
2. Biết viết đoạn văn bằng thẻ ``p``.
3. Biết làm nổi bật nội dung bằng ``strong`` và ``em``.
4. Biết xuống dòng bằng ``br``.
5. Biết tạo đường kẻ phân cách bằng ``hr``.
6. Biết tạo danh sách không thứ tự bằng ``ul``, ``li``.
7. Biết tạo danh sách có thứ tự bằng ``ol``, ``li``.
8. Hoàn thiện một trang giới thiệu bản thân có cấu trúc rõ ràng.

</v-clicks>

---

# Thẻ tiêu đề

<v-clicks>

- HTML có nhiều cấp độ tiêu đề từ ``h1`` đến ``h6``.

```html
<h1>Tiêu đề cấp 1</h1>
<h2>Tiêu đề cấp 2</h2>
<h3>Tiêu đề cấp 3</h3>
<h4>Tiêu đề cấp 4</h4>
<h5>Tiêu đề cấp 5</h5>
<h6>Tiêu đề cấp 6</h6>
```

| Thẻ    | Vai trò                     |
| ------ | --------------------------- |
| `<h1>` | Tiêu đề lớn nhất của trang  |
| `<h2>` | Tiêu đề cho từng phần       |
| `<h3>` | Tiêu đề nhỏ bên trong `<h2>` |

> Một trang web thường chỉ nên có một `h1` chính. Các phần nhỏ hơn nên dùng `h2`, `h3`.

</v-clicks>

----

# Thẻ đoạn văn

<v-clicks>

- Thẻ `p` dùng để viết đoạn văn bản.
- Ví dụ:
```html
<p>
  Xin chào, tôi là Lan. Tôi đang học HTML để có thể tạo ra trang web đầu tiên
  của mình.
</p>
```

> Lưu ý: Trong HTML, khi mình xuống dòng trong code, trình duyệt không nhất thiết hiển thị xuống dòng giống như trong file.

```html
<p>
  Xin chào.
  Tôi đang học HTML.
  Tôi rất thích lập trình web.
</p>
```

</v-clicks>

---

# Thẻ làm nổi bật chữ

<v-clicks>

- Có 2 thẻ quan trọng: `<strong>`, `<em>`.
```html
<p>
  Tôi đang học <strong>HTML</strong> và cảm thấy môn này rất <em>thú vị</em>.
</p>
```
- `strong`: chữ đậm.
- `em`: chữ nghiêng.

> Về ý nghĩa, `strong` dùng cho nội dung quan trọng, `em` dùng cho nội dung cần nhấn mạnh.

</v-clicks>

---

# Thẻ xuống dòng

<v-clicks>

- Thẻ `br` dùng để xuống dòng trong cùng một đoạn nội dung.
```html
<p>
  Nguyễn Văn A<br>
  Email: nguyenvana@example.com<br>
  Số điện thoại: 0123456789
</p>
```
- Nên dùng br khi nội dung cần xuống dòng ngắn, ví dụ:
    - Địa chỉ.
    - Thông tin liên hệ.
    - Bài thơ.
    - Dòng thông tin cá nhân.
> Lưu ý: `br` là thẻ không cần thẻ đóng. Không nên lạm dụng `br` để tạo khoảng cách lớn. Sau này khoảng cách sẽ dùng CSS.

</v-clicks>

---

# Thẻ đường kẻ ngang

<v-clicks>

- Thẻ `hr` tạo một đường kẻ phân cách nội dung.
```html
<h2>Giới thiệu</h2>
<p>Tôi là người mới học HTML.</p>

<hr>

<h2>Sở thích</h2>
<p>Tôi thích đọc sách và nghe nhạc.</p>
```
> `hr` giúp chia các phần nội dung rõ ràng hơn.

</v-clicks>

---

# Danh sách không thứ tự `ul`, `li`

<v-clicks>

- Danh sách không thứ tự dùng khi các mục không cần đánh số.
```html
<h2>Sở thích của tôi</h2>

<ul>
  <li>Nghe nhạc</li>
  <li>Đọc sách</li>
  <li>Chơi thể thao</li>
  <li>Học lập trình</li>
</ul>
```
| Thẻ    | Ý nghĩa                         |
| ------ | ------------------------------- |
| `<ul>` | Bao ngoài danh sách không thứ tự |
| `<li>` | Một mục trong danh sách          |

> Kết quả trên trình duyệt thường có dấu chấm đầu dòng.

</v-clicks>

---

# Danh sách có thứ tự `ol`, `li`

<v-clicks>

- Danh sách có thứ tự dùng khi các mục cần đánh số.
```html
<h2>Các bước học HTML</h2>

<ol>
  <li>Tạo file HTML</li>
  <li>Viết cấu trúc cơ bản</li>
  <li>Thêm tiêu đề và đoạn văn</li>
  <li>Mở file bằng trình duyệt</li>
</ol>
```
| Thẻ    | Ý nghĩa                       |
| ------ | ----------------------------- |
| `<ol>` | Bao ngoài danh sách có thứ tự |
| `<li>` | Một mục trong danh sách       |

> Kết quả trên trình duyệt thường có số thứ tự: 1, 2, 3, 4.

</v-clicks>

---

# Thực Hành

Tạo trang giới thiệu bản thân: `about-me.html`

Nội dung cần có:

    - Tên học viên bằng h1.
    - Một đoạn giới thiệu bản thân bằng p.
    - Tên được làm nổi bật bằng strong.
    - Một từ/cụm từ được nhấn mạnh bằng em.
    - Thông tin liên hệ có dùng br.
    - Một đường phân cách bằng hr.
    - Danh sách sở thích bằng ul.
    - Danh sách mục tiêu học tập bằng ol.

---

# Thực Hành

Trang kế hoạch học tập: `learning-plan.html`

Gồm có các thông tin:
  - Lý do tôi học lập trình web.
  - Những kỹ năng tôi muốn học.
  - Lộ trình học tập.
  - Mục tiêu sau 1 tháng.