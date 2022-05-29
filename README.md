#ShopPet
# Phân tích trâng web bán đồ thú cưng
## Dự án không lớn

1. Đối tượng dùng
A. Super Admin
Aa. Admin
B. Người bán
2. Chức Năng Từng Phần
 A. Super Admin
- Quản lý nội dung : banner, thông tin mặt hàng, loại sản phẩm, bài viết
- Quản lý người dùng
- Quản lý file
- Quản lý voucher
Aa. Admin
- Đăng bài 
- Kiểm tra chất lượng ( bài viết, đánh giá sản phẩm)
C. Người mua
- Tìm kiếm vật phẩm 
- Đánh giá, nhận xét 
- Xem danh sách ( liên quan đến keyword , số lượng còn lại)
- Báo cáo vi phạm ( lừa đảo, sai mặt hàng, không phản hồi )
3.Phân tích chức năng
- Super Admin : giá bán , file, tạo voucher
- Admin : Báo hóa đơn , báo sản lượng, sản phẩm
- Người mua : tên vật phẩm , địa điểm ,hình thức thanh toán , chọn voucher , yêu cầu thêm 


| Tác Nhân | Admin |
| ------ | ------ |
| Mô Tả | Đăng Bài Bán Hàng |
| Kích Hoạt | Admin ấn vào nút "Đăng Bài" trong menu admin  |
| Đầu Vào | Tên Sản Phẩm<br>Giá Bán ra<br>Số lượng hiện có   |
| Trình tự xử lý |  |
| Đầu ra | Đúng: Hiện thị trang bán hàng và thông báo thành công<br>Sai:Hiển thị sai trang đăng nhập và thông báo thất bại |
| Lưu ý| Kiểm tra ô nhập không được để trống bằng javaScript |


