# Portfolio | LEE EUIJU
## :pushpin: Intro
안녕하세요! 꿈의 미래를 만들어가는 사람 **이의주**입니다!  
IoT, Embedded 분야에서 **Embedded Sofrware Engineer**로서 빛나기 위해 노력중입니다!

## :pushpin: Profile 
**이의주** <sub>LEE EUIJU / 2000.06.07  

> :mortar_board: 2019.03 ~ 2025.02 | **광운대학교 전기공학과 졸업**  
> :memo: Thesis | **Cost Benefit and Capacity Analysis in Long Term ESS Operation**  
>   
> Programming Languages: **C, C++, Python**  
> Hardware Platforms: **Raspberry Pi, Arduino**
  
## :pushpin: Projects
### :bar_chart: Project 1 | 주파수 대역별 Audio Level Meter
> * 입력 신호 **주파수 3개 대역(LPF, BPF, HPF)** 분리  
> * 입력 신호 **가변 증폭**  
> * 주파수 대역별 **입력 신호 크기 10단계 LED 표시**  
> * 주파수 대역별 **증폭 gain control**  
>> #### Trouble shooting
>> 스피커 출력 noise 발생  
>> PREAMP 가변증폭기능 확인불가  
>> 소자별 배터리 전원 연결 후 short 발생

### :wrench: Project 2 | 전자부하 (DC LOAD)
> * **전류 8 단계 가변(0~2A)**  
> * **전압, 전류, 전력** monitoring  
> * **배터리 내부저항** monitoring  
> * **SoC(State of Charge)** 구현 및 monitoring  
>> #### Trouble shooting
>> Arduino 연결 시 7T, 8T 전류가변 불가  
>> LCD 모니터, INA219 사용 시 Arduino SDA, SCL 연결 핀 부족  
>> Arduino 통해 전압 측정 시, 순시적 전압 상승  
>> 내부저항 측정 시 Voc, VL 측정 필요

### :loudspeaker: Project 3 | 폭염주의보/경보 알리미
> * 도시명 입력, **폭염 주의보/경보 발령 시 LED 점등**  
> * **실시간 날씨(기온) 정보 open api 통해 확인**  
>> #### Trouble shooting
>> 주의보/경보 간 LED 밝기 차이  
>> portable한 형태 제작 필요

### :battery: Project 4 | Battery Charger
> * **고속 충전**
> * **전압 전류 monitoring**  
>> #### Trouble shooting
>> 고효율 충전 불가  
>> 디지털화 필요  
>> 충전 시 발열 문제
