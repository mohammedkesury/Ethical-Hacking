                                                          Pract 2
Use nmap scanner to perform port scanning of various form such as 
1. Conduct a SYN scan of the host scanme.nmap.org
2. Conduct FIN, Null and Xmas scan of the above host 
3. conduct ACK scan of the above host
 

1. 	nmap -sS scanme.nmap.org
2.i. 	nmap -sN scanme.nmap.org
2.ii. 	nmap -sF scanme.nmap.org
2.iii. 	nmap -sX scanme.nmap.org
3. 	nmap -sA scanme.nmap.org

					                                                      
                                                           
                                                           Pract 3
Run the following commands on linux

Netstat :- This command displays various network related info such as network info, routing tables, interface statics, connections and multitask membership.

1. list all ports
2. list all TCP ports
3. list all UDP ports
4. list all sockets which are in listening state

1. netstat -a|more OR netstat -a|less
2. netstat -at|more OR netstat -at|less
3. netstat -au
4. netstat -l and netstat -lt and netstat -lu
