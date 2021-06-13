2021-1-OSSPC-MUYAHO-3
---

[![License](https://img.shields.io/badge/license-GPLv3-green.svg)](http://www.gnu.org/licenses/gpl-3.0.html)
![badges](https://img.shields.io/badge/OS-ubuntu-red)
![Laguage](https://img.shields.io/badge/python-3.6.1-blue.svg)
![Laguage](https://img.shields.io/badge/pygame-2.0.1-lightgreen.svg)
![badges](https://img.shields.io/badge/pygame_menu-3.3.0-black)    


>Pygame을 이용한 Tetris 게임 "MUYAHOTRIS"   

**3조 무야호**  

- Team Leader: 산업시스템공학과 [김성균](https://github.com/ggyull/2021-1-OSSPC-MUYAHO-3)

- Team Member: 산업시스템공학과 [황동진](https://github.com/Fluffy-Star/2021-1-OSSPC-MUYAHO-3)

- Team Member: 식품산업관리학과 [이유림](https://github.com/RimuZZ/2021-1-OSSPC-MUYAHO-3)

>실행 방법   
***1. Python 3.6.1 설치***

```
$ sudo apt get update
$ sudo apt install python3.6.1
```

***2. Pygame 2.0.1 설치***

```
$ pip3 install pygame==2.0.1
```

***3. Pygame_menu 3.3.0 설치***

```
$ pip3 install pygame_menu==2.0.1
```

***4. Pymysql 1.0.2 설치***
```
$ pip3 install pymysql==1.0.2
```

***5. 프로젝트 폴더 접속***
```
$ cd 2021-1-OSSPC-MUYAHO-3
```

***6. 코드 실행***
```
$ cd MUYAHOTRIS
$ python3 Run.py
```

## MUYAHOTRIS 게임 소개

### 1. 메뉴 선택
게임 시작 메뉴 선택 페이지
<img src="MUYAHOTRIS/assets/images/main_widget.png" width ="500" height"250"">

### 2. 게임 플레이
인게임 플레이 화면
<img src="MUYAHOTRIS/assets/images/playgame_image.png" width ="500" height"250"">

##게임모드
- 이지 모드
  - 블록 하강 속도 느린 모드   
- 하드 모드
  - 블록 하강 속도 빠른 모드   
- 레벨 모드
  - 레벨 별 랜덤 블록 생성   


### 3. 랭킹 확인
레벨 모드 랭킹 확인 화면
<img src="MUYAHOTRIS/assets/images/levelranking_image.png" width ="500" height"250"">

Origin Base Source  
- https://github.com/hbseo/OSD_game
