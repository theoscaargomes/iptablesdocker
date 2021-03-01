# iptablesdocker

# Firewall forwarder port container with IPTABLES

##Buildar a imagem

docker build .  -t theoscaargomes/firewall:1.0

##Rodar container

sudo docker run --privileged --name firewall theoscaargomes/firewall:1.0
