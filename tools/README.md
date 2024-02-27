This is a bc file content checker. For those who need to make there own bible content file. This tool is quite simple and straight forward.

Please download this file and unzip it. Put your bc-file in the same directory. And use this command:

bc-checker [your bc file]

And you'll see some outputs. If no outputs or simple tell you Total lines:xxxxx, this means your bc-file is OK. If you got some error messages like:

Error 1033:Verse count is not match [17!=18] @ REV:12 at line 35717.

You'd better to check file in which line message tell you.

bc-checker.0.1.zip is for Windows users.
bc-checker.0.1.tar.gz is for Linux users.

All Error/Warning messages are as following:

 

Error

1000 Bible Section data count error

1001 Missing Bible Version

1002 Missing Bible name

1003 Missing Bible language

1010 Chapter Section data count error

1011 Missing Book name

1012 Missing Book full name

1013 Book name is wrong or mis-ordered with %s and %s

1014 Book chapter count is not match. Input data:%s!=%d @ %s

1015 Missing Book short name

1030 Context Section data count error

1032 Verse mis-ordered %d @ %s:%d

1033 Verse count is not match [%d!=%d] @ %s:%d

1034 Line mark can only be '*' @ %s:%d:%s

 

Warning

7000 Bible Section misplace

7001 Chapter Section misplace

7002 Chapter Context misplace

7010 Book chapter File count is not match. Book:%s, Chap:%d, Count:%d

7011 Missing Book chapter count

7030 Vesrse Context is empty. @ %s:%d:%s
