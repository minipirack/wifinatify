# wifinatify
Convert the MiniPiRack to use WiFi for WAN and a NAT internally

Credit to from https://hacks.mozilla.org/2018/02/headless-raspberry-pi-configuration-over-bluetooth/

ansible-playbook -i hosts site.yml

# To access a terminal via BlueTooth
ls -al /dev/cu*
screen /dev/cu.Boogers-SerialPort 115200


