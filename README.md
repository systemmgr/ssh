## OpenSSH  
  
Secure SHell is a program for logging into and executing commands on a remote machine  
  
requires:    
```
apt install openssh openssh-server
```  
```
yum install openssh openssh-server
```  
```
pacman -S openssh
```  
  
Automatic install/update:
```
sudo bash -c "$(curl -LSs https://github.com/casjay-dotfiles/ssh/raw/master/install.sh)"
```
Manual install:
```
sudo git clone https://github.com/casjay-dotfiles/ssh "/usr/local/etc/ssh"
sudo ln -sf /usr/local/etc/ssh/sshd_config /etc/ssh/sshd_config
sudo systemctl enable --now sshd
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/OpenSSH" target="_blank">OpenSSH wiki</a>  |  
  <a href="https://www.openssh.com/" target="_blank">OpenSSH site</a>
</p>  
    
