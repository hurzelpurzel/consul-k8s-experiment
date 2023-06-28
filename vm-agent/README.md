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
wget -O- <https://apt.releases.hashicorp.com/gpg> | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] <https://apt.releases.hashicorp.com> $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install consul
