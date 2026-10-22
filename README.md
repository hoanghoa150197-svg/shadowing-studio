# Shadowing Studio V2 — website tĩnh

## Triển khai miễn phí trên GitHub Pages
1. Tạo một repository GitHub mới (ví dụ `shadowing-studio`).
2. Tải **toàn bộ nội dung thư mục** này lên nhánh `main` ở thư mục gốc, đặc biệt là `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`.
3. Vào **Settings → Pages → Build and deployment → Deploy from a branch**, chọn `main` và `/(root)`, lưu lại.
4. Mở địa chỉ GitHub Pages được cung cấp trên Edge/Chrome Windows hoặc Safari iPhone.

## Sử dụng
- Nhập bài học bằng CSV hoặc nhập từng câu trong mục Nhập câu.
- Vào Học Shadowing để phát câu, chọn giọng AI Kokoro, hoặc dùng giọng hệ thống dự phòng.
- Lần đầu tạo giọng Kokoro cần mạng để tải thư viện và mô hình, có thể tốn thời gian/dung lượng.
- Nên tạo âm thanh trên Windows rồi dùng tính năng xuất/nhập gói âm thanh để chuyển sang iPhone.
- Dữ liệu bài học lưu cục bộ trong trình duyệt, không tự đồng bộ giữa thiết bị. Hãy sao lưu thường xuyên.

## Giới hạn
- Đây là website tĩnh thật sự, không cần máy chủ ứng dụng hay API trả phí.
- Kokoro chạy trong trình duyệt qua CDN/model từ bên thứ ba, vì vậy cần Internet lần đầu và có thể không chạy trên một số thiết bị; không bảo đảm offline hoàn toàn cho AI.
- Các tính năng phát âm thanh cần thao tác của người dùng; trình duyệt iPhone có thể hạn chế phát nền.
- Gói JSON có âm thanh có thể khá lớn.
