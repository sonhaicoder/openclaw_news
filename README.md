# 🚀 Tech News Website

Một website đơn giản hiển thị tin tức công nghệ từ các nguồn uy tín (GenK, ICTNews, Thanh Niên, VnExpress).

## 📌 Tính năng
- **Hiển thị tin tức** từ các nguồn công nghệ hàng đầu.
- **Cập nhật tự động** mỗi 30 phút.
- **Giao diện thân thiện** (responsive).
- **Dễ dàng deploy** lên GitHub Pages, Netlify, hoặc Vercel.

## 📂 Cấu trúc thư mục
```
tech-news-website/
├── index.html          # Trang web chính
├── README.md           # Hướng dẫn sử dụng
└── .gitignore          # Danh sách file không đẩy lên GitHub
```

## 🚀 Cách deploy lên GitHub Pages

### Bước 1: Tạo repository trên GitHub
1. Truy cập [GitHub](https://github.com) và tạo một repository mới.
2. Đặt tên là `tech-news-website` (hoặc tên khác tùy ý).

### Bước 2: Clone repository về máy
```bash
cd ~
git clone https://github.com/[username]/tech-news-website.git
cd tech-news-website
```

### Bước 3: Copy code vào thư mục
```bash
cp -r /home/openclaw/.openclaw/workspace/tech-news-website/* ./
```

### Bước 4: Commit và push lên GitHub
```bash
git add .
git commit -m "Initial commit: Create Tech News Website"
git push origin main
```

### Bước 5: Enable GitHub Pages
1. Vào **Settings** của repository.
2. Chọn **Pages** ở menu bên trái.
3. Chọn **Branch: main** và **Folder: / (root)**.
4. Nhấn **Save**.

### Bước 6: Truy cập website
Sau vài phút, website của anh sẽ được deploy tại:
```
https://[username].github.io/tech-news-website/
```

## 🔄 Cách cập nhật tin tức
- Website sẽ **tự động cập nhật** tin tức mỗi 30 phút.
- Nếu anh muốn cập nhật thủ công, chỉ cần **refresh** trang web.

## 📌 Các nguồn tin tức được sử dụng
| Nguồn       | URL                     | RSS Feed                     |
|-------------|-------------------------|------------------------------|
| GenK        | https://genk.vn         | https://genk.vn/rss          |
| ICTNews     | https://ictnews.vn      | https://ictnews.vn/rss       |
| Thanh Niên  | https://thanhnien.vn   | https://thanhnien.vn/rss/cong-nghe.rss |
| VnExpress   | https://vnexpress.net  | https://vnexpress.net/rss/tin-moi-nhat.rss |

## 🛠️ Công nghệ sử dụng
- **HTML5**, **CSS3**, **JavaScript** (ES6+)
- **RSS Feed** để lấy tin tức
- **CORS Proxy** (api.allorigins.win) để tránh lỗi CORS

## 📝 Ghi chú
- Website này chỉ mang tính chất **tham khảo** và **học tập**.
- Nếu anh muốn thêm nguồn tin tức khác, hãy chỉnh sửa file `index.html` và thêm vào danh sách `newsSources`.
- Để deploy lên các nền tảng khác (Netlify, Vercel), anh có thể tham khảo hướng dẫn tương ứng của họ.

## 🌟 Tính năng nâng cao (nếu anh muốn)
- Thêm **tìm kiếm tin tức** theo từ khóa.
- Thêm **thể loại** (Công nghệ, Khoa học, AI, v.v.).
- Thêm **chế độ tối** (dark mode).
- Thêm **lưu trữ tin tức** vào localStorage để xem offline.

---