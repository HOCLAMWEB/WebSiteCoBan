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
