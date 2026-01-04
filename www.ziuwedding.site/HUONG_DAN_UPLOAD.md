# Hướng dẫn Upload Website Lên Hosting Để Chia Sẻ Link

## ✅ Đã sửa xong:
- ✅ Tất cả ảnh đã dùng URL tuyệt đối (https://w.ladicdn.com/...)
- ✅ Google Maps iframe đã được cấu hình đúng
- ✅ Viewport meta tag đã có sẵn cho mobile responsive

## 📱 Các bước để người khác xem được trên điện thoại:

### Cách 1: Upload lên GitHub Pages (MIỄN PHÍ)

1. **Tạo tài khoản GitHub** (nếu chưa có):
   - Vào https://github.com
   - Đăng ký tài khoản miễn phí

2. **Tạo repository mới**:
   - Click nút "+" → "New repository"
   - Đặt tên: `wedding-invitation` (hoặc tên khác)
   - Chọn "Public"
   - Click "Create repository"

3. **Upload files**:
   - Vào repository vừa tạo
   - Click "uploading an existing file"
   - Kéo thả toàn bộ thư mục `www.ziuwedding.site` vào
   - Commit changes

4. **Bật GitHub Pages**:
   - Vào Settings → Pages
   - Source: chọn "main" branch và "/ (root)"
   - Save
   - Đợi vài phút, bạn sẽ có link: `https://tên-user.github.io/wedding-invitation/myhai.html`

### Cách 2: Upload lên Netlify (MIỄN PHÍ - Dễ nhất)

1. **Vào https://www.netlify.com**
2. **Đăng ký/Đăng nhập** (có thể dùng GitHub account)
3. **Kéo thả thư mục** `www.ziuwedding.site` vào trang Netlify
4. **Nhận link ngay**: `https://random-name.netlify.app/myhai.html`
5. **Có thể đổi tên** trong Site settings → Change site name

### Cách 3: Upload lên Vercel (MIỄN PHÍ)

1. **Vào https://vercel.com**
2. **Đăng ký/Đăng nhập**
3. **Import Project** → Upload folder `www.ziuwedding.site`
4. **Deploy** → Nhận link ngay

### Cách 4: Upload lên Hosting có sẵn (Nếu bạn đã có)

1. **Đăng nhập vào cPanel/FTP**
2. **Upload toàn bộ thư mục** `www.ziuwedding.site` lên thư mục `public_html` hoặc `www`
3. **Truy cập**: `https://tên-domain.com/myhai.html`

## 🔗 Sau khi có link:

1. **Test trên điện thoại**: Mở link trên điện thoại để kiểm tra
2. **Chia sẻ link**: Gửi link cho mọi người qua Zalo, Facebook, SMS...
3. **Link sẽ hoạt động** trên cả máy tính và điện thoại

## ⚠️ Lưu ý quan trọng:

- **Tất cả ảnh đã dùng URL tuyệt đối** từ CDN (w.ladicdn.com) nên sẽ load được từ mọi nơi
- **Google Maps** sẽ hoạt động khi có internet
- **Nhạc nền** cần internet để load
- **Responsive design** đã được cấu hình sẵn cho mobile

## 🎯 Khuyến nghị:

**Netlify** là cách dễ nhất và nhanh nhất:
- Miễn phí
- Không cần cấu hình
- Có HTTPS tự động
- Link đẹp và dễ nhớ

