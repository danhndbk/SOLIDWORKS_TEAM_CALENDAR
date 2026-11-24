📘 SOLIDWORKS TEAM CALENDAR – Hướng dẫn nhanh

Ứng dụng quản lý lịch sử dụng SolidWorks cho nhóm 3D CAD (小峠, 佐藤, ヤイン, 栃木), tự động chống trùng lịch và đồng bộ qua file DB chung trên server công ty.

1. Chuẩn bị

Trình duyệt: Dùng Google Chrome hoặc Microsoft Edge.

Thư mục DB mặc định: Z:\10.技術CAD\00_共通\11_3DCAD\Solidworks Team Calendar DB

File DB chung: SOLIDWORKS_GROUP_DB.JSON

(Tùy chọn) Đặt ảnh image_30ffc4.png cùng thư mục với file HTML để hiện logo SolidWorks.

2. Đăng nhập & Phân quyền

Lần đầu mở app: Chọn tên của bạn tại màn hình ユーザー選択 (trình duyệt sẽ tự nhớ).

Hàng của bạn (có dấu tích xanh): Được phép Thêm, Sửa, Xóa, Kéo thả.

Hàng người khác: Chỉ xem (閲覧のみ), không thể thao tác nhầm.

Đổi người dùng: Bấm icon đăng xuất cạnh tên ở góc trên bên phải.

3. Liên kết & Đồng bộ DB (Quan trọng)

Thiết lập lần đầu (chỉ làm 1 lần trên mỗi máy):

Bấm DB読込 (hoặc DB変更). Đường dẫn ổ Z:\... sẽ được tự động copy.

Khi cửa sổ chọn file hiện ra, nhấn Ctrl + V → Enter để vào thẳng thư mục DB và chọn file SOLIDWORKS_GROUP_DB.JSON.

Từ các lần mở sau: App tự nhớ file và tự động đọc DB khi khởi động (nếu trình duyệt hỏi quyền bảo mật, chỉ cần bấm OK).

Lưu thay đổi: Bấm DB保存 để ghi đè trực tiếp lên file DB chung.

Đổi file/thư mục DB: Bấm DB変更 (hoặc bấm vào nhãn trạng thái DB trên thanh công cụ).

Lưu nháp trình duyệt: Dùng 一時保存 (lưu tạm) và nút icon đồng hồ (khôi phục).

4. Thao tác lịch

Chế độ xem: 週 (Theo tuần) / 日 (Theo ngày, khung 7:00–19:00). Click trực tiếp vào ngày tháng để mở Calendar Picker.

Thêm / Sửa lịch: Click vào ô trống hoặc nút + trên hàng của bạn (giờ mặc định 08:00 – 10:00, bước nhảy 5 phút, chọn 10 màu phân loại).

Kéo thả: Kéo khối công việc sang ngày khác để dời lịch. Hệ thống tự chặn trùng giờ giữa các thành viên.

5. Màu sắc trạng thái & Giao diện

🕒 予定 (Dự kiến): Màu bạn đã chọn.

🔄 作業中 (Đang làm): Tự động chuyển ĐỎ khi đến giờ.

✔️ 完了 (Đã xong): Tự động chuyển XÁM khi hết giờ.

🌙 Giao diện: Tự động đổi Sáng / Đen tuyền theo cài đặt Windows/trình duyệt.
