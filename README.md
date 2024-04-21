## What is this?
```/lib/firmware/brcm/``` 에 포함된 펌웨어들은 Wi-Fi 모듈이 올바르게 작동하고 Wi-Fi 네트워크에 연결할 수 있도록 도와줍니다. Raspberry Pi Zero W와 Zero 2W 는 동일한 네트워크 칩셋을 기반으로 사용하기 때문에, 이론적으로는 같은 드라이버가 두 모델에서 모두 작동해야 하지만, Zero 2W 로 업그레이드 되면서 Bluetooth와 Wi-Fi 부분에 성능 향상과 개선점이 있기 때문에 호환성 문제가 발생할 수 있습니다.

## Introduction
2024-03-12 릴리즈에 포함된 브로드컴 펌웨어 입니다.  
Raspberry Pi Zero W/2W 에 RetroPie 설치시 Wi-Fi 스캔 및 연결 동작이 불가능한 경우 사용할 수 있습니다.

### Installation
```
cd ~
git clone https://github.com/AnnaJinK/firmware-brcm.git
sudo cp -r firmware-brcm/brcm/* /lib/firmware/brcm
```
