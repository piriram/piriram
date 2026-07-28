# 안녕하세요, 저는 임베디드 SW를 공부하고 있는 김소람입니다.

> "소프트웨어의 신뢰성은 결국 하드웨어를 얼마나 이해하느냐에 달려 있다"

iOS 앱 4건을 직접 출시하고, TTA에서 소프트웨어 품질 검증 인턴으로 근무하며 결함 재현과 엣지 케이스 분석을 체득했습니다.  
검증 업무 중 "소프트웨어의 안정성은 결국 하위 계층의 동작 원리에서 비롯된다"는 것을 절감하고, 임베디드 SW 개발로 전향했습니다.

---

## 🔧 Embedded SW

현재 STM32 Bare-metal 기반으로 드라이버를 직접 구현하며 실력을 쌓는 중입니다.

| 저장소 | 내용 | 기술 |
|--------|------|------|
| 🚧 **stm32-imu-can-node** (준비 중) | MPU6050 IMU → CAN 전송 시스템. I2C 드라이버, 상보필터, CAN 송수신 | `C` `STM32F103` `I2C` `CAN` |
| 🚧 **stm32-bare-metal-drivers** (준비 중) | GPIO / UART / I2C / CAN 드라이버 레지스터 직접 구현 | `C` `Bare-metal` `STM32` |

**진행 상황 (2026.07 기준):**
- ✅ STM32F103 개발환경 셋업 (ST-Link, CubeIDE)
- ✅ GPIO / UART 레지스터 직접 제어
- ✅ I2C HAL — MPU6050 데이터 수신, 상보필터로 Roll/Pitch 안정화
- ✅ I2C Bit-banging 챌린지 (SCL/SDA 레지스터 직접 토글)
- 🔄 CAN 루프백 (TJA1050, bxCAN 레지스터) — 진행 중

---

## 🍎 iOS (이전 경력)

<details>
<summary>Swift / UIKit 기반 iOS 앱 4건 출시 (클릭해서 보기)</summary>

| 프로젝트 | 링크 | 설명 |
|----------|------|------|
| DoSurf | [GitHub](https://github.com/piriram/DoSurf-iOS) · [App Store](https://apps.apple.com/kr/app/id6753593506) | 서핑 포인트 정보 앱 |
| Pilling | [GitHub](https://github.com/piriram/Pilling-UIKit) · [App Store](https://apps.apple.com/kr/app/pilling/id6753967952) | 복약 관리 앱 |
| MacC 2024 | [GitHub](https://github.com/piriram/2024-MacC-M4-6princess) · [App Store](https://apps.apple.com/kr/app/id6737822930) | Apple MacC 프로젝트 |
| Bangdari | [GitHub](https://github.com/piriram/Bangdari-SwiftUI) | SwiftUI 전통시장 정보 앱 |

**주요 기술:** Swift · UIKit · RxSwift · MVVM · SwiftUI

</details>

---

## 🛠 Tech Stack

```
Embedded : C · STM32F103 · STM32CubeIDE · ARM GCC · ST-Link
Protocol : I2C · UART · CAN (학습 중)
iOS      : Swift · UIKit · RxSwift · MVVM · SwiftUI
기타      : Linux (SSH, 프로세스 관리) · Git
```

---

## 📬 Contact

- **Email:** piriram22@naver.com
- **Velog (TIL):** [velog.io/@piriram22](https://velog.io/@piriram22)
