# ✦ JOURNEY — Animated Travel Gallery

> **Một khung hình. Một chuyển động. Một lời mời lên đường.**  
> Trải nghiệm gallery du lịch toàn màn hình, nơi những điểm đến nổi tiếng được kể bằng hình ảnh, typography thanh lịch và chuyển cảnh mượt mà.

<p align="center">
  <strong>KYOTO · ICELAND · MALDIVES · SWISS ALPS · MARRAKECH · SANTORINI · AFRICA</strong>
</p>

---

## 🌍 Giới thiệu

**Animated Card Opening – Travel Gallery** là website trình chiếu ảnh du lịch dạng slideshow tương tác. Mỗi điểm đến xuất hiện như một tấm thẻ toàn màn hình với ảnh nền, địa danh, tiêu đề, mô tả và nút khám phá. Dải ảnh thu nhỏ, nút điều hướng, bộ đếm và thanh tiến trình giúp bạn dễ dàng di chuyển giữa các khung cảnh.

Giao diện sử dụng tông tối làm nền cho ảnh, điểm nhấn cam ấm và kiểu chữ kết hợp giữa nét cổ điển với phong cách hiện đại. Các thành phần được bố trí thích ứng cho màn hình máy tính, máy tính bảng và điện thoại.

## ✨ Điểm nổi bật

- 🖼️ **Ảnh toàn màn hình** với lớp phủ chuyển sắc để nội dung luôn dễ đọc.
- 🎞️ **Chuyển cảnh hoạt họa** cho nội dung, thumbnail và giao diện mở đầu, sử dụng GSAP.
- 🧭 **Nhiều cách điều hướng:** nút trước/sau, nhấn thumbnail, phím mũi tên và vuốt trên màn hình cảm ứng.
- ⏱️ **Tự động trình chiếu** theo chu kỳ 5 giây; tự dừng khi rê chuột vào gallery và chạy lại khi rê chuột ra.
- 📍 **Bộ đếm slide và thanh tiến trình** cập nhật theo slide hiện tại.
- 📱 **Responsive** với bố cục và kích thước thumbnail được điều chỉnh cho tablet và điện thoại.
- 🛟 **Dự phòng ảnh lỗi:** chuyển sang ảnh thay thế, rồi ảnh SVG nhúng nếu thumbnail vẫn không tải được.
- ⚡ **Không cần build hoặc cài dependency** để mở website.

## 🗺️ Hành trình qua 7 điểm đến

| # | Điểm đến | Tiêu đề | Nội dung |
|---:|---|---|---|
| 1 | **Kyoto, Nhật Bản** | *Ancient Temples* — *of Serenity* | Cổng torii Fushimi Inari và những ngôi chùa vàng giữa sườn núi. |
| 2 | **Iceland** | *Northern Lights* — *Dancing Skies* | Cực quang Bắc Cực vẽ những dải ngọc lục bảo trên bầu trời. |
| 3 | **Maldives** | *Crystal Waters* — *Paradise Found* | Rạn san hô, làn nước trong xanh và thiên nhiên nhiệt đới. |
| 4 | **Swiss Alps** | *Majestic Peaks* — *Crown of Europe* | Những đỉnh núi phủ tuyết và cung đường trượt tuyết Zermatt. |
| 5 | **Marrakech, Morocco** | *Spice Markets* — *of the Medina* | Khu chợ cổ, gia vị, đèn thủ công và sắc màu Bắc Phi. |
| 6 | **Santorini, Greece** | *White & Blue* — *Aegean Dreams* | Làng trắng trên vách đá và hoàng hôn bên biển Aegean. |
| 7 | **Africa** | *Wild Safari* — *Soul of the Savanna* | Đồng bằng Serengeti và khung cảnh cuộc di cư vĩ đại. |

## 🎮 Cách sử dụng

| Thao tác | Kết quả |
|---|---|
| Nhấn **mũi tên trái/phải** trên giao diện | Chuyển về slide trước / tiếp theo |
| Nhấn phím **← / →** | Điều hướng bằng bàn phím |
| Nhấn một **thumbnail** | Mở trực tiếp điểm đến tương ứng |
| **Vuốt ngang** trên thiết bị cảm ứng | Chuyển slide; cần vuốt hơn 50 px |
| Để yên giao diện | Tự chuyển slide sau mỗi 5 giây |
| Rê chuột vào / ra gallery | Tạm dừng / chạy lại tự động trình chiếu |

Nút **“Explore Now”** hiện được trình bày như một nút kêu gọi hành động; dự án chưa gắn hành vi điều hướng hoặc xử lý nhấn cho nút này.

## 🚀 Chạy website

Đây là website tĩnh, không cần cài đặt gói hay biên dịch.

1. Tải hoặc clone thư mục dự án về máy.
2. Mở `index.html` trực tiếp bằng trình duyệt; hoặc dùng tiện ích **Live Server** trong VS Code để chạy trên máy chủ cục bộ.
3. Đảm bảo có kết nối Internet để tải GSAP, Google Fonts và ảnh từ Unsplash.

## 🧱 Công nghệ và tài nguyên

- **HTML5** — cấu trúc giao diện và nội dung trang.
- **CSS3** — bố cục toàn màn hình, hiệu ứng hover, biến giao diện và responsive.
- **JavaScript thuần** — dữ liệu slide, thumbnail, điều hướng, tự chạy và xử lý ảnh dự phòng.
- **GSAP 3.12.5** — timeline và hoạt họa chuyển cảnh, tải từ cdnjs.
- **Google Fonts** — Playfair Display và Poppins.
- **Unsplash** — ảnh minh họa được tham chiếu bằng URL bên ngoài.

> Ảnh, font chữ và thư viện CDN cần kết nối Internet. Nếu các dịch vụ này không khả dụng, một số nội dung bên ngoài có thể không tải được; ảnh có cơ chế dự phòng trong mã nguồn.

## 🗂️ Cấu trúc dự án

```text
.
├── index.html   # Khung giao diện và các phần tử điều khiển
├── style.css    # Giao diện, hoạt họa CSS và breakpoint responsive
├── script.js    # Dữ liệu điểm đến, slideshow và tương tác
└── README.md    # Tài liệu dự án
```

## 🎨 Tùy chỉnh

- **Thêm hoặc sửa điểm đến:** cập nhật các đối tượng trong mảng `slidesData` ở `script.js`. Mỗi slide gồm `place`, `title1`, `title2`, `description` và `image`.
- **Đổi thời gian tự chạy:** chỉnh `AUTO_PLAY_DELAY` trong `script.js` (đơn vị mili giây; mặc định `5000`).
- **Đổi màu, font hoặc kích thước thumbnail:** điều chỉnh các CSS custom properties trong `:root` ở `style.css`.
- **Bổ sung hành vi cho nút “Explore Now”:** thêm sự kiện nhấn phù hợp trong `script.js`.

## 👤 Tác giả

**Lê Phú An**

---

<p align="center">
  <strong>Đi thật xa. Nhìn thế giới theo một góc nhìn khác.</strong><br>
  <sub>Made with curiosity and a love for beautiful places.</sub>
</p>
