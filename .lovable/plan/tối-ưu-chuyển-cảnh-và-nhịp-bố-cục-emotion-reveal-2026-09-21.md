# Tối ưu chuyển cảnh và nhịp bố cục Emotion Reveal

## Mục tiêu
- Tiếp tục từ mã nguồn `emotion-reveal` hiện tại.
- Làm phần cuối intro trùng khớp hoàn toàn với khung đầu của thiệp, không có nhảy ảnh, đổi tỷ lệ hay chớp nền.
- Rút gọn khoảng trống giữa các phần để nội dung liền mạch nhưng vẫn dễ đọc trên điện thoại và máy tính.

## Thực hiện
1. Đưa toàn bộ mã nguồn và ảnh/nhạc hiện tại của dự án vào bản đang mở.
2. Đồng bộ intro và ảnh đầu trang bằng cùng ảnh, vị trí cắt, lớp phủ và kích thước khung.
3. Cho hai lớp giao nhau trong một khoảng ngắn, dùng chuyển động chỉ dựa trên opacity/transform để tránh giật khung hình.
4. Tiền tải ảnh đầu trang, giữ intro tồn tại đến hết chuyển cảnh và chỉ bật nội dung/trình điều khiển sau khi cảnh đã ổn định.
5. Điều chỉnh nhịp xuất hiện chữ theo từng câu; bỏ các hiệu ứng blur nặng và khoảng dừng gây cảm giác đứt đoạn.
6. Chuẩn hóa khoảng cách dọc, khoảng cách tiêu đề–nội dung, lưới ảnh và các khối thông tin trên mobile/desktop.
7. Kiểm tra trực tiếp toàn bộ intro, điểm nối sang trang chính và các đoạn cuộn ở hai kích thước màn hình; sửa mọi hiện tượng chớp, tràn hoặc khoảng trắng quá lớn.

## Giới hạn
- Giữ nguyên nội dung, ảnh, nhạc, màu sắc và các chức năng hiện có.
- Không thêm tính năng mới hoặc thay đổi thông tin thiệp cưới.
