Tổng hợp tính năng hiện có trong web ENGO

Dựa trên phiên bản mới nhất của file web hiện tại.

1. Tài khoản và xác thực
Đăng ký tài khoản mới.
Đăng nhập bằng email và mật khẩu.
Chọn vai trò khi đăng nhập.
Khôi phục phiên đăng nhập khi tải lại trang.
Đăng xuất tài khoản.
Hiển thị tên và avatar theo người dùng.
Tài khoản được xác thực qua Node.js và MySQL.

Các vai trò gồm:

Học sinh
Giáo viên
Phụ huynh
Quản trị viên
2. Dashboard theo vai trò

Sau khi đăng nhập, hệ thống tự mở đúng khu vực:

Học sinh: Dashboard học tập.
Giáo viên: Không gian giáo viên.
Phụ huynh: Theo dõi học tập.
Quản trị viên: Quản lý dữ liệu.

Dashboard học sinh hiển thị:

Số bài đã hoàn thành.
Điểm trung bình.
Chuỗi ngày học.
Thời gian ôn tập.
Bài tập cần hoàn thành.
Kết quả gần đây.
Tiến độ mục tiêu.
3. Giao diện sáng và tối
Có nút chuyển chế độ sáng/tối.
Hoạt động cả ở trang đăng nhập và bên trong hệ thống.
Ghi nhớ chế độ đã chọn bằng trình duyệt.
Chế độ tối áp dụng cho bảng, thẻ, form, flashcard, bài kiểm tra và cửa sổ thông báo.
4. Kế hoạch học mỗi ngày

Học sinh có 3 nhiệm vụ:

Ôn flashcard.
Hoàn thành một bài luyện.
Hoàn thành một phiên tập trung.

Hệ thống có:

Đánh dấu nhiệm vụ hoàn thành.
Tính phần trăm mục tiêu ngày.
Cộng XP theo từng nhiệm vụ.
Tự làm mới kế hoạch theo ngày.
5. Làm bài kiểm tra
Câu hỏi trắc nghiệm.
Câu hỏi điền từ.
Viết lại câu.
Đọc hiểu.
Phát âm.
Từ vựng và ngữ pháp.
Đồng hồ đếm ngược.
Di chuyển qua lại giữa các câu.
Danh sách câu đã làm và chưa làm.
Tự lưu đáp án.
Kiểm tra đáp án từng câu.
Hiện lời giải.
Tự chấm điểm khi nộp.
Hiện số câu đúng, sai và số lần làm.
Làm lại bài kiểm tra.
6. Ôn tập thông minh

Hệ thống ghi nhận lỗi sau mỗi bài và:

Tính tỷ lệ trả lời đúng.
Ghi nhận điểm cao nhất.
Đếm số lượt luyện.
Xác định kỹ năng có nhiều lỗi.
Đề xuất kỹ năng cần ôn trước.
Hiển thị mức độ cần cải thiện.
7. Flashcard tương tác
Lật mặt trước và mặt sau.
Hiển thị từ, phiên âm, nghĩa và ví dụ.
Chuyển thẻ trước hoặc sau.
Trộn thứ tự thẻ.
Học lại bộ thẻ.
Đánh dấu “Đã nhớ”.
Đánh dấu “Cần ôn lại”.
Theo dõi số thẻ đã nhớ.
Có nhiều bộ thẻ theo Unit và phát âm.
8. Phòng tập trung
Đồng hồ học tập 25 phút.
Nghỉ ngắn 5 phút.
Nghỉ dài 15 phút.
Bắt đầu, tạm dừng và đặt lại đồng hồ.
Ghi nhận số phiên tập trung.
Tính tổng thời gian đã học.
Cộng XP khi hoàn thành phiên học.
9. Thành tích và trò chơi hóa
Hệ thống XP.
Cấp độ người học.
Thanh tiến trình lên cấp.
Chuỗi ngày học.
8 huy hiệu thành tích.

Ví dụ:

Hoàn thành bài đầu tiên.
Đạt từ 8 điểm.
Đạt điểm 10.
Hoàn thành 3 lượt luyện.
Hoàn thành phiên tập trung.
Hoàn thành mục tiêu ngày.
Đạt 100 XP.
Học liên tục 7 ngày.
10. Trung tâm thông báo
Thông báo bài luyện mới.
Nhắc duy trì chuỗi học.
Thông báo tính năng mới.
Hiển thị chấm đỏ khi còn thông báo chưa đọc.
Đánh dấu tất cả là đã đọc.
11. Khu vực giáo viên
Xem số lượng câu hỏi.
Xem số học sinh.
Xem tỷ lệ hoàn thành.
Xem danh sách bài kiểm tra.
Xem tiến độ theo lớp.
Chọn file DOCX để nhập câu hỏi.
Mở form tạo bài kiểm tra.
Chọn lớp, thời gian, số lần làm và chế độ hiện đáp án.
Tạo mã QR chia sẻ bài.
12. Khu vực phụ huynh
Xem tiến độ học của học sinh.
Xem số bài đã hoàn thành.
Xem điểm trung bình.
Xem thời gian học.
Xem bài sắp đến hạn.
Xem điểm theo từng kỹ năng.
Xem tình trạng các bài tập gần đây.
13. Khu vực quản trị viên

Quản lý tài khoản MySQL:

Xem danh sách tài khoản.
Thêm tài khoản.
Duyệt tài khoản đang chờ.
Khóa tài khoản.
Mở khóa tài khoản.
Xóa tài khoản.
Tìm kiếm tài khoản.
Chọn vai trò và trạng thái tài khoản.

Quản lý dữ liệu nội dung:

Xem câu hỏi.
Xem bài kiểm tra.
Xem nhật ký hoạt động.
Tìm kiếm dữ liệu.
Nhập file JSON.
Xuất dữ liệu JSON.
Sao lưu dữ liệu.
Khôi phục dữ liệu mẫu.
14. Chia sẻ và tiện ích
Tạo mã QR minh họa.
Sao chép đường link bài tập.
In báo cáo kết quả.
Hiển thị thông báo nhỏ khi thao tác thành công.
Menu sidebar trên máy tính.
Menu thu gọn trên điện thoại.
Giao diện responsive cho máy tính bảng và điện thoại.
Phần đã kết nối dữ liệu thật
Đăng ký.
Đăng nhập.
Phiên đăng nhập.
Đăng xuất.
Quản lý tài khoản.
Duyệt, khóa, mở khóa và xóa tài khoản.
Phần hiện còn lưu cục bộ hoặc dữ liệu minh họa
Câu hỏi và bài kiểm tra.
Kết quả học tập.
Đáp án đang làm.
XP và huy hiệu.
Kế hoạch ngày.
Flashcard.
Thời gian tập trung.
Thông báo.
Báo cáo lớp học.
Nhập DOCX và tạo đề.
