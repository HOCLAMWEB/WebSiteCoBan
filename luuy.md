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
