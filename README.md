# zero
###
```
sudo raspi-config
```

### 최상위 디렉토리
---
```
cd / 
```
```
cd /home/pi/
cd-
cd~
```
### 파일복사
---
```
cp test.c Downloads/test.c  <cp 복사할파일 
cp test.c /home/pt/Downloads/test.c
```
### 블루투스끄기
---
```
dtoverlay=pi3-disable/at
sudo systemctl disable hciuart
```
### 종료
---
```
sudo reboot
```
