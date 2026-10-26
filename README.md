# Gym AI

Bài tập gym theo cấp độ (Người mới, Trung cấp, Nâng cao), có ảnh minh họa, tạo giáo án, ghi tạ/reps và gợi ý tăng tạ.

Phiên bản này bổ sung các luồng quản lý dữ liệu lấy cảm hứng từ OpenGym: đánh dấu bài yêu thích, lọc nhanh trong thư viện, xuất/nhập toàn bộ dữ liệu dạng JSON, xóa dữ liệu cục bộ có xác nhận, double progression theo khoảng reps, 1RM ước tính và tính đĩa tạ đòn. Ứng dụng vẫn chạy độc lập, không cần máy chủ và dữ liệu tập luyện được lưu trong trình duyệt.

## Các file
- index.html: toàn bộ app, đã gồm dữ liệu 876 bài tập và logic ứng dụng
- manifest.json: cấu hình để cài lên màn hình chính
- sw.js: cho phép dùng offline sau lần mở đầu

## Sao lưu dữ liệu

Mở tab **Cài đặt** trong ứng dụng để xuất tệp JSON. Khi chuyển máy hoặc khôi phục, chọn **Nhập dữ liệu** và chọn tệp sao lưu đó. Nên sao lưu trước khi xóa dữ liệu trình duyệt.

## Cách đưa lên GitHub Pages
1. Tạo repo mới, bật Public.
2. Upload cả 3 file trên vào thư mục gốc của repo, rồi Commit.
3. Vào Settings → Pages, chọn Branch main, thư mục / (root), Save.

Dữ liệu bài tập: free-exercise-db (Unlicense, public domain). Ảnh được tải từ kho đó.
