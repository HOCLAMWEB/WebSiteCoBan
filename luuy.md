font-family: 'Lobster', cursive, Arial, sans-serif;
font chữ đẹp 

add_filter('woocommerce_currency_symbol', 'change_existing_currency_symbol', 10, 2);
 
function change_existing_currency_symbol( $currency_symbol, $currency ) {
 switch( $currency ) {
 case 'VND': $currency_symbol = 'VNÐ'; break;
 }
 return $currency_symbol;
}   /// bỏ vào đường link    "C:\xampp\htdocs\huyen\wp-content\themes\flatsome\functions.php" để chuyển đổi từ đồng thành VND.


Thay chữ quick-view ở trên sản phẩm  trong file php. ở đường link phía dưới:
C:\xampp\htdocs\huyen\wp-content\themes\flatsome\inc\extensions\flatsome-wc-quick-view

<div>
<h3> đôi font chữ </h3>
Thuộc tính text-transform trong CSS cho phép bạn thay đổi các hiển thị đoạn text bạn muốn thành chữ "IN HOA" hoặc chữ "thường" hoặc viết hoa "Chữ Cái Đầu".

HTML:
<p id="textid1">BẠn muốn hiển thị chữ IN HOA hay chữ thường hay viết Hoa Tất Cả Các Chữ Cái Đầu</p> 

Các giá trị của thuộc tính.
 - uppercase: hiển thị tất cả thành chữ IN HOA
CSS:
#textid1 {
text-transform: uppercase;
}
Kết quả:
BẠN MUỐN HIỂN THỊ CHỮ IN HOA HAY CHỮ THƯỜNG HAY VIẾT HOA TẤT CẢ CÁC CHỮ CÁI ĐẦU

 - lowercase: hiển thị tất cả thành chữ thường.
CSS:
#textid1 {
text-transform: lowercase;
}
Kết quả:
bạn muốn hiển thị chữ in hoa hay chữ thường hay viết hoa tất cả các chữ cái đầu

 - capitalize: Viết hoa tất cả chữ cái đầu.
CSS:
#textid1 {
text-transform: capitalize;
}
</div>

<div class="form dang ki thong tin"><h2>form đăng kí thông tin </h2>
<div class="vc_column-inner "><div class="wpb_wrapper">
<div class="qodef-custom-font-holder" style="font-family: sans-serif;font-size: 22px;font-weight: 700;text-align: center;color: #000000" data-font-size="22">
	Liên hệ với chúng tôi</div>
	<div class="wpb_text_column wpb_content_element ">
		<div class="wpb_wrapper">
			            <div class="block_price login-devnet">
                <form action="" method="post" class="form_price">
                    <div style="display:none" class="notification_popup"></div>
                    <input type="hidden" class="goto" name="goto" value="">
                    <div class="block_rm">
                        <div class="group-from">
                            <input type="hidden" class="name_rm" name="name_rm" value="Liên hệ với chúng tôi 0đ">
                            <input type="hidden" class="price_rm" name="price_rm" value="0">
                            <input type="hidden" class="commission_rm" name="commission_rm" value="">
                            <input type="hidden" class="bonus_rm" name="bonus_rm" value="">
                            <div class="panel-default">
                                <div class="block-rm">
                                    <div class="rm-form-group">
                                        <input required="" type="text" name="fullname_rm" value="" placeholder="Họ và tên:" class="rm-form-control fullname_rm">
                                    </div>
                                    <div class="rm-form-group">
                                        <input required="" type="email" name="email_rm" value="" placeholder="E-Mail:" class="rm-form-control email_rm">
                                    </div>
                                    <div class="rm-form-group">
                                        <input required="" type="number" name="phone_rm" value="" placeholder="Số điện thoại:" class="rm-form-control phone_rm">
                                    </div>
                                    <div class="rm-form-group">
                                        <input required="" type="text" name="address_rm" value="" placeholder="Địa chỉ:" class="rm-form-control address_rm">
                                    </div>
                                    <div class="rm-form-group">
                                        <textarea type="text" name="note_rm" placeholder="Ghi chú:" class="rm-form-control note_rm"></textarea>
                                    </div>
                                </div>
                            </div>
                            <div class="order-btn">
                                <input type="submit" name="purchase_rm" value="Đăng ký" class="btn order-price order_btn">
                            </div>
                        </div>
                    </div>
                </form>
            </div>
            <style>
                .block_rm{padding: 10px}
                .order-price{background-color: #52b400; color: #ffffff;font-weight: 700;}
                .order-btn{text-align: center;}
                .btn.order-price.order_btn{ background-color: #f1c110;
                color: black; }
            </style>
</div></div>
</div>

<div>
	<h4> các loại text căn lề </h4>
	left	Aligns the text to the left	
right	Aligns the text to the right	
center	Centers the text	
justify	:cân đều 2 bên vd |bxbgkfsdgbd|	
initial	Sets this property to its default value. Read about initial	
inherit	Inherits this property from its parent element. Read about inherit	
</div>
<div>
	<h3> font chữ chuẩn</h3>
	body{
    font-size: 13px;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif!important;
}
</div>

<h4> cách làm form liên hệ để gửi đến email </h4>
https://thachpham.com/wordpress/wp-plugin/contact-form-7-tao-form-chuyen-nghiep.html

<h3> smtp </h3>
https://thachpham.com/wordpress/wordpress-tutorials/smtp-gmail-wordpress.html

HOST:smtp.gmail.com
POST:465;
USER:EMAIL
PASS: MÃ BẢO MẬT 2 LỚP CỦA EMAIL

<h2> plugin sao chép trang web </h2>
duplicator
cài đặt plugin đó vào trang web càn copy
............. sau đó sẽ sinh ra 2 file tải về
vào xam tạo thư mục rồi bỏ 2 trong đó 
tiếp tục tạo database ..........
xóa file đã dup từ trang khác vào tool 
còn dup bản mới thì vào package

<h2> link lấy ifram fanpage fb</h2>
https://developers.facebook.com/docs/plugins/page-plugin


<h2> plugin dịch </h2>
Loco Translate
<h3> SUBIZ</h3>

TEN O TRONG KHUNG
<label> 
    [text* your-name placeholder'Họ và Tên'] </label>

<label> 
    [email* your-email placeholder 'email'] </label>

<label>
    [textarea your-message placeholder'Nội Dung'] </label>
<div class="lienhegui">
[submit "GỬI"]</div>

<h3> sửa chữ UPDATE CART<h3>
/domains/mixushop.vn/public_html/wp-content/themes/bignet/woocommerce/cart/cart.php
<h3>sửa chữ view card<h3>
/domains/mixushop.vn/public_html/wp-content/plugins/woocommerce/includes/wc-template-functions.php
<h2  sủa chữa continue shopping</h2>
C:\xampp\htdocs\huyen\wp-content\themes\flatsome\woocommerce\cart\continue-shopping.php:
<h2> sửa chữ proceed to chckout</h2>
C:\xampp\htdocs\huyen\wp-content\plugins\woocommerce\templates\cart\proceed-to-checkout-button.php:
C:\xampp\htdocs\huyen\wp-content\plugins\woocommerce\templates\checkout\form-coupon.php:
