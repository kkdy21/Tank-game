# Tank-game
C언어로만튼 탱크 슈팅게임

### 프로그램기능
- 대기방에서 채팅, 귓속말 기능
- 대기방에서 팀선택, 팀채팅, ready기능
- 정상적인 플레이가 가능한 다양한 랜덤맵 생성 알고리즘
- 4방향 이동, 방향에 따른 대포발사
- 2:2 탱크 게임으로 1만점 점수 획득시 승리
- 총알발사비용으로 총알 난사시 점수가 -점될수 있음.
- 독수리 잡을시 +1000
- 플레이어 잡을시 +500
- 벽 제거시 +100
- 1만점 먼저 획득한사람 우승

### 개발환경 
- Linux Ubuntu 20.04
- C 언어
- Vi editor

### 맡은 파트
- 탱크게임 전체 총괄, 구현

### 느낀점 
- 멀티가 되는 게임을 만들면서 방대한양의 데이터 처리를 와 모든 클라이언트들의 동기화를 어
떻게 해야할지 고민이 되었다.
동기화를 위해 서버에서 모든 데이터 처리를 해주고 맵을 전송하는 식으로 했는데 서버에 부
담을 주는 방식이라 이게 맞는 방법인지 잘 모르겠다. 보통의 게임회사에서는 어떻게 처리를
하는지 궁금하다.
탱크게임에서 플레이어들과 플레이어들의 총알을 구현하는데 구조체를 활용했고 이번 과제를
통해 구조체의 유용함을 알수있었다.
나름 완성도 있는 게임을 만들게 되어 뿌듯했다.

### 구현내용

<img width="723" alt="image" src="https://user-images.githubusercontent.com/86215246/208306063-1483a011-5dba-421b-8adc-b7dc8be034d2.png">
<img width="723" alt="image" src="https://user-images.githubusercontent.com/86215246/208306068-e043d8ed-b76b-4560-8c4f-c3a5aefdb60a.png">
<img width="723" alt="image" src="https://user-images.githubusercontent.com/86215246/208306073-9340355e-849b-4c1b-ba3d-bbce73a3f860.png">


<img src="https://user-images.githubusercontent.com/86215246/196715079-b3f35df6-d2a7-4521-87b1-8f4aafecaf75.mp4"/>
