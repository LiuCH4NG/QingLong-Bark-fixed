# 修复推送内容过长导致Bark推送失败

* 将两js文件保存于青龙docker挂载路径中
* 订阅管理——>编辑订阅——>执行后加入
```shell
cp -f /ql/scripts/sendNotify_fun.js /ql/data/scripts/KingRan_KR/function/sendNotify.js
cp -f /ql/scripts/sendNotify.js /ql/data/scripts/KingRan_KR/sendNotify.js
cp -f /ql/scripts/sendNotify.js  /ql/data/deps/sendNotify.js
```