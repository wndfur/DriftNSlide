# DriftNSlide
It's racing game, It can contol with arduino!
<aside>
<img width="630" height="500" alt="image" src="https://github.com/user-attachments/assets/bbd20b27-59cf-45d7-8e81-b821d05dd856" />


# DriftNSlide

**개발기간: 2024.07 ~ 2024.11**

</aside>

> **“레이싱 게임과 아두이노 회로를 직접 연결하여, 마치 콘솔 게임처럼!”**
> 

**컨트롤러를 이용하여 콘솔 게임처럼 화면에 자동차를 움직이며 플레이할 수 있는 프로젝트**

| **사용 프로그램** | **Arduino IDE, GMS**  |
| --- | --- |
| **사용 기술 스택** | **C, GML** |

### 개발 배경

**레이싱 게임에 대한 관심과 아두이노 컨트롤러를 활용한 몰입감 있는 조작 방식에 
매력을 느껴 프로젝트를 시작했습니다.**

### 기능

- **아두이노 컨트롤러를 통한 게임 화면 속의 자동차 조종**
    - 외부 확장자에 포함된 데이터 라이브러리 사용
- **컨트롤러의 작동을 통해서 자동차에서 다른 자동차를 저지**
    - **instance_place(x, y, obj)** : 오브젝트 상호간의 접촉 이벤트 함수를 사용
- **다른 기본 OS(Win, Mac, etc…)에서도 구동**
    - GMS에서 상응하는 OS에 따라서 구동이 가능하게 설정

### 문제 상황

- **외부 확장자의 함수들이 엔진의 최신 버전과 호환되지 않는 문제**
- **함수에서 받는 데이터 값이 제대로 전달되지 않는 문제**

### 개선점

- **사용자의 개발 엔진 버전이 낮으면, 외부 확장자의 공식 문서를 통해 
새로운 버전의 함수 호환법을 찾음**
- **함수에 들어가는 인수값을 바꾸어 제대로 된 결과값을 출력**

### 회고

- **arduino.DLL을 활용해 아두이노의 센서 값을 게임에 전달하고, 게임의 데이터값을
다시 하드웨어로 보내는 양방향 시스템을 구축했습니다.**
- **이번 프로젝트를 통해 외부 라이브러리와 하드웨어 연동의 중요성을 느꼈고, 
단순 구현을 넘어 시스템 전체를 고려한 설계의 필요성을 체감할 수 있었습니다.**

### 자료
<img width="794" height="892" alt="image" src="https://github.com/user-attachments/assets/ce342e84-3481-4580-8cd9-a690d54478e6" /> 
<img width="795" height="894" alt="image" src="https://github.com/user-attachments/assets/31af85ab-23c7-4e65-817e-d4969ee6f79e" />
<img width="795" height="894" alt="image" src="https://github.com/user-attachments/assets/b700f843-31ea-4b7d-bf9c-c86c50777ec6" />
<img width="1050" height="1173" alt="image" src="https://github.com/user-attachments/assets/7a8d2f8f-21e5-4f23-9288-dab7b2c52c8f" />


