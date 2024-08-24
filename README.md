<p align="center">
  <img src="https://cdn.discordapp.com/attachments/1208011896322793494/1276851389976547464/ChessGo.png?ex=66cb0806&is=66c9b686&hm=e33340ce51233a928a6c5de26670de1ae2df75035fa6ed4f2fa9c8b7d8404745&">
</p>
 
# What is this

python으로 만든 stockfish 16.1 기반 체스봇입니다.
Pyqt5와 python-chess 라이브러리를 사용하였습니다.

# How is works

프로그램을 실행할시 ChesGo라는 인스턴스가 생성되어 윈도우가 띄워집니다.
사용자가 기물을 드래그 앤 드롭으로 이동시키면 chessbton 클래스가 이를 처리하고, ChessBoard의 hdmove() 함수가 호출해 stockfish 엔진에 사용자의 수를 반영합니다.
사용자 수가 반영된 후, make_ai_move()가 호출돼 엔진이 수를 둡니다.

# Usage

- 파이썬이 깔려 있어야합니다. (최선버전 권장)
1. [stockfish를 다운받습니다.](https://stockfishchess.org/)
2. stockfish 폴더를 src폴더 안에 넣습니다.
3. 엔진파일의 경로를 바꿉니다. (125줄)
4. 실행

아 라면먹고싶다
