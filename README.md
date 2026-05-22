# Raspberry Pi Flask GPIO Web Server

## 패키지 업데이트

```bash
sudo apt-get update
sudo apt-get upgrade
```
## flask
```bash
sudo apt-get install python-pip python-flask
sudo pip install flask
```
## app.py 생성
```bash
mkdir web-server
cd web-server
nano app.py
```
## template 폴더 생성
```bash
mkdir templates
cd templates
```
## HTML 파일 생성
```bash
nano main.html
```
## 서버 실행
```bash
cd ..
sudo python app.py
```
라즈베리 파이 ip를 확인하여 접속
```bash
hostname -I
```
ex: http://192.168.0.15
