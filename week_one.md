- Configured three devices (Rasberry Pi 3 x 2, Nvidia jetson nano) installed the OS, connected 
to the network, assigned ip by dhcp.

- Installed Docker in Nvidia jetson nano for future use.

- made the secure ssh-key and sent to all three devices a public key, in order to have a secure
connection.
 
- Used main worksation to administrate the devices using Ansible. (It operates in RedHat OS) 

- Installed vim-nox and tmux on all three devices using Ansible. 

- Checked /var/log/apt from pure curiosity to check all installed apps by Ansible appear here.

- Enabled automatic updates on Pi 3 

- Lock down password logins on Pi 3 by configuring /etc/ssh/sshd_config

- Added Firewall UFW for Pi 3 in order to use it for future use 

