# -TUT-Config-sendmail-linux
# -TUT-Config-sendmail-linux


1. install Centos Linux ( EX: Centos7 )
2. install epel-release => sudo yum install epel-release
3. install ssmtp => sudo yum install ssmtp
4. config ssmtp:
   File ssmtp.conf
      root=User Gmail
      mailhub=smtp.gmail.com:587
      hostname=CentosMonitor
      UseTLS=Yes
      UseSTARTTLS=Yes
      AuthUser=User gmail
      AuthPass=Pass Gmail
      FromLineOverride=Yes
      TLS_CA_File=/etc/pki/tls/certs/ca-bundle.crt
		File reva
			root:s2upinss@gmail.com:smtp.gmail.com:587
5. install mailx

DONE!


More information:
[+] https://www.server-world.info/en/note?os=CentOS_7&p=squid&f=2
[+] http://linuxpitstop.com/install-ssmtp-to-send-emails-to-gmail-and-office3655/
[+] https://www.cyberciti.biz/faq/installing-rhel-epel-repo-on-centos-redhat-7-x/
[+] https://www.cyberciti.biz/tips/linux-use-gmail-as-a-smarthost.html
