UMA RAPIDA POC DO ROTEADOR DOMÉSTICO ProLink PRS1841

Exploit Title: Router backdoor - ProLink PRS1841 PLDT Home fiber
# Exploit Author: Lawrence Amer @zux0x3a
# Vendor Homepage: https://prolink2u.com/product/prs1841/
# Firmware : PRS1841 U V2
# reference: https://0xsp.com/security%20research%20%20development%20srd/backdoor-discovered-in-pldt-home-fiber-routers/

Description
========================
A silent privileged backdoor account discovered on the Prolink PRS1841 
routers; allows attackers to gain command execution privileges to the 
router OS.

The vulnerable account issued by the vendor was identified as "adsl" and 
"realtek" as the default password; attackers could use this account to 
access the router remotely/internally using either Telnet or FTP 
protocol.

PoC
=============================
adsl:$1$$m9g7v7tSyWPyjvelclu6D1:0:0::/tmp:/bin/cli
