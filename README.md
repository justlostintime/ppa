# ppa
ppa install repository, Gambas Shell gsh, em6502

# Update for new Releases of DEBian/mint/ubuntu
```
sudo -i
curl -s --compressed "https://raw.githubusercontent.com/justlostintime/ppa/main/ubuntu/KEY.gpg" | gpg --dearmor > /etc/apt/trusted.gpg.d/westwood-archive-key.gpg
sudo curl -s --compressed -o /etc/apt/sources.list.d/gsh.list "https://raw.githubusercontent.com/justlostintime/ppa/main/ubuntu/gsh.list"
sudo apt update
```

# Add Additional application source
```
curl -s --compressed "https://raw.githubusercontent.com/justlostintime/ppa/main/ubuntu/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/gsh.list "https://raw.githubusercontent.com/justlostintime/ppa/main/ubuntu/gsh.list"
sudo apt update
```

# Install software
```
sudo apt install gsh
or
sudo apt install em6502
```
