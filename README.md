# TIL 

<details>
<summary>2022-09-21</summary>


### 1. 리눅스 커맨드라인 기초
```
# print working directory
pwd
```
- ~ : 사용자의 root directory에 있음을 의미

```
# change directory
cd
```
- cd만 입력하면 root directory로 이동
- cd .. 을 입력하면, 이전 디렉토리로 이동
- / 는 절대경로를 의미


```
ls // list
```
- ls 뒤에는 -a, -l 옵션을 붙일 수 있음
> - a : 숨긴 파일/폴더까지 보여줌
> - l : 자세한 내용 (권한, 수정 날짜 등) 출력
> - 합쳐서 -al 옵션 사용 가능


### vim 사용법
> window에서 git bash를 사용할 때, default editor로 vim을 세팅했기 때문에, git을 사용하려면 반드시 vim을 사용할 줄 알아야 한다
(최소 파일 수정하는 것까지는 알아야 git을 다룰 수 있음)
```
vim // 문자 편집기
```
- vim test.txt 등으로 없는 파일 즉시 생성 가능
- vim 에디터 처음 켰을 때에는 명령 모드로 진입 (입력 불가능)
- 입력모드 전환 ->  `i`
- 입력모드 빠져나오기 -> `esc`
- 단순 저장 -> `:w` + `enter`(단순 저장, write)
- vim 빠져나오기 -> `:q` (빠져나오기, quit)
- 저장하고 빠져나오기 -> `:wq!` (write and quit)

```
vim 에서 문서 비정상적 종료 되었을 경우
```
- 리커버리 모드가 켜짐
- 대문자 R로 들어가서 저장하고, :wq로 나옴
- 다시 들어가도 attention 명령 출력됨
> - 이 경우, 메세지에 출력되는 .파일명.txt.swp 파일 삭제
> - rm.파일명.txt.swp로 지우거나, 디렉토리에서 바로 삭제


### commit

#### 정의
- The "commit" commend is used to save your changes to the local repository.
- 커밋 하나는 독립적인 버전을 나타냄
- The git commit command captures a snapshot of the project's currently staged changes.
- 스냅샷(사진)과 유사

#### 언제 커밋을 만드는가?
- logical한 변경이 있을 때 만듦
- 가능하다면 커밋 단위는 작을 수록 좋음 (rollback을 위함)


### Git ignore
`.gitignore`이란?
> - Project에 원하지 않는 Backup File이나 Log File , 혹은 컴파일 된 파일들을 Git에서 제외시킬수 있는 설정 File이다.
> - 운영 체계, 사용 툴, 언어 선택
> - https://www.toptal.com/developers/gitignore

</details>




<details>
<summary>2023-07-24</summary>
  
- Atomic Habits 1챕터 -> Good Habits, Bad Habits  <br>
- html 문법 -> 토글 만들기 (details)  <br>
- 시간 관리 타임 트래커

</details>


<details>
<summary>2023-07-25</summary>
  
- vscode 에 git bash 기본 터미널 설정 변경
    - git bash 터미널 vscode 바깥에 뜨는 문제 해결
- git clone & commit & push 구조 떠올리기
- 신체 교정 운동
  
</details>


<details>
<summary>2023-07-26</summary>
  
- 개인 과제 -> 인게임 보상이 결제에 미치는 영향 파악
    - 가설 기각, 후속 분석 위한 새로운 가설 제안 필요
- 타임 트래커 -> 시간 계획 지키기 성공
    - 기상 시간, 출근 전 독서, To Do 해결 
  
</details>


<details>
<summary>2023-07-27</summary>
  
- 주니어 데이터 분석가 모임 참석
    - 데잇걸즈, 지난 6개월 회고, 앞으로의 6개월 계획
  
</details>




<details>
<summary>2023-07-28</summary>
  
- 개인 과제 발전안
- 타임 트래커
- 삶 돌보기 
  
</details>


<details>
<summary>2023-07-30</summary>
  
- 타임 트래커
- 가족과 시간 보내기
- 내 삶 돌봄, 감사일기
  
</details>



<details>
<summary>2023-07-31</summary>
  
- 타임 트래커
- 운동, 신체 교정
- 내 삶 돌봄, 감사일기
  
</details>


<details>
<summary>2023-08-01</summary>
  
- 타임 트래커
- 시뮬레이터 > 깃 브랜치, 머지, 풀 리퀘스트 (for 협업)
  
</details>




<details>
<summary>2023-08-02</summary>
  
- 타임 트래커
- python 프로그래밍, 깃으로 협업 익숙해지기
- 삶 돌보기 (to do)
  
</details>


<details>
<summary>2023-08-03</summary>
  
- 타임 트래커
- python 프로그래밍 (딕셔너리), 깃 명령어
- 삶 돌보기 (to do)
  
</details>


<details>
<summary>2023-08-04</summary>
  
- 타임 트래커
- 삶 돌보기 (to do)
  
</details>


<details>
<summary>2023-08-05</summary>
  
- 타임 트래커
- 업무 develop
    - 타임트래커 주니어 플래너 챌린지 참여
  
</details>

<details>
<summary>2023-08-06</summary>
  
- 타임 트래커
- 업무 develop
    - 타임트래커 주니어 플래너 챌린지 참여
    - excel 데이터 도구 사용
  
</details>

<details>
<summary>2023-08-07</summary>
  
- 주니어 플래너 (타임트래커 체험단)
- 업무 develop
    - python class 이해
        - https://rebro.kr/133
        - 내 언어로 정리하고, 시뮬 코드에 적용 필요
- 운동 (pt)        
  
</details>


<details>
<summary>2023-08-08</summary>
  
- 주니어 플래너 (타임트래커 체험단)
- 삶 챙기기
    - 휴가 전 집 정리
</details>

<details>
<summary>2023-08-09</summary>
  
> - 8/9 ~ 8/13 여름 휴가
- 주니어 플래너 (타임트래커 체험단) 
</details>



<details>
<summary>2023-08-10</summary>
  
> - 8/9 ~ 8/13 여름 휴가
- 주니어 플래너 (타임트래커 체험단) 
</details>

<details>
<summary>2023-08-11</summary>
  
> - 8/9 ~ 8/13 여름 휴가
- 주니어 플래너 (타임트래커 체험단) 
</details>





<details>
<summary>2023-08-13</summary>
  
- 여름 휴가 끝! 월요일 업무 준비
    - 놓친 슬랙 메세지 리딩, 업무 따라가기
    - 타임 트래커 작성
- 삶 챙기기
    - 짐 정리, 몸 건강 챙기기
  
</details>



<details>
<summary>2023-08-13</summary>
  
- 주니어 트래커
- python develop
    - 함수 안에서 함수 호출하기
    - 기능 class로 묶기
  
</details>

<details>
<summary>2023-08-14</summary>
  
- 삶 돌보기 : 필라테스
- 주니어 트래커
- 업무 발전
    - 업무 회고 : 업무 발전을 위한 공부는 업무 외 시간에
    - 업무 발전을 위해 필요한 공부
        - SQL (튜닝이 가능한 수준)
        - Python (원하는 기능 구현할 수 있는 수준)
  
</details>


<details>
<summary>2023-08-15</summary>
  
- 주니어 트래커
- 업무 발전 python develop
    - 함수 안에서 함수 호출
    - py 파일끼리 서로 호출하기
  
</details>



<details>
<summary>2023-08-16</summary>
  
- 삶 돌보기 : pt
- 주니어 트래커
- 업무 발전
    - 업무 회고 : 업무사항 전달 전 셀프 체크
        - 놓친 건 없는가? 제대로 된 정보를 전달하고 있는가?
    - Python 시뮬레이터 완성 (내가 해냄!)
        - 헤메던 부분 해결 : 누적 점수화 / 라운드 변경 시 새 변수에 누적합으로 넣어줌
  
</details>


<details>
<summary>2023-08-21</summary>
  
- 주니어 트래커
- 업무 발전
    - 업무 회고 : 상사는 무엇을 궁금해 하는가?
        - 묻지 않아도 추가로 전달할 수 있는 "쓸모있는 정보"
        - "믿을 수 있는" 정보
    - Python 시뮬레이터 디버깅
        - 앨범 리워드 수정
        - 포인트 시스템 리워드 수정
        - 추가 필요 : 포인트 시스템 리워드 -> 카드팩
  
</details>



<details>
<summary>2023-08-22</summary>
    
- 삶 돌보기 : 필라테스!
- 주니어 트래커
- 업무 발전
    - 업무 체크리스트 만들기 : 내가 자주 실수하는 것들 모아서, 다시 실수하지 않도록
- 팀 따또같 발표자료 준비 : Python 관련 (블로그 업데이트 하기)
  
</details>



<details>
<summary>2023-08-22</summary>
    
- 주니어 트래커
- 업무 발전
    - 시뮬레이션 필요한 데이터 컬럼 타입 추가
- 팀 따또같 모임 : Python 공부 내용 발표
  
</details>


<details>
<summary>2023-08-28</summary>
    
- 주니어 트래커
- 업무 발전
    - 시뮬레이션 필요한 데이터 추가 (sp)
    - 표준 편차, z-score를 활용한 7일 이동평균 트래킹
  
</details>



<details>
<summary>2023-08-29</summary>

- 삶 돌보기 : 필라테스
- 주니어 트래커
- 업무 발전
    - 시뮬레이션 데이터 / 실제 데이터 비교
    - 업무 커뮤니케이션 코스트 줄이기 : 오픈된 장소에서, 모두가 볼 수 있게, 다시 되물을만한 정보는 미리 제공하여 시간 낭비 하지 않기
  
</details>


<details>
<summary>2023-08-31</summary>

- 삶 돌보기 : 피티
- 주니어 트래커
- 업무 발전
    - 시뮬레이션 데이터 / 실제 데이터 비교 : 퀘스트 난이도 의도된 것인지 기획에 전달 (시뮬레이션 상 너무 어려워짐)
    - 업무 커뮤니케이션 코스트 줄이기 : 시뮬레이션 버전과 공유 문서 버전 맞추기
  
</details>



<details>
<summary>2023-09-01</summary>

- 삶 돌보기 : 집 정리
- 주니어 트래커
- 업무 발전
    - AURORA / REDSHIFT 데이터 집계 차이 발견
        - 1. 씽크가 늦게 되어서 다를 수 있음
        - 2. aurora에서 update쳤어도, 해당 유저가 계속 접속중이면 db에 반영되지 않아서 다를 수 있음
        - 3. 인수 합병 때 넘어온 데이터들이 있어서, 인수 이후 한 번도 들어오지 않았다면 새로운 register_date가 생성되었을 수 있음
  
</details>


<details>
<summary>2023-09-03</summary>

- 삶 돌보기 : 씽크대 보수공사, 집 정리
- 주니어 트래커
  
</details>


<details>
<summary>2023-09-04</summary>

- 주니어 트래커
- 업무 발전 : 협업 상황에서 스프레드 시트 활용해서 협업 cost 줄이기, 파라미터 입력창 (쿼리 베이스) 사용해서 대시보드 수정하기
  
</details>


<details>
<summary>2023-09-05</summary>

- 삶 돌보기 : 필라테스
- 주니어 트래커
- 업무 발전
    - 데이터 시각화 : 척도가 다른 두 데이터를 한 그래프 안에 표현해야 할 때 -> 이중축, 같은 형태의 그래프 (선 + 선) 사용하기, 기준 맞추기 (7일 이동평균이라면, 나머지 하나도 7일 이동평균으로)
</details>


<details>
<summary>2023-09-06</summary>

- 삶 돌보기 : 식습관 관리 시작
- 주니어 트래커
- 업무 발전
    - 협업! 내가 지금 해야하는 일 주체적으로 찾아서 하기
</details>


<details>
<summary>2023-09-08</summary>

- 삶 돌보기 : 식습관 관리, 걷기 운동
- 주니어 트래커
- 업무 발전
    - 내가 해온 일 & 성과 정리, 앞으로 해야할 일과 내고싶은 성과를 위해 해야할 일 정리

</details>


<details>
<summary>2023-09-09</summary>

- 삶 돌보기 : 식습관 관리
- 경력 기술서 업데이트, 포트폴리오 페이지 업데이트

</details>


<details>
<summary>2023-09-10</summary>

- 삶 돌보기 : 식습관 관리, 걷기 운동
- 지난 주 업무 회고, 다음 주 해야 할 일 정리
    - 지난 주 업무 아쉬웠던 점 : 한 번에 처리할 수 있는 일을 두 번씩 나누어 해서 두 배의 시간이 쓰였음. 한 번에 할 수 있는 일이 뭐가 있는지 확인해보고, 시간을 효율적으로 써야 다른 걸 할 시간이 늘어남
    - 다음 주 해야할 일 : 월요일 출근하자마자 라이브 모니터링 (필수!!)

</details>




<details>
<summary>2023-09-11</summary>

- 주니어 트래커
- 형우 깃 입문 도와주기
    - 깃 기본 설정
    - 원격 저장소 <> 로컬 연결
    - 브랜치 개념 알려주기
    - 단순 저장으로 안 될 때 명령어
        - git add -A
        - ctrl + s re test
        - 한컴 문제인지 확인
<<<<<<< HEAD
        - ignore 파일 삭제
=======
>>>>>>> test

</details>