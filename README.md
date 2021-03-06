# JellibiAGV_BlockCoding 
**Jellibi** **A**utomated **G**uided **V**ehicle

## 개요

이 저장소의 코드들은 격자형 맵위에서 빠레뜨를 원하는 위치로 옮기는 물류이송로봇의 기능들이 구현되어 있습니다.

JellibiAGV 는 아두이노 나노 호환보드를 중심으로 RFID TAG 를 인식하기 위하여 연결된 RFID 리더, 빠레뜨를 들어올리는 네개의 서보모터와 라인트레이서 구현에 필요한 두개의 IR 센서, 바퀴를 굴리기 위한 두개의 DC 모터로 구성됩니다. 

이 코드는 mBlock5 프로그램을 사용하는 JellibiAGV의 Block Coding 버전 입니다.

### 다운로드


- [[젤리비 마카롱을 위한 mBlock 5 확장 사용법 다운로드]](http://www.robotnmore.com/download/codecrunch/robotjellibi_mBlock5_manual_v01.pdf)  
- [[미션 Map 다운로드]](http://www.robotnmore.com/download/codecrunch/robotjellibi_mission_map_v01.pdf) 



## mBlock 실행 및 초기 설정

### mBlock5 설치

https://www.mblock.cc/en-us/download/
위 링크에서 mBlock5 프로그램을 다운로드하고, 설치 합니다.  

### mBlock 실행 및 초기 설정
프로그램을 처음으로 실행했을 때 기본으로 설정되어 있는 'Codey'장치를 먼저 삭제해야 합니다.  
1) mBlock을 실행하고, 장치 탭의 Codey 위의 X버튼을 클릭하여 스프라이트를 삭제합니다.
2) '+' 추가 버튼을 클릭하여 장치 라이브러리를 띄웁니다.
3) 'Arduino Nano'를 찾아 별을 눌러 장치를 추가합니다.  

### 젤리비 AGV 확장 추가
mBlock에서 젤리비 AGV를 블럭을 사용하기 위해서는 Jellibi-AGV Extension을 다운로드 받아야 합니다.  
1) 검색을 통해 Jellibi-AGV Extension을 찾은 후 '+' 버튼을 클릭하여 다운로드 받아 추가합니다.
2) 확장 버전이 업데이트 된 경우 초록색 버튼을 클릭하여 업데이트 한 후에 프로그램을 다시 실행합니다.
3) Jellibi-AGV-Extension이 추가된 경우 제어 블록들을 확인할 수 있습니다.  

### PC와 젤리비 연결후 코드 업로드 하기
1) JellibiAGV를 USB 케이블로 연결 후 하단의 연결 버튼을 눌러 시리얼(COM) 포트 선택후 연결합니다.
2) 연결이 성공하면 업로드 버튼이 나타납니다.
3) 업로드 버튼을 누르면 컴파일 창이 나타나서 업로드 진행 상태를 보여줍니다.
4) 업로드가 완료되면 블록이 자동 실행 됩니다.  

### 코드 다운로드 

모든 코드는 Git 툴을 이용하거나 이 페이지에서 Zip 파일로 다운로드 할수 있습니다.    
파일목록 바로 위의 버튼들 중 "Clone or download" 을 선택하여 "Download ZIP" 메뉴를 선택하면 이 코드저장소의 모든 파일을 다운로드 받을 수 있습니다.   
받은 ZIP 파일을 압축을 풀어 mBlock프로그램에서 열수 있습니다.  



## *참고*
- 반드시 처음에 **'젤리비 AGV 사용 준비'** 블록을 사용하여야 합니다.
이 블록을 빠뜨린 경우에 업로드하면 컴파일 오류가 발생 됩니다.
- ***만약 2020년 7월 이후 생산된 JellibiAGV를 가지고 있다면, 젤리비 부트로더 펌웨어를 ATmega328P 최신 버전으로 업데이트해야 합니다.***    

> 문의하기 - sein@robotnmore.com



## 젤리비 AGV 제어용 핀 번호


- JellibiAGV 핀번호


![JellibiAGV_Pin](./jellibiAGV_pin.PNG)





