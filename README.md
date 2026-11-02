# Không Gian Tâm Hương

Website tĩnh HTML/CSS/JavaScript, tối ưu màn hình điện thoại và máy tính.

## Chạy thử
Mở `index.html` bằng trình duyệt. Chạm vào nút trên lư hương để xem ba nén nhang chuyển động lên lư; bật âm thanh nếu muốn nghe chuông và câu niệm Phật.

## Deploy GitHub Pages
1. Tạo repository GitHub mới, chọn Public.
2. Upload `index.html` và toàn bộ thư mục `assets`.
3. Vào Settings → Pages.
4. Chọn Deploy from a branch → `main` → `/ (root)` → Save.

## Âm thanh
Ba tiếng chuông được tạo bằng Web Audio API. Câu niệm Phật dùng giọng tiếng Việt sẵn có của trình duyệt qua SpeechSynthesis. Giọng đọc phụ thuộc thiết bị; để có giọng nam trầm giống nhau trên mọi máy, cần thay bằng file thu âm/được cấp phép.
