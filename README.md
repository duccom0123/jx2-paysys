👋 Xin chào, tôi là @duccom0123

Đây là paysys linux cho jx2 mà tôi đã chia sẻ tại:
https://clbgameviet.com/threads/12243-Share-paysys-jx2-linux.html
Nay lưu trữ tại đây.

Vì CentOS 7 sẽ chính thức đạt Ngày Kết Thúc Vòng Đời (EOL) vào ngày 30 tháng 6 năm 2024. Sau ngày này, hệ điều hành sẽ không còn nhận được bất kỳ bản cập nhật bảo mật, vá lỗi hay hỗ trợ nào từ Red Hat và cộng đồng phát triển.

Nên tôi chỉ hướng dẫn cài trên alma linux 9.

⚡ Sử dụng trên alma linux 9:

dnf update -y
dnf install mariadb-connector-c-devel.x86_64
rm -rf /usr/lib64/libmysqlclient.so.18
ln -s /usr/lib64/libmysqlclient.so /usr/lib64/libmysqlclient.so.18

gõ các lệnh trên để cài đặt môi trường cho paysys

Chia sẻ miễn phí mong ae đừng mang đi bán hoặc lừa đảo...........