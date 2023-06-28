# vm-agent

After installing consul on kubernetes, we would like to let an external agent let join the cluster

see:

https://developer.hashicorp.com/consul/tutorials/get-started-vms/virtual-machine-gs-service-discovery



## install vm
e.g. debian 12

copy ssh key e.g.
<pre>
ssh-copy-id ludger@192.168.122.94
</pre>


## ansible

<pre>
ansible-playbook -i inventory.ini playbook.yaml  
</pre>

https://github.com/ansible-community/ansible-consul


## consul

https://medium.com/@wenhuanglin/tutorial-on-running-nomad-and-consul-as-a-systemd-daemon-service-part-2-d1b999c73bdd
<https://github.com/hashicorp-education/learn-consul-get-started-vms/tree/main/self-managed/infrastructure/local/scripts>
