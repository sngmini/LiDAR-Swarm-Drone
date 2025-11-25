# Summary

---

## Datasheet of RPLIDAR C1

---

1. Product Overview
   + The RPLIDAR C1 is a next-generation 360-dgree 2D laser scanner developed by SLAMTEC.

2. Measurement Performance

   |Item|Detail|
   |---|---|
   |Distance Range|0.05 meters up to 12 meters (for White object under 70% reflection)|
   |Sample Rate|5,000 samples per second (5 KHz)|
   |Scan Filed Flatness|0° ~ 1.5°(can be customized)|
   |Communication Inerface|TTL UART|
   |Communication Speed|460800|

4. External Interface Signal Definition
   
   |Color|Signal Name|Type|Description|Min|Max|
   |---|---|---|---|---|---|
   |Red|VCC|Power|Total Power|4.8V|5.2V|
   |Yellow|TX|Output|Serial port output|0V|3.5|
   |Green|RX|Input|Serial port input|0V|3.5V|
   |Black|GND|Power|GND|0V|0V|

## Usermanual of RPLIDER C1

---

1. Overview
   + After connection the RPLIDAR C1 with PC via USB adapter, users can observe the cloud map of the enviroment scanning point in Robostudio.
   + The drivable motor controller can be used to configure the scan frequency by tuning motor speed.
     
     
     Items in the Development Kit
     + RPLIDAR C1
     + USB adapter
     + USB Type-C cable

2. Connection
   1. Connect RPLIDAR C1 with USB adapter (CP2102 => UART => USB)
   2. Connet the USB adapter to PC via the USB Type-C cable. 
   3. If the PC is on, the indicator light of the USB adapter will light up.

3. Recommandation
   + Pre-Heating
     + The scan core will ve heating when start woking. For best measurement accuracy, we recommend pre-heating for more than 2 mintues.
   + Ambient Temperature
     + RPLIDAR's measurement resolution is sensitive to ambient temperature. Avoid using at extremely high(>40℃) or low(<-10℃) temperatures.


> Copyright (c) 2009-2013 RoboPeak Team

> Copyright (c) 2013-2023 Shanghai Slamtec Co., Ltd.

> Summarized by sngmini

# 요약
---
## RPLidar C1 데이터 시트
---
1. 제품 개요
   + RPLIDAR C1은 SLAMTEC이 개발한 차세대 360° 2D 레이저 스캐너입니다.
2. 주요 성능 사항

   |항목|상세|
   |---|---|
   |측정 거리|반경 0.5 m에서 최대 12 m (반사율 70% 백색 물체 기준)|
   |샘플링 속도|초당 최대 5,000번 (5 KHz)|
   |스캔 균일도|0° ~ 1.5° (사용자화 할 수 있음)|
   |통신 인터페이스|TTL UART|
   |통신 속도|460800|

3. 외부 인터페이스 신호 정의
   |색상|신호명|형식|상세|최소|최대|
   |---|---|---|---|---|---|
   |빨강색|VCC|전원|전력 공급|4.8 V|5.2 V|
   |노랑색|TX|출력|시리얼 포트 출력|0 V|3.5 V|
   |초록색|RX|입력|시리얼 포트 입력|0 V|3.5 V|
   |검정색|GND|전원|GND|0V|0V|

## RPLIDER C1 사용자 메뉴얼

---

1. 개요
   + USB 어댑터를 통해 RPLIDAR C1을 PC에 연결한 후, 사용자는 RoboStudio에서 환경 스캔 포인트의 클라우드 맵을 관찰할 수 있습니다.
   + 구동 가능한 모터 컨트롤러를 사용하여 모터 속도를 조절함으로써 스캔 주파수를 구성할 수 있습니다.
     
     
     개발 키트 구성품
     + RPLIDAR C1
     + USB 어댑터
     + USB Type-C 케이블

2. 연결
   1. RPLIDAR C1을 USB 어댑터와 연결합니다. (CP2102 => UART => USB)
   2. USB Type-C 케이블을 통해 USB 어댑터를 PC에 연결합니다.
   3. PC가 켜져 있으면 USB 어댑터의 표시등이 켜집니다.

3. 권장 사항
   + 예열
     + 작동을 시작하면 스캔 코어에서 열이 발생합니다. 최고의 측정 정확도를 위해 2분 이상 예열할 것을 권장합니다.
   + 주변 온도
     + RPLIDAR의 측정 해상도는 주변 온도에 민감합니다. 극도로 높은 온도(>40℃)나 낮은 온도(<-10℃)에서의 사용을 피하십시오.
    

> Copyright (c) 2009-2013 RoboPeak Team

> Copyright (c) 2013-2023 Shanghai Slamtec Co., Ltd.

> Summarized by sngmini
