# l2tp
A script to establish l2tp
run as follow


chmod +x l2tp.sh  
./l2tp.sh  
service ipsec restart  
service xl2tpd restart  
ipsec verify  

edit /etc/ppp/chap-secrets to change  username   l2tpd   passwd 


From https://blog.csdn.net/bbwangj/article/details/78593281
