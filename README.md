# Hướng dẫn sử dụng plugin

## Thêm sửa xoá sản phẩm khuyến mãi


Click vào KM Product Manager trên thanh điều hướng bên trái trang Quản lý của Wordpress
![image](https://github.com/vietrux/kec/assets/89530449/e8f7532e-08bb-4ecc-8625-42902ece9c40)

Nhìn sang giữa màn hình, chúng ta thấy giao diện của plugin
![image](https://github.com/vietrux/kec/assets/89530449/100a5fde-1b77-4045-ab4c-55ff6a85d1ec)

Ở đây, chúng ta có 2 phần, phần Chỉnh sửa sản phầm khuyến mãi và danh sách những sản phầm đã đuợc thêm

### Phần 1: Chỉnh sửa danh sách sản phẩm khuyến mãi
Ở đây có 3 phần cần phải điền:
- Product Type: Ví dụ :vong-tay ( vòng tay), nhan-nu (nhẫn nữ),...
> đây là loại sản phẩm, tên của từng loại sẽ tuỳ người dùng đặt, những sản phầm cùng loại nên đặt cùng product type

- Product Code: Ví dụ: WO99NN20058
> đây là mã sản phẩm, là mã của sản phầm đang khuyễn mãi mà người dùng muốn hiển thị lên trang

- Product Old Price: Ví dụ: 12900000 (12.900.000 VND)
> đây là giá cũ của sản phẩm

### Phần 2: Danh sách sản phẩm
Danh sách sản phầm sẽ được hiển thị theo loại sản phẩm mà người dùng đặt ở phần 1 ( sản phẩm cùng loại sẽ nằm trên cùng 1 bảng)

Khách hàng có thể sửa sản phẩm hoặc xoá khỏi danh sách bằng 2 nút ở cột cuối cùng của bảng

Khi bấm nút EDIT thông tin về sản phầm sẽ hiển thị ở trên phần 1, khách hàng chỉ cần sửa thông tin và bấm Lưu là đuợc.


## Hiển thị/ sắp xếp sản phẩm khuyến mãi lên trang
Click vào phần Page trên thanh điều hướng, Nhìn vào trang Home và click vào "Edit with Elementor"  
![image](https://github.com/vietrux/kec/assets/89530449/bff200d5-df55-4457-877f-193c9b59c829)

![image](https://github.com/vietrux/kec/assets/89530449/79f0dbac-049a-46f4-8655-a5cafe72797d)

Người dùng cuộn xuống phần muốn đổi, sau đó click vào cái mục đấy
![image](https://github.com/vietrux/kec/assets/89530449/7c1b1a4c-2ecf-42c2-994c-1cffe6f8fb01)

Người dùng nhìn vào bên trái.

Phần shortcode có dạng `[sale_product type="nhan-nu"]`

Nếu người dùng muốn đổi loại sản phầm ở mục đó thì chỉ cần thay đổi thông số của type bằng những loại mà người dùng đã nhập ở phần trước

![image](https://github.com/vietrux/kec/assets/89530449/60d9b715-d48a-4732-84ce-2ca4fb59e7f8)



