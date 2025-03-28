⭐️ 전북대학교 게임및혼합현실 팀 프로젝트에서 기여했던 것을 구분하기 쉽게 분리한 레포 입니다.

<br>

![올디너리데이 메인화면](https://github.com/user-attachments/assets/c0da74ee-8cca-4f9e-8bcd-c8aadca5b96d)

<br>

# 프로젝트 개요
| 개발 환경 | Unity |
|:------:|:------:|
| 개발 기간 | 2024/03/07 ~ 2024/05/07 |
| 게임 설명 | 주인공이 일상인 직장 야간 근무를 하며 겪는 알 수 없는 공포 상황 |
| 담당 역할 | 플레이어 상호작용에 대한 전반적인 개발 |
| 팀 레포지토리 | [GitHub](https://github.com/gdevhun/OrdinaryDay) |
| 스케줄링 | [Notion](https://river-pearl-643.notion.site/UnityTeamProject-06bfc7d0cf334de69735aa4340d57176?pvs=4) |

<br>

# 시연 영상  
+ [Ordinary Day](https://youtu.be/z3EsQjbcxCw)

<br>

# 주요 기능  
⚡ 플레이어 상호작용
- Interaction Base : 상호작용 공통 멤버 정의 [[스크립트](PlayerInteraction/Base/InteractionBase.cs)]
- IHandPickable : 손으로 잡을 수 있는 인터페이스 멤버 정의 [[스크립트](PlayerInteraction/Base/IHandPickable.cs)]
- Interaction Implement : Interaction Base 상속, 필요 시 IHandPickable 인터페이스를 다중상속해 각 상호작용 구현 [[스크립트 폴더](PlayerInteraction/Implement)]
- ![상호작용 클래스 다이어그램final drawio](https://github.com/LeeJungHwi/OrdinaryDay_./assets/101587101/8ffd9193-a42c-431c-b543-5641f48aa5c7)
