#ptt_login
Script for logining ptt.cc with ssh

##Installation (On ubuntu)
$ apt-get install expect

##Configure
If you never used ssh to connect to bbsu@ptt.cc, you need to type "ssh bbsu@ptt.cc" on terminal and accept the fingerprint.

replace yourUserName and yourPassword with your username and password

bbsu@ptt.cc for UTF-8 (Default)

bbs@ptt.cc for BIG5

##Usage
choising ethier ptt.exp or ptt.sh.

use terminal

$ expect ptt.exp

or

$ . ptt.sh
