#Qúa Trình Cài Đặt Mail Server

## Lỗi 1

Miêu tả: Khi đăng nhập vào web mail SquirrelMail bị lỗi sau: SquirrelMail and dovecot imap 13 : Permission denied

Cách sửa: 

setsebool -P httpd_can_network_connect=1

Nếu thay 1 bằng 0 sẽ lại bị lỗi cũ. 

Link tham khảo: http://forums.fedoraforum.org/showthread.php?t=59291

