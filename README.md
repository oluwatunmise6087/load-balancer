# load-balancer 

## Prepare the Lab Direct
cd load_balancer_lab
![network1](network1.PNG)

 ## Set Up Vagrant Configuration
 ![networking](networking.PNG)
 ![provision-nginx](provision-nginx.PNG)

 ![provision-webserver](provision-webserver.PNG)

 ![networking2](networking2.PNG)

 ![networking3](networking3.PNG)

## Verify Load Balancing
 vagrant ssh web1
 ![web1](web1.PNG)
 ![web-server1](web-server1.PNG)

vagrant ssh web2
![web2](web2.PNG)
![web-server2](web-server2.PNG)
vagrant ssh web3
![web3](web3.PNG)
![web-server3](web-server3.PNG)