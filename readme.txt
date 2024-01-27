#The following are settings for the ansible automation engine (control node)
apt-get update
apt-get install python -y
apt-get install build-essential libssl-dev libffi-dev -y
apt-get install python-pip -y
apt install libxml2-dev libxslt1-dev zlib1g-dev -y
pip install cryptography
pip install netmiko
pip install napalm
pip3 install --upgrade ncclient junos-eznc jinja2 netmiko napalm ansible
apt install nmap


ansible-galaxy collection install cisco.ios
ansible-galaxy collection install arista.eos
pip3 install ansible-pylibssh