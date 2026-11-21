---
layout: page
title: 방송 소프트웨어
permalink: /software/
---

첫 방송까지 필요한 것을 여섯 단계로 정리했습니다. 각 단계에서 **꼭 필요한 것은 하나씩**이고, 나머지는 필요해지면 더하면 됩니다.

| 단계 | 꼭 필요 | 처음 추천 | debutkit이 돕는 일 |
|---|---|---|---|
| 1. 아바타 | 모델 1개 | VRoid Studio(3D, 무료) 또는 PNG 2장 | 모델 사용 조건 확인 |
| 2. 트래킹 | 프로그램 1개 + 웹캠 | Live2D는 VTube Studio, 3D는 VSeeFace | 설치 확인, OBS에 투명 배경으로 연결 |
| 3. 송출 | OBS Studio | OBS Studio(무료) | 장면 5종 자동 구성 |
| 4. 소리 | 마이크 + 잡음 제거 | OBS 내장 잡음 제거 | - |
| 5. 채팅·후원 | 채팅창 | 한 플랫폼이면 내장 위젯, 동시 송출이면 debutkit overlay | 통합 채팅창, 후원 알림 |
| 6. 방송 후 | - | stream2clip | 하이라이트 클립 |

## 꼭 확인할 것 하나

**아바타 모델의 사용 조건.** 판매 모델은 대부분 "개인 활동"만 허락합니다. 수익 활동이나 소속사 활동(법인 사용)을 하려면 제작자의 허락이 따로 필요한 경우가 많습니다. VRM 모델은 파일에 조건이 들어 있어서 `debutkit doctor --avatar 모델.vrm --agency` 로 바로 확인할 수 있습니다.

전체 목록, 라이선스, 플랫폼 API 정리: [SOFTWARE.md](https://github.com/BudongJW/debutkit/blob/main/docs/SOFTWARE.md)
