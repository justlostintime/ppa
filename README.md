# ppa
ppa install repository

# Add Additional application source
```
curl -s --compressed "https://raw.githubusercontent.com/justlostintime/ppa/main/ubuntu/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/ppa.list "https://raw.githubusercontent.com/justlostintime/ppa/main/ubuntu/ppa.list"
sudo apt update
```

# Install software
```
sudo apt install gsh
```
