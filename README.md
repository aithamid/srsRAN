# srsRAN
Config files for deploying a 5G platform with srsRAN


# Trouble CORE

Try 

sudo ip ro add 10.45.0.0/16 via 10.53.1.2  
sudo iptables -t nat -A POSTROUTING -o br-d84890a36697 -j MASQUERADE 
sudo ip addr add 127.0.10.1/8 dev  br-d84890a36697   
sudo ip addr add 127.0.10.2/8 dev  br-d84890a36697 
sudo ip addr add 127.0.10.3/8 dev  br-d84890a36697 