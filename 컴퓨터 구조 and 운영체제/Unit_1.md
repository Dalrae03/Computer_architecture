# 1단원 - 컴퓨터 구조 시작하기
<br>
- 컴퓨터 구조를 알아야 하는 이유 <br>
1. 컴퓨터 내부를 들여다봄으로써 문제 상황을 빠르게 진단하고, 문제의 원인을 다양하게 찾을 수 있다. ( 문제 해결 능력 향상 ) <br>
2. 자신이 개발한 프로그램이 어떤 환경에서 어떻게 작동하는지 이해하고 있어야 프로그램을 위한 최적의 컴퓨터 환경을 만들 수 있다. ( 프로그램이나 서버컴퓨터의 성능, 용량, 비용을 고려 할 수 있다. ) 

<br>
<br>

## 컴퓨터가 이해하는 정보

→ 0과 1로만 이루어진 정보 ⇒ 데이터, 명령어

( 데이터와 명령어는 0과 1로만 이루어져 있다. )

<br>

- **데이터** → 명령어를 위해 존재하는 일종의 내용물
    
    컴퓨터가 이해하는 숫자, 문자, 이미지, 동영상과 같은 정적인 정보
    
    컴퓨터와 주고받는 정보나 컴퓨터에 저장된 정보를 가리킬 때 편하게 통칭
    

- **명령어** → 컴퓨터를 작동시키는 정보
    
    데이터를 움직이고 컴퓨터를 실질적으로 동작시키는 정보
    
<br>
<br>
<br>

## 컴퓨터의 4가지 핵심부품

![1단원 - 컴퓨터 핵심부품](./1%EB%8B%A8%EC%9B%90%20-%20%EC%BB%B4%ED%93%A8%ED%84%B0%20%ED%95%B5%EC%8B%AC%EB%B6%80%ED%92%88.png)

- 중앙처리장치 ( CPU: Central Processing Unit )
- 주기억장치 ( 메모리 )
- 보조기억장치 ( Secondart storage )
- 입출력장치

⇒ 메인보드 ( or 마더 보드 )라는 판에 연결

메인보드 - 여러 컴퓨터 부품을 부착할 수 있는 슬롯과 연결단자가 있음

<br>
<br>

- **주기억장치 ( 메모리 )**

→ 실행되는 프로그램의 명령어와 데이터를 저장하는 부품 ⇒ 프로그램이 실행되려면 반드시 메모리에 저장이 되어있어야한다. 

크게 RAM( Random Access Memory ), ROM( Read Only Memory ) 2가지가 있음

( 보통 ‘메모리’ 라고하면  RAM지칭 )

<br>

주소 - 지정된 값의 위치

저장된 값에 빠르고 효율적으로 접근하기 위해, 메모리 내 원하는 위치 접근 가능

<br>
<br>

- **CPU ( 중앙처리 장치 )**

→ 메모리에 저장된 명령어를 읽어 들이고, 읽어 들인 명령어를 해석하고, 실행하는 부품

- CPU 내부 구성 요소
    - 산술논리연산장치 ( ALU )
    - 레지스터
    - 제어장치

<br>

<ins>ALU</ins> - 계산기. 컴퓨터 내부에서 수행되는 대부분의 계산을 수행.

<ins>레지스터</ins> - CPU내부의 작은 임시 저장 장치. 프로그램을 실행하는 데 필요한 값들을 임시로 저장. CPU에 다양한 이름, 역할을 가진 레지스터 존재.

<ins>제어장치</ins> - ‘제어 신호’ 를 내보내고 명령어를 해석하는 장치. 

( 제어 신호 - 컴퓨터 부품을 관리하고 작동시키기 위한 전기신호 )

<br>

-대충 흘러가는 과정-

CPU안의 제어 장치가 메모리에 ‘메모리 읽기’ 제어신호를 보냄 → 메모리가 CPU 내부의 레지스터에 명령어 전달 → 레지스터로 읽어들인 명령어를 제어장치가 해석 → 추가적인 메모리가 필요하면 한번 더 반복 → 계산이 필요하면 레지스터의 데이터를 ALU가 계산 수행 → 수행후 레지스터에 값 저장 → 제어장치가 다음 메모리를 읽기 → 메모리의 내용을 레지스터로 전달 → 제어장치 레지스터 해석 → 저장하라는 명령어였다면 레지스터 내부의 정해진 데이터를 제어장치의 ‘메모리 쓰기’ 제어 신호와 함께 메모리에 저장

<br>

- 단점
1. 가격이 비싸 저장 용량이 적다.
2. 전원이 꺼지면 저장된 내용을 잃는다.

<br>
<br>

- **보조기억장치**

→ 전원이 꺼져도 저장된 내용을 기억할 수 있는 장치. ( 메모리보다 크기가 크다 )

하드 디스크 드라이브, SSD, USB 메모리, DVD, CD-ROM 등

<br>

메모리 → 현재 ‘실행되는’ 프로그램 저장

보조기억장치 → ‘보관할’프로그램을 저장

<br>
<br>

- **입출력장치**

→ 컴퓨터 외부에 연결되어 컴퓨터 내부와 정보를 교환할 수 있는 장치

마이크, 스피커, 프린터, 마우스, 키보드 등

<br>

보조기억장치는 관점에 따라 입출력장치의 일종으로 볼 수 있다.

주변장치 ( 컴퓨터 주변에 붙어있는 장치 )= 입출력장치 + 보조기억장치 ( 메모리를 보조하는 특별기능수행 입출력장치 )

<br>
<br>

- **시스템 버스**

→ 컴퓨터 네 가지 핵심 부품 ( CPU, 메모리, 보조기억장치, 입출력장치 )을 연결하는 가장 주요한 버스 ( 통로 ).

- 시스템 버스 내부 구조
    - 주소 버스 - 주소를 주고 받는 통로
    - 데이터 버스 - 명령어와 데이터를 주고받는 통로
    - 제어 버스 - 제어 신호를 주고받는 통로

컴퓨터 내부에는 다양한 종류의 통로 ( 버스 )가 연결되어 서로 정보를 주고받는다