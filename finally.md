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
        # getenfo

` # gedit /etc/selinux/config `  
修改裡面的 SELINUX = disabled  
並且關機重新開機 就可以了

4. ifconfig確定自己的ip位置


# 考試解題順序
## 1. bind (in w16.md)
## 2. Apacha (in w8.md)
## 3. www mysql virtual host (in w8.md)
## 4. www php virtual host (in w8.md)
## 5. telnet(in w13.md)
## 6. ssh scp(in w4.md) 用putty確認連線  
關機後clone新創的vmware  
`hostnamectl set-hostname test2`  
關機後再clone user2的vmware  
`hostnamectl set-hostname test3`  
## 7. ssh no password (in w4.md)
## 8. nfs (in w10.md)
## 9-0. vsftp (in w14.md)
## 9-1. vsftp download (in w14.md)
## 9-2. vsftp upload (in w14.md)
## 10. haproxy (in w12.md) 用到3台虛擬機

# 有時間選下面幾個做
## DHCP  (in w15.md 要改一下)
## samba (in w11.md) 出錯率太高 倒數第三個做 但是如果有時間先做這個  
## NAT 要重新設定 會出現連線問題 所以倒數第二個做  
## From NetworkManager to network (in w10.md 要改一下) 需要確定這台虛擬機不會再用到 再去做設定 所以最後做  













