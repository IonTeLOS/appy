# appy

To get Appy Software Manager :

curl -s --compressed "https://iontelos.github.io/appy/KEY.gpg" | sudo apt-key add -

sudo curl -s --compressed -o /etc/apt/sources.list.d/telos.list "https://iontelos.github.io/appy/telos.list"

sudo apt update

sudo apt install appy

