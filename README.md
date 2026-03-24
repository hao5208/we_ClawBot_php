# we_ClawBot_php
微信ClawBot的php简易用法

本项目仅供参考，无法保证安全

宝塔建站php82，命令行php版本82

改poll.php和aa.php里的域名

终端执行，会给个链接，微信扫码登陆即可
php login.php

宝塔进程守护添加
php poll.php

先用自己微信给机器人发个消息让系统拿到context_token

发消息接口
http://bot.cn/send.php?msg=测试消息

图片接口(目前有问题用不了)
http://bot.cn/send.php?type=image&msg=图片url
