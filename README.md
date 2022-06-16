# Semi Project 
## 구해줘 바다


### 네이밍 규칙
- 파스칼 케이스 : 띄어쓰기를 모두 붙여서 표현, 각 단어의 첫 글자는 대문자 / Ex) Example, IsJumping
- 스네이크 케이스 : 만약 대문자가 겹칠 시 띄어쓰기를 _로 표현 / Ex) WBP_MainMenu
- 영어로만 표기, 한글 금지
- 특수문자 사용 금지(예외 bool 변수명은 '?' 사용 가능) 

- 블루 프린트 : BP_ / Ex) BP_Player
- 머터리얼 : M_ / Ex) M_CharacterBase
- 머터리얼 인스 턴스 : MI_ / Ex) MI_Character
- 스태틱 메시 : SM_ / Ex) SM_Box
- 스켈레탈 메시 : SKM_ / Ex) SKM_Mouse
- 텍스처 : T_ / Ex) T_Character
- 위젯블루프린트 : WBP_ / Ex) WBP_MainMenu

### 플로우 차트
![GameFlowChart](https://user-images.githubusercontent.com/29518708/174001247-fb272278-928c-4bdf-82bc-48cb1c4291e3.png)

### 메인 메뉴
1. 맵 - MainMenu
2. UI
 1. 기능
 게임 시작
 나가기

### 필드
1. 맵 - OceanField
[참고용]
![LevelSample](https://user-images.githubusercontent.com/29518708/174003570-7478fb62-d288-48d3-afde-77c7eeba68be.png)

2. 플레이어_이동
 1. 캐릭터
![Player](https://user-images.githubusercontent.com/29518708/174002536-d677699f-e5f6-448a-ad0a-2970af9b5afc.png)

 2. 시점
 3인칭 / 캐릭터 뒤 카메라 고정, 마우스로 회전
 3. 점프 기능
3. 적_이동
 1. 캐릭터
 2. 비헤이비어트리 예상

### 전투
1. 맵 - BattleField
 간단한 전투 레벨
2. 플레이어_전투
 1. 능력치 
 HP, MP, EXP, AD(공격력)
 2. 전투
 공격
 스킬
3. 적_전투
 1. 능력치
 HP, MP, AD(공격력)
 2. 전투
 공격
 스킬
