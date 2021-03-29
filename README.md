# TryHackme - Rootme

[RootMe Room](https://tryhackme.com/room/rrootme)

### hangzou

1. **Reconhecimento**

   1. **Nmap Scan**
      - Portas
      - Serviços/Protocolos

   2. **Gobuster**
      1. Diretórios Ocultos
         - /panel/
         - /uploads/

2. **Shell Reverso**

   1. **PHP**
      - /usr/share/laudanum/php/php-reverse-shell.php
      - [Pentest Monkey PHP Reverse Shell](http://pentestmonkey.net/tools/web-shells/php-reverse-shell)

   2. **Blacklist Bypass**
      - .php3
      - .php4
      - .php5
      - .phtml

   3. **Netcat**
      - Endereço IP da Rede THM
      - nc -lvnp 4444
 
      > Solucionado com ajuda de Writeup

3. **Escalação de Privilégio**

   1. **Exploração de Permissão SUID**
      - /usr/bin/python 

      > Solucionado com ajuda de Writeup 

   2. **Python**
      - `python -c 'import os; os.execl("/bin/sh", "sh", "-p")'`
 
   3. **Root**
      - `cd /root/`
      - `ls`
      - root.txt
      - `cat root.txt`

## Concluido!

Writeup Consultado:
 
[title](https://infosecwriteups.com/tryhackme-rootme-ctf-walkthrough-detailed-a7c521df7339)

Observação:

Essa anotação é apenas um teste, que visa descrever meu passo a passo da resolução dos desafios do TryHackMe.
