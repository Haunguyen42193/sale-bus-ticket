# sale-bus-ticket
1. Giới thiệu đề tài

Sale bus ticket là đề tài về xây dựng hệ thống bán vé xe khách để sử dụng trong lĩnh vực giao thông, hệ thống có thể giúp đảm bảo sự thuận tiện cho hành khách trong việc di chuyển, nâng cao sự tiện lợi cho đời sống sinh hoạt cộng đồng.

2. Các bước thực hiện đề tài

- Thiết kế lượt đồ use case.
- Thiết kế sơ đồ lớp.
- Thiết kế giao diện cho ứng dụng.
- Xây dựng các chức năng cho website bán hàng.
- Viết test case kiểm tra các chức năng hệ thống.
- Đảm bảo tính bảo mật cho website bằng cách sử dụng các công nghệ mã hóa dữ liệu.
- Thực hiện thử nghiệm trên website để kiểm tra các lỗi và đảm bảo tính ổn định.

3. Thiết kế hệ thống

3.1 Lược đồ use case

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/de70337e-00a5-4430-8821-d0ff19e2e3a2)

3.1 Sơ đồ lớp

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/33e2aae8-ea5f-4ff0-bd6a-45358c1bd154)

3.2 Lược đồ cơ sở dữ liệu

- Users (UserID, Username, Password, UserRole, Name)
- Ticket (TicketID, #UserID, #TripID, #CustomerID, Chair, Status, PrintDate)
- Customer (CustomerID, Name, Phone)
- Trip (TripID, DepartingAt, ArrivingAt, #CarID, #RouteID)
- Car (CarID, LisensePlate, Name, SumChair)
- Route (RouteID, Start, End)

3.3 Mối quan hệ giữa các thực thể

- Mối quan hệ giữa bảng Users và Ticket: Một User có thể quản nhiều Ticket và một Ticket thuộc một User.
- Mối quan hệ giữa bảng Ticket và Customer: Một Customer có nhiều Ticket và một Ticket thuộc một Customer.
- Mối quan hệ giữa bảng Ticket và Trip: Một Trip có nhiều Ticket và một Ticket thuộc một Trip.
- Mối quan hệ giữa bảng Trip và Car: Một Car có thể chạy nhiều Trip và một Trip thuộc một Car.
- Mối quan hệ giữa bảng Trip và Route: Một Route có nhiều Trip và một Trip thuộc một Route.

4. CHức năng]

4.1 Mô tả chức năng

4.1.1 Chức năng của Admin
- Thêm chuyến đi.
- Sửa chuyến đi.
- Xóa chuyến đi.
- Tìm kiếm chuyến đi.
4.1.1 Chức năng của Staff
- Tìm vé theo chuyến.
- Tìm vé.
- Đổi vé theo chuyến hoặc đổi chuyến.
- Hủy vé.
- Đặt vé.
- Bán vé.
- Xuất vé.

5. Giao diện

- Đăng nhập

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/4c987cb2-1ce9-4558-9e36-6d52f65ed720)

- Trang chủ

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/42eefcd4-50c9-4a1a-a574-15da452dcc97)

- Trang quản chuyến đi

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/2a3365e2-09a4-4024-ae6b-a6a62d65a7a5)

- Trang quản lý vé xe

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/f58bd1a8-af0c-4f8b-a717-467b34d5ec2d)

- Trang đặt vé

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/bd9fd090-5b51-4b24-876a-7a5a80f12a90)

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/82856e22-8d9e-494a-ad76-1be0fc26a0ce)

- Trang bán vé

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/9e62daa5-19bd-4dc6-822f-501d6773bbb3)

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/620c74dd-fc1d-4504-b1ff-c74dc9745202)

- Xuất vé

![image](https://github.com/Haunguyen42193/sale-bus-ticket/assets/92702518/e1677898-e8c4-40f6-975f-fd73edba80d6)

