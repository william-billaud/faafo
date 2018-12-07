faafo
adaptation of https://git.openstack.org/cgit/openstack/faafo/plain/contrib/install.sh  
https://developer.openstack.org/firstapp-shade/scaling_out.html
correction of some big under ubuntu 16.04 :
- not editing the proper mysql configuration file
- using guest/guest credential in rabbitmq for external access without proper settings (creation of a new user fractal/guest instead)
