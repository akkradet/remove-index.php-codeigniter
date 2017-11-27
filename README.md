# remove-index.php-codeigniter
วิธีลบ index.php ออกจาก URL ใน codeigniter

- ดาวน์โหลดไฟล์ .htaccess แล้ว Save ไว้ที่โฟลเดอร์ของ Codeigniter ที่เราติดตั้ง

- แก้ไขไฟล์ /system/application/config/config.php

จาก

`php
$config['index_page']="index.php";`

เป็น

`php
$config['index_page']="";`
