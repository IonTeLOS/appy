# appy

To get Appy Software Manager :

wget -qO - https://iontelos.github.io/appy/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/appy.gpg

sudo curl -s --compressed -o /etc/apt/sources.list.d/telos.list "https://iontelos.github.io/appy/telos.list"

sudo apt clean

sudo apt update

sudo apt install appy

