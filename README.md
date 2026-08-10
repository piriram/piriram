# 김소람 | Embedded Software Engineer

센서 데이터 수집부터 자세 추정까지 구현하고, 문제를 재현 가능한 근거로 좁혀가는 소프트웨어 개발자입니다.

STM32 펌웨어 구현과 iOS 제품 출시 경험을 바탕으로 동작 원리를 이해하고 검증 가능한 결과를 만드는 데 집중합니다.

## Featured Project

### [STM32 IMU Attitude Estimation](https://github.com/piriram/stm32-imu-telemetry)

STM32F103C8T6에서 MPU6050의 6축 IMU 데이터를 수집하고 Roll/Pitch 자세각을 계산하는 펌웨어입니다.

- MPU6050 I2C Driver와 14-byte Burst Read 구현
- Accelerometer와 Gyroscope 데이터 기반 Roll/Pitch 계산
- Complementary Filter로 Noise와 Drift 보정
- UART Log와 SWD Live Expressions를 활용한 데이터 검증
- CMake 기반 ARM Cross Compile 및 GitHub Actions 자동 빌드

`C` `STM32F103` `MPU6050` `I2C` `UART` `CMake` `GitHub Actions`

## Experience

- **Apple Developer Academy @ POSTECH:** iOS 앱 4건을 App Store에 출시하며 기획부터 배포까지 제품 개발 전 과정을 경험했습니다.

## Software Projects

<details>
<summary>대표 iOS 프로젝트 보기</summary>

| 프로젝트 | 링크 | 설명 |
|---|---|---|
| DoSurf | [GitHub](https://github.com/piriram/DoSurf-iOS) / [App Store](https://apps.apple.com/kr/app/id6753593506) | 서핑 포인트 정보 및 기록 앱 |
| Pilling | [GitHub](https://github.com/piriram/Pilling-UIKit) / [App Store](https://apps.apple.com/kr/app/pilling/id6753967952) | 복약 알림 및 기록 앱 |
| MacC 2024 | [GitHub](https://github.com/piriram/2024-MacC-M4-6princess) / [App Store](https://apps.apple.com/kr/app/id6737822930) | 아카데미 MacC 팀프로젝트 |
| Bangdari | [GitHub](https://github.com/piriram/Bangdari-SwiftUI) | SwiftUI 기반 전통시장 정보 앱 |

</details>

## Tech Stack

```text
Embedded  : C, STM32F103, STM32 HAL, I2C, UART
Tooling   : STM32CubeIDE, STM32CubeMX, ARM GNU Toolchain, CMake, GitHub Actions, ST-Link
Quality   : Software Testing, Regression Testing, Defect Reproduction
Software  : Swift, UIKit, SwiftUI, RxSwift, Git, Linux
```

## Contact

- **Email:** piriram22@gmail.com
- **Velog:** [velog.io/@piriram22](https://velog.io/@piriram22)
