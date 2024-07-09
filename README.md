# Ứng dụng Quản lý Thông tin Thanh Thiếu Niên

## Giới thiệu

Ứng dụng Quản lý Thông tin Thanh Thiếu Niên là một phần mềm quản lý các thông tin về thanh thiếu niên trong một khu vực hoặc tổ chức. Ứng dụng cung cấp các chức năng như thêm mới, xóa, tìm kiếm, thống kê và quản lý thông tin của thanh thiếu niên.

## Các chức năng chính

- **Thêm mới thanh thiếu niên**: Cho phép thêm mới thông tin thanh thiếu niên với các trường dữ liệu như ID, Họ tên, Giới tính, Ngày sinh, Nơi ở, Hộ khẩu thường trú, Thông tin người giám hộ, Liên lạc người giám hộ, Tình trạng gia đình.
- **Xóa thanh thiếu niên**: Cho phép xóa thông tin của thanh thiếu niên từ danh sách.
- **Tìm kiếm thanh thiếu niên**: Cho phép tìm kiếm thanh thiếu niên theo tên hoặc theo độ tuổi.
- **Thống kê**: Cung cấp thông tin thống kê về số lượng thanh thiếu niên nam và nữ trong danh sách.
- **Đăng nhập**: Yêu cầu người dùng đăng nhập để truy cập vào ứng dụng.

## Yêu cầu hệ thống

- JDK 8 trở lên
- Một môi trường phát triển Java như IntelliJ IDEA hoặc Eclipse

## Hướng dẫn cài đặt và chạy chương trình

1. **Clone repository**:
    ```bash
    git clone <repository_url>
    ```
2. **Nhập project vào môi trường phát triển của bạn (IntelliJ IDEA hoặc Eclipse)**.

3. **Cấu trúc thư mục**:
    - `qlYouth_swing/qlYouth/`: Chứa các file chính của ứng dụng
        - `controller/`: Chứa các lớp điều khiển (LoginController.java, YouthController.java)
        - `entity/`: Chứa các lớp thực thể (User.java, Youth.java, YouthXML.java)
        - `func/`: Chứa các lớp chức năng (UserFunc.java, YouthFunc.java)
        - `utils/`: Chứa các lớp tiện ích (FileUtils.java)
        - `view/`: Chứa các lớp giao diện người dùng (LoginView.java, YouthView.java)

4. **Chạy chương trình**:
    - Mở lớp `App.java` trong thư mục `qlYouth_swing/qlYouth` và chạy lớp này để khởi động ứng dụng.

## Hướng dẫn sử dụng

### Đăng nhập

- Khi khởi động ứng dụng, người dùng sẽ được yêu cầu đăng nhập. Sử dụng thông tin đăng nhập hợp lệ để truy cập vào ứng dụng.

### Thêm mới thanh thiếu niên

1. Nhập các thông tin cần thiết vào các trường tương ứng.
2. Nhấn nút "Thêm" để lưu thông tin.

### Xóa thanh thiếu niên

1. Chọn một hàng trong bảng danh sách thanh thiếu niên.
2. Nhấn nút "Xóa" để xóa thông tin.

### Tìm kiếm thanh thiếu niên

- **Tìm kiếm theo tên**:
    1. Nhấn nút "Tìm kiếm".
    2. Nhập từ khóa tìm kiếm.
    3. Kết quả tìm kiếm sẽ được hiển thị trong một bảng mới.
- **Tìm kiếm theo độ tuổi**:
    1. Nhấn nút "Tìm kiếm theo tuổi".
    2. Nhập tuổi bắt đầu và tuổi kết thúc.
    3. Kết quả tìm kiếm sẽ được hiển thị trong một bảng mới.

### Thống kê

- Nhấn nút "Thống kê" để hiển thị thông tin thống kê về số lượng thanh thiếu niên nam và nữ.

## Liên hệ

Nếu có bất kỳ câu hỏi hay vấn đề gì về ứng dụng, vui lòng liên hệ qua email: [22010076@st.phenikaa-uni.edu.vn].

