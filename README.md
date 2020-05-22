copy folder flutter_login to xampp/htdocs
open phpmyadmin in your browser and import database login_flutter.sql
Cek your IPADDRESS, open cmd write ipconfig and press enter
change code in file api.dart to
class Api { static String url = "http://IPADDRESS/flutter_login/check.php"; static String regis = "http://IPADDRESS/flutter_login/register.php"; }
