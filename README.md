# ubuntu_init_script
Script for install packages in clear system
```bash
sudo apt-get update && apt-get install git && \
  git clone https://github.com/Azition/ubuntu_init_script.git && \
  ln -s $(pwd)/ubuntu_init_script/init_system.sh /usr/local/bin/init_system && \
  chmod +x /usr/local/bin/init_system
```
