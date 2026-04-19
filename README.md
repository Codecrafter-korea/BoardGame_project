# 하이브리드 보드게임 (Hybrid Board Game)
한국어 | [English](#english-version)

아두이노(Arduino)와 웹 서버(Node.js)를 연동하여, 오프라인 보드게임의 아날로그적인 재미에 디지털 요소를 결합한 하이브리드 보드게임 프로젝트입니다.
하드웨어 장치와 웹 프론트엔드가 실시간으로 데이터를 주고받으며 게임이 진행됩니다.

### 🛠 Tech Stack
* **Backend:** Node.js, Express
* **Frontend:** HTML, CSS, Vanilla JavaScript
* **Hardware:** Arduino (SPI Communication)

### 🚀 실행 방법 (How to Run)
프로젝트를 실행하려면 다음 순서대로 진행해 주세요.

1. **백엔드 서버 실행**
   터미널을 열고 프로젝트 루트 경로에서 `server.js`를 실행합니다.
   ```bash
   node server.js

2. **웹 인터페이스 접속**
서버가 켜지면, public 폴더 안에 있는 website.html 파일을 웹 브라우저로 실행하여 게임 화면을 띄웁니다.

3. **하드웨어(아두이노) 연동**
아두이노 IDE를 열고 RealEthernet2.ino 코드를 아두이노 보드에 업로드하여 실행합니다. 통신이 연결되면 게임을 시작할 수 있습니다!







A hybrid board game project that combines the tactile fun of physical offline gameplay with digital elements by seamlessly connecting Arduino hardware with a web server (Node.js). Showcased at a university festival, the game operates through real-time data exchange between the physical devices and the web frontend interface.

🛠 Tech Stack
Backend: Node.js, Express

Frontend: HTML, CSS, Vanilla JavaScript

Hardware: Arduino (SPI Communication)

🚀 Getting Started
Follow these steps to run the project locally.

Run the Backend Server
Open your terminal, navigate to the project root, and execute server.js.

Bash

node server.js
Open the Web Interface
Once the server is running, open the website.html file located in the public directory using your web browser to display the game interface.

Connect the Hardware
Open the Arduino IDE, upload, and run the RealEthernet2.ino sketch on your Arduino board. Once connected, you are ready to play!
