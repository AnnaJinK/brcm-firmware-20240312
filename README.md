## What is this?
```/lib/firmware/brcm/``` 경로에 포함된 펌웨어들은 Wi-Fi 모듈이 올바르게 작동하고 네트워크에 연결할 수 있도록 도와줍니다.  


## Introduction
2024-03-12 릴리즈에 포함된 브로드컴 펌웨어 입니다.  
Raspberry Pi Zero W/2W 에 RetroPie 설치시 Wi-Fi 스캔 및 연결 동작이 불가능한 경우 사용할 수 있습니다.

### Installation
```
cd ~
git clone https://github.com/AnnaJinK/firmware-brcm.git
sudo cp -r firmware-brcm/brcm/* /lib/firmware/brcm
```
