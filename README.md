1. copy folder flutter_login to xampp/htdocs

2. open phpmyadmin in your browser and import database login_flutter.sql

3. Cek your IPADDRESS, open cmd write ipconfig and press enter

4. change code in file api.dart to

5. class Api { static String url = "http://IPADDRESS/flutter_login/check.php"; static String regis =          "http://IPADDRESS/flutter_login/register.php"; }
