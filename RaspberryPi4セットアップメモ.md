# Java11インストール手順

### OpenJDKをインストール
#### インストール
```shell
sudo apt install default-jdk-headless
```
#### 確認
```shell
java --version
```
---
### WiringPiインストール
#### インストール
```shell
wget https://project-downloads.drogon.net/wiringpi-latest.deb
dpkg -i wiringpi-latest.deb
```
#### 確認
```shell
gpio -v
```
---
### VIMをインストール
#### インストール
```shell
sudo apt-get --purge remove vim-common vim-tiny
sudo apt-get install vim
```
