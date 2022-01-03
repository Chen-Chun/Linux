# Finally

## Centos installation
1. 改hostname  
`hostnamectl set-hostname test1`
2. 關閉 firewalld
3. secure linux 要是 disable 

        $su  
        # systemctl start sshd  
        # systemctl status sshd  
        # systemctl stop firewalld
        # systemctl status firewalld
        # getenforce

` # gedit /etc/selinux/config `  
修改裡面的 SELINUX = disabled  
並且關機重新開機 就可以了

4. ifconfig確定自己的ip位置


# 用到一台虛擬機
## 1. bind (in w16.md)
## 2. Apacha (in w8.md)
## 3. www mysql virtual host (in w8.md)
## 4. www php virtual host (in w8.md)
## 5. telnet(in w13.md)
關機後clone新創的vmware  
## ssh scp(in w4.md)
## ssh no password (in w4.md)
## nfs(in w10.md)


## vsftp
## haproxy

`yum install -y epel-release`  
`yum install haproxy -y`  
`cp /etc/haproxy/haproxy.cfg cp /etc/haproxy/haproxy.cfg.bak` 

## samba (in w11.md) 錯率太高 最後做

# 用到兩台虛擬機

## DHCP

## NAT

## From NetworkManager to network










