# HOW TO SETUP OPENSSH SERVER ON LINUX AND CONNECT TO IT

  - sudo apt-get install openssh-server
  - sudo systemctl enable ssh --now
  - sudo systemctl start ssh
  - sudo apt install ufw
  - sudo ufw allow ssh
  - sudo ufw enable
  - sudo ufw status
  - vim /etc/ssh/sshd_config
  - change -> PasswordAuthentication yes
  - change -> PermitRootLogin yes
  - sudo service ssh restart
  - client -> ssh username@ip
