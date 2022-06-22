# Semi Project 
# 구해줘 바다

## 네이밍 규칙
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

## 플로우 차트
![GameFlowChart](https://user-images.githubusercontent.com/29518708/174001247-fb272278-928c-4bdf-82bc-48cb1c4291e3.png)

## 폰트
- 빛의 계승자체

## 메인 메뉴
### 맵(MainMenu)
- UI
1. 기능
- 게임 시작
- 나가기

## 필드
### 맵(OceanField)
[참고용]

![LevelSample](https://user-images.githubusercontent.com/29518708/174003570-7478fb62-d288-48d3-afde-77c7eeba68be.png)

[작업중]

![Ocean](https://user-images.githubusercontent.com/29518708/174526261-c56ae544-238a-451d-8f3d-04cc7450c0ba.png)

- 외부 회복 시스템
- 적의 해당 구역마다 컨셉에 맞는 쓰레기 배치(적 처치시 사라짐)
- 해당 구역 적 모두 처치 시 가로막고 있던 요소 해금

### 플레이어(이동)
- 캐릭터

![Player](https://user-images.githubusercontent.com/29518708/174002536-d677699f-e5f6-448a-ad0a-2970af9b5afc.png)

- 시점
3인칭 / 캐릭터 뒤 카메라 고정, 마우스로 회전

- 점프 기능

### 적_이동

- 캐릭터

- 비헤이비어트리 예상

## 전투
### UI
[참고용]

![PocketmonBattleScene](https://user-images.githubusercontent.com/29518708/174214193-eb75b3ea-3517-42a3-9ef2-7763786ae4e6.jpg)

[작업중]

![BattleUI](https://user-images.githubusercontent.com/29518708/174622741-aa6a5a23-1008-4f64-b722-33e0b27be1ea.png)

마우스 클릭 방식
### 맵(BattleField)
간단한 전투 레벨 예상

### 플레이어(전투)
1. 능력치 
 - HP, MP, EXP, AD(공격력)

2. 전투
 - 공격(빗자루로 때리기)
 - 스킬 / 회복(춤), 강타(발차기), 리스크 공격(턴을 소비 후 다음턴에 마법 공격 / Stage01 클리어 시 해금), 파워업(춤 / 3턴 공격력 증가)
 - 도망가기

### 적(전투)
1. 능력치
 - HP, MP, AD(공격력)

2. 종류
### Trash Man
- 전투
 - 공격
 - 스킬 (도트 데미지)
 - 힐

### Drum
- 전투
 - 공격
 - 스킬 (강공격)
 - 힐

### The Boss
- 전투
 - 공격
 - 스킬 (강화)
 - 힐

