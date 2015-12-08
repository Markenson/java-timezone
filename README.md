java-timezone
===========

Simple java time zone checker

How build it?
=============

After clone it, install maven and type the following command:

```
mvn clean install
```

How use it?
===========

type:
```
java -jar target\java-time-1.0-SNAPSHOT.jar [timezone_id]

timezone_id - optional. Show selected time zone at top.

```
example 1 (JRE defined as America/Sao_Paulo, informing time zone) :
```
java -jar target\java-time-1.0-SNAPSHOT.jar America/Sao_Paulo
```

output 1:
```
Now (jre default): Tue Dec 08 19:07:41 BRST 2015

***Current time zone at selected time zone: America/Sao_Paulo    08/12/15 19:07

Default time zone: America/Sao_Paulo
Current time at America/Sao_Paulo       08/12/15 19:07

Current time at ...
ACT     09/12/15 06:37
AET     09/12/15 08:07
AGT     08/12/15 18:07
ART     08/12/15 23:07
AST     08/12/15 12:07
Africa/Abidjan  08/12/15 21:07
Africa/Accra    08/12/15 21:07
Africa/Addis_Ababa      09/12/15 00:07
Africa/Algiers  08/12/15 22:07
Africa/Asmara   09/12/15 00:07
Africa/Asmera   09/12/15 00:07
Africa/Bamako   08/12/15 21:07
```

example 2 (JRE defined as UTC, without time zone informed):
```
```

output 2:
```
Now (jre default): Tue Dec 08 20:54:48 UTC 2015

Default time zone: Etc/UTC
Current time at Etc/UTC 12/8/15 8:54 PM

Current time at ...
ACT     12/9/15 6:24 AM
AET     12/9/15 7:54 AM
AGT     12/8/15 5:54 PM
ART     12/8/15 10:54 PM
AST     12/8/15 11:54 AM
Africa/Abidjan  12/8/15 8:54 PM
Africa/Accra    12/8/15 8:54 PM
Africa/Addis_Ababa      12/8/15 11:54 PM
Africa/Algiers  12/8/15 9:54 PM
Africa/Asmara   12/8/15 11:54 PM
Africa/Asmera   12/8/15 11:54 PM
Africa/Bamako   12/8/15 8:54 PM
Africa/Bangui   12/8/15 9:54 PM
Africa/Banjul   12/8/15 8:54 PM
Africa/Bissau   12/8/15 8:54 PM
Africa/Blantyre 12/8/15 10:54 PM

```
