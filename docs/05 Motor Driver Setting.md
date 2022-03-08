# Motor Driver Setting
## 5.1 AC Servo Motor Driver Setting

PANATERM.exe (PC Program 사용)

- 준비물: Micro Mini 5pin 케이블 ##드라이버에 케이블 연결하는 위치 사진첨부
- 프로그램 설치([PANATERM 파나소닉 셋업 지원 소프트웨어 다운로드](https://www3.panasonic.biz/ac/kr/dl/software/index.jsp?series_cd=3514))


![PANATERM 다운로드](docs/05/5_1.png)

PC프로그램 실행
: Driver에 USB micro 케이블 연결→②Driver 전원 on후 PC프로그램 실행 


### 5.1.1 앱솔루트 설정

[매개변수]선택→[앰프에서 읽어 오기]선택→[015앱솔루트 인코더설정]에서 선택항목 변경
공장 초기 설정 [1: 인크리멘탈로 사용 설정]
→ USER 선택 설정 [0: 앱솔루트로 사용 설정]

![앱솔루트설정](05/5_1_1_1.png)

![앱솔루트설정](05/5_1_1_2.gif)

### 5.1.2 스무딩 설정
    모터 떨림 발생시 모터의 떨림을 잡기 위해 사용


![스무딩설정](05/5_1_2.gif)

### 5.1.3 오토튜닝 설정
    조건 : 0 무효(비활성화), 1 표준응답모드(활성화)

![오토튜닝설정1](05/5_1_3_1.gif)

![오토튜닝설정2](05/5_1_3_2.gif)


### 5.1.4 Gain 설정

① 강성

![강성](05/5_1_4_1.gif)

② 관성비

![관성비1](05/5_1_4_2.gif)

![관성비2](05/5_1_4_3.gif)

## 5.2 BLDC Motor Driver Setting

EPOS Studio.exe (PC Program 사용) // 준비물: Micro Mini 5pin 케이블

PC프로그램 실행
: Driver에 USB micro 케이블 연결→②Driver 전원 on후 PC프로그램 실행

참고 문서
-	[홈페이지](https://www.maxongroup.co.kr/maxon/view/content/index)
-	유튜브 maxon ESCON Tutorials

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
    <iframe src="https://www.youtube.com/embed/playlist?list=PLmklAQtFT_ZJzWOa9O6507qA0NiSU8hzN" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>






--------------------------------------------------------
## 1. Panasonic AC Servo
### 1.1 Absolute Encoder
PC화면 캡쳐  - 종성씨
### 1.2 Smoothing
### 1.3 Gain
sdfsdf  
## 2. Maxon BLDC
### 2.1 Hall Sensor
Maxon EPOS4 사용방법 작성 - 준호씨
### 2.2 Encoder


## 3. HITEC RC Servo
### 3.1 Range
종성씨

### 3.2 Center
### 3.3 Motor Direction
