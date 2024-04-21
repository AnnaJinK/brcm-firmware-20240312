## Raspberry Pi OS brcm
2024-03-12 릴리즈에 포함된 브로드컴 펌웨어 입니다.  
Raspberry Pi Zero W/2W 에 RetroPie 설치시 Wi-Fi 스캔 및 연결 동작이 불가능한 경우 사용할 수 있습니다.

```/lib/firmware/brcm/``` 경로에 포함된 펌웨어들은 Wi-Fi 모듈이 올바르게 작동하고 Wi-Fi 네트워크에 연결할 수 있도록 도와줍니다.  
라즈베리 파이 제로 W와 제로 2 W가 동일한 칩셋을 사용하기 때문에, 이론적으로는 같은 드라이버가 두 모델에서 모두 작동해야 합니다.  
그러나 때로는 특정 문제로 인해 호환성 문제가 발생할 수 있습니다.

```
cd ~
git clone https://github.com/AnnaJinK/firmware-brcm.git
sudo cp -r firmware-brcm/brcm/* /lib/firmware/brcm
```
