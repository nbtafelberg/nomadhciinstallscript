Nomad Install Script
- install Nomad, Nginx, Docker, Consul on a 3 node cluster (just add more if you want more nodes)
- set up DNS entries to your public ip's of the nodes
- change the file before running it on each node

** WARNING - this will clean up any existing configs on the server **

Edit the file and deploy it to all 3 servers, you will need a public network and private network, make sure your ports are all open as well on the local network.

I set this up on 3 servers on hetzner in Germany with one of their vswitches.


It's designed for debian Trixie (13)

 

Good luck - warning don't use it on an existing installation it will destroy it before it starts - obvs, you could modify it just to update the current configs if required rather than destroying.

*** YOU MUST PUT YOUR SERVERS DETAILS IN THE SCRIPT ***

I nano'd up the install script then
chmod +x install
then ./install



Enjoy

Wolf Software Systems Ltd
https://wolf.uk.com
