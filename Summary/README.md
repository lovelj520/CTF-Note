# CTF总结

- Web : [Web总结](https://github.com/lovelj520/CTF-Note/tree/main/Summary/Web)
- Misc : [Misc总结](https://github.com/lovelj520/CTF-Note/tree/main/Summary/Misc)
- Crypto : [Crypto总结](https://github.com/lovelj520/CTF-Note/tree/main/Summary/Crypto)
- Real : [Real总结](https://github.com/lovelj520/CTF-Note/tree/main/Summary/Real)
- Pwn : [Pwn总结](https://github.com/lovelj520/CTF-Note/tree/main/Summary/Pwn)
- Reverse :[Reverse总结](https://github.com/lovelj520/CTF-Note/tree/main/Summary/Re)
---


- 常用找flag的命令
```bash
find / -name flag*
find / -name * | grep "flag{"
echo $PATH | grep "flag{"
env | grep "flag"
```

- 环境变量
```bash
env
cat /proc/1/environ
cat /proc/$PID/environ
```

- VPS
```
python -m SimpleHTTPServer 8080

```

- 图片马制作

```bash
copy 1.jpg/b+2.php 3.jpg
```