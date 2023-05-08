# PHP.ini Config Window

```ini
[PHP]
post_max_size = 20M
extension_dir = "C:/development/php7.4/ext"
upload_max_filesize = 20M
max_file_uploads = 20

extension=curl
extension=fileinfo
extension=gd2
extension=mbstring
extension=exif      ; Must be after mbstring as it depends on it
extension=mysqli
extension=openssl
extension=pdo_mysql
extension=pdo_sqlite
extension=sqlite3

[curl]
curl.cainfo="C:\php7.4\extras\ssl\cacert.pem"

[openssl]
openssl.cafile="C:\php7.4\extras\ssl\cacert.pem"
openssl.capath="C:\php7.4\extras\ssl\cacert.pem"
```
