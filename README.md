# Network-Programming-Project

#### Cisco Virtual Internet Routing Lab Personal Edition VIRL PE 20 nodes 
- Cisco network device interaction examples


### Network device 
- NX-OS, IOS-XR, Jupiper 


### Security 
- ansible-vault encrypt ...


### Routing protocol 
- Interior gateway protocol : OSPF, IS-IS, RIPv2
- Exterior gateway protocol : BGPv4

### OSI model 
- IPv4 Header 
- TCP, UDP header


#### Intent driven networking 


#### Teck stack 
- Python 
    - netmiko 
    - integrate Netmiko into router object 
- C/C++ 
- Java 
- Network libs 

- Hardware(Intel NUC)
- Cisco VIRL 
    - 
- IOS-XR, Juniper, Culumus, Arista, 
- Routing object 
- VMWare 
- Ansible 
- Vault for encrypt Ansible playbook and variables 

- Other virtualized software 

- Netmiko documenation:
http://netmiko.readthedocs.io/en/stable/index.html

- Netmiko GitHub repository:
https://github.com/ktbyers/netmiko

- Netmiko Blog Post:
https://pynet.twb-tech.com/blog/automation/netmiko.html

- Netmiko Installation
sudo apt-get install -y git python-pip
git clone https://github.com/ktbyers/netmiko.git
cd netmiko/
pip install -r requirements.txt
python setup.py install

- Pexpect and Parmiko Examples
https://github.com/PacktPublishing/Mastering-Python-Networking/tree/master/Chapter02

- Python **kwargs
https://www.digitalocean.com/community/tutorials/how-to-use-args-and-kwargs-in-python-3

- https://learningnetworkstore.cisco.com/

- Ansible Vault
https://docs.ansible.com/ansible/2.5/user_guide/vault.html

- Ansible Template
https://docs.ansible.com/ansible/latest/modules/template_module.html

- Ansible Developing Modules
https://docs.ansible.com/ansible/latest/dev_guide/developing_modules.html

- Custom Module Example (From Mastering Python Networking)
https://github.com/PacktPublishing/Mastering-Python-Networking/tree/master/Chapter05/Custom_Modules

- NX-API
https://www.cisco.com/c/en/us/td/docs/switches/datacenter/nexus7000/sw/programmability/guide/b_Cisco_Nexus_7000_Series_NX-OS_Programmability_Guide/b_Cisco_Nexus_7000_Series_NX-OS_Programmability_Guide_chapter_0101.html
https://github.com/datacenter/nxos/tree/master/nxapi/samples
lax-agg-r1# confi t
Enter configuration commands, one per line.  End with CNTL/Z.
lax-agg-r1(config)# feature nxapi
lax-agg-r1(config)# nxapi sandbox
lax-agg-r1# show nxapi

- IOS-XR
https://xrdocs.io/application-hosting/tutorials/2016-08-15-netmiko-and-napalm-with-ios-xr-quick-look/

RP/0/0/CPU0:lax-cor-r1(config)#xml agent tty iteration off

- Juniper PyEZ
https://www.juniper.net/documentation/en_US/junos-pyez/topics/task/installation/junos-pyez-server-installing.html#task-junos-pyez-install-dependencies

- Arista eAPI
https://eos.arista.com/introducing-the-python-client-for-eapi-pyeapi/

vEOS#confi t
vEOS(config)#management api http-commands
vEOS(config-mgmt-api-http-cmds)#no shutdown
vEOS(config-mgmt-api-http-cmds)#protocol https
vEOS(config-mgmt-api-http-cmds)#end
vEOS#show management api http-commands

- VyOS Links
https://wiki.vyos.net/wiki/Basic_setup
https://github.com/vyos/python-vyos-mgmt
http://vymgmt.readthedocs.io/en/latest/


#### How to run 
- `ip int br`
- `ip int brief`





#### Resource 
- https://learningnetworkstore.cisco.com/





#### TODO 
- Buy & install , set up Cisco Virtual Internet Routing Lab Personal Edition VIRL PE 20 nodes  (200 $)


