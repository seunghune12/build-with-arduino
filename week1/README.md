Week 1 - Arduino Starter Kit

Arduino Starter Kit를 이용해 Project 03 ~ Project 06을 실습했습니다.

진행한 프로젝트

Project 03 - Love-O-Meter

온도 센서를 이용해 주변 온도를 측정하고, 측정값에 따라 LED가 켜지도록 구현했습니다.

학습 내용

* 아날로그 입력
* 온도 센서 사용
* analogRead()
* 조건문을 이용한 LED 제어

⸻

Project 04 - Color Mixing Lamp

빛의 세기를 감지하고 RGB LED의 색상을 조절하는 회로를 구현했습니다.

학습 내용

* 포토트랜지스터
* RGB LED
* 아날로그 센서 입력
* PWM 출력

⸻

Project 05 - Mood Cue

가변저항을 이용해 서보모터의 위치를 제어했습니다.

학습 내용

* Potentiometer
* Servo Motor
* 센서값 변환
* map()
* Servo Library

⸻

Project 06 - Light Theremin

조도 센서의 입력값에 따라 부저의 음높이가 변하도록 구현했습니다.

학습 내용

* 조도 센서
* Piezo
* 센서값과 출력값 연결
* tone()
* 입력값 Mapping

⸻

Week 1 정리

이번 주에는 Arduino의 기본적인 입력 → 처리 → 출력 구조를 실습했습니다.

Sensor Input
     ↓
   Arduino
     ↓
Processing
     ↓
LED / Servo / Piezo

센서 데이터를 읽고, 해당 값을 조건문이나 map()을 이용해 변환하여 여러 출력장치를 제어하는 기본적인 Arduino 제어 방식을 학습했습니다.

사용 장비

* Arduino Uno
* Arduino Starter Kit
* Arduino IDE
