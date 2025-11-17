## To install Snort on Kali
```
sudo apt-get install -y snort
```
## To ensure that it is installed 
```
snort --version
```
## Normally, Snort is saved in  /etc/snort, to show the file inside it 
```
ls  -all /etc/snort
```
![image alt](https://github.com/noor-nas24/IDS-IPS-Snort/blob/68a1c48f1ecf75661b20203aff59fb9a004f8ac8/snort%20file.png)

## **Note: in Snort 3, there isn't Snort.conf, instead of there is Snort.lua
-You can open it with this command 
```
sudo nano /etc/snort/snort.lua
```
![image alt](https://github.com/noor-nas24/IDS-IPS-Snort/blob/261e9c733f110bba71c64f05b4cac957fcd23a91/snort%20config.png)

## You should configure your network 
![image alt](https://github.com/noor-nas24/IDS-IPS-Snort/blob/2b28d873e7180260361ce1155524e67c3312ec5d/Set%20network.png)
