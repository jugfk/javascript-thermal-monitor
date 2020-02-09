# 자바스크립트 젯슨나노 온도 모니터

젯슨나노의 모듈타입 온도센서 출력하기

<img src="./javascript_temp_monitor.png" alt="Screenshot" title="Screenshot">

# 설치하기
```
sudo apt update
sudo apt install nodejs
sudo apt install npm
sudo npm install -g --unsafe-perm node-red
node -v
npm -v

cd .node-red
npm install node-red-node-serialport
npm install node-red-contrib-moment
npm install node-red-dashboard

```

# 다운로드하기
```
wget https://raw.githubusercontent.com/jetsonworld/javascript-thermal-monitor/master/flows.json
```
위 주소를 복사해서 터미널에 입력한 후 엔터를 칩니다. flow.json 파일이 다운로드가 됩니다.


# 업로드하기

방금 다운로드한 flow.json 파일을 업로드하기 위해서 터미널에서 node-red를 입력한후 엔터를 칩니다.

# 구동하기
```
node-red
```

<img src="./01_node-red_log.png" alt="Screenshot" title="Screenshot">


# 노트
- 이 매뉴얼은 젯슨나노에서만 테스트했습니다.
