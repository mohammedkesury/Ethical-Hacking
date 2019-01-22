Use nmap scanner to perform port scanning of various form such as 
1. Conduct a SYN scan of the host scanme.nmap.org
2. Conduct FIN, Null and Xmas scan of the above host 
3. conduct ACK scan of the above host
 

1. 	nmap -sS scanme.nmap.org
2.i. 	nmap -sN scanme.nmap.org
2.ii. 	nmap -sF scanme.nmap.org
2.iii. 	nmap -sX scanme.nmap.org
3. 	nmap -sA scanme.nmap.org
