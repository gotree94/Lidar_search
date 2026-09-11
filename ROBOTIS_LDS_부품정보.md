# ROBOTIS LDS 센서 파트명 및 호환 부품

## 정확한 파트명

| 모델 | 공식 명칭 | 주요 특징 |
|------|-----------|-----------|
| **LDS-02** | 360 Laser Distance Sensor LDS-02 | 2022년 이후 사용, 160~8000mm 감지 |
| **LDS-03** | 360 Laser Distance Sensor LDS-03 | 2025년 이후 LDS-02 대체, 0.05~12m 감지 |

## 호환 가능한 부품

1. **USB2LDS 어댑터**
   - LDS-02와 LDS-03 모두 UART 인터페이스를 USB로 변환하는 어댑터 필요
   - **주의**: 2022년 2월 이후 변경된 USB2LDS 모델은 이전 모델과 호환되지 않음

2. **호환 가능 모델**
   - LDS-03은 LDS-02의 완전한 대체품으로 동일한 UART 인터페이스 사용
   - TurtleBot3 Burger 및 Waffle Pi 모델 모두 호환

## 주요 차이점

| 항목 | LDS-02 | LDS-03 |
|------|--------|--------|
| 크기 | 70×90×42mm | 54.7×39.7×34mm |
| 무게 | 131g | 42g |
| 감지 거리 | 160~8000mm | 0.05~12m |
| 샘플링 레이트 | 2.3kHz | 4kHz |
| 수명 | 1,000시간 | 10,000시간 |

LDS-03이 LDS-02보다 성능이 우수하며, 현재 주력 제품입니다.

---

## 참고 자료

- [ROBOTIS 공식 문서 - LDS-02](https://docs.robotis.com/docs/systems/turtlebot3/more_info/lds_02)
- [ROBOTIS 공식 문서 - LDS-03](https://docs.robotis.com/docs/systems/turtlebot3/more_info/lds_03)