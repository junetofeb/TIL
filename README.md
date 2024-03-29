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
        - 한컴 문제 아니고, git add . 을 원래 했었는데 이 부분을 -am으로 대체하는 과정에서 생긴 문제 ㅎㅎ;
<<<<<<< HEAD
        - ignore 파일 삭제
=======
>>>>>>> test

</details>



<details>
<summary>2023-09-12</summary>

- 삶 돌보기 : 식습관 관리, 필라테스
- 업무 발전 :  
    - 지표 정의 : n시점 이후에 획득한 카드, register_date / update_date 중 어떤 지표를 사용해서 집계할 것인지 
        -> update_date 사용하기로 (획득한 시점 이후에 오픈한 경우 새로운 아이템을 획득하기 때문에 집계 필요)
    - 데이터 시각화 : 읽는 이가 원하는 시각 자료 만들기
        - 내가 생각했던 보기 편한 자료는 단위를 10 단위로 잘라서 x축에 나타내는 것이었지만, 읽는이(헤드)는 그렇게 생각하지 않음. 리대시의 순서 오더 문제로 인해 단위를 0부터 수치화 해서 표현했는데, 단위를 변환해서 읽는 것이 아닌 0~ 수치 그대로 해석해서 곤란했음. 
        - 시간이 얼마나 걸렸고, 얼마나 멋진 코드를 짰는지가 중요한 게 아님. 단순하고 때로는 무식하더라도 읽는 이가 이 자료를 보고 전달하고자 하는 바를 명확하게 이해할 수 있도록 데이터를 표현하는 것이 분석가에게는 중요한 덕목이 될 것.

</details>




<details>
<summary>2023-09-13</summary>

- 삶 돌보기 : 식습관 관리, 작은 성공 경험 만들기 (포트폴리오에 1시간 쓰기)
- 업무 발전 :  
    - 주체적 업무 수행 : 기획팀에 단순히 데이터만 던져줄 수 있는 일이었지만, 내가 먼저 이런 저런 제안안을 줬기 때문에 wc 천장 수치 집계는 나의 업무가 되었음. 앞으로도 내가 아쉬움을 느끼는 부분들 (우리는 단순히 숫자만 주는 부서가 아닌데, 모든 의사결정은 기획팀이 하는 것 같다고 느껴왔음) 에 있어 주체적이고 능동적으로 일할 필요가 있다!
        -내가 먼저 제안안을 가져갔기 때문에 잘했다고 칭찬받은 것. 말씀했던 내용 (그래프, 수치) 만 가져갔다면 실장님께 인정받기 어려웠을 테다. 시키는 일도 못하는 단계 -> 시키는 일은 해내는 단계 -> 시키지 않았는데 생각하지 못한 것까지 해오는 단계로 나아가기 위해 계속해서 고민하자!

</details>


<details>
<summary>2023-09-14</summary>

- 삶 돌보기 : 식습관 관리, 주니어 트래커, 작은 성공 경험 만들기 (포트폴리오에 1시간 쓰기)
- 업무 발전 : 
    - 데이터 그립 사용법 익히기
    - 슈퍼셋 사용법 익히기

</details>

<details>
<summary>2023-09-15</summary>

- 삶 돌보기 : 식습관 관리, 주니어 트래커, 운동(PT)
- 업무 발전 : 
    - 슈퍼셋에 익숙해지기
    - 파이썬 스터디 참여

</details>

<details>
<summary>2023-09-16</summary>

- 삶 돌보기 : 식습관 관리, 주니어 트래커
- 데잇걸즈 네트워킹 모임 참석
    - 다양한 산업에서 데이터 분석가/기획자/개발자로 일하는 데잇걸즈 1~6기 구성원들의 생생한 직무 이야기를 들을 수 있었다
    - 더 열심히 살아야겠다! 더 공부하고, 업무에 적용하고, 발전시켜나가며 이들에게 도움받고, 도움줄 수 있는 구성원이 되고 싶은 열망이 더더욱 커졌다
    - 앞으로 일을 대할 때 어떤 마음가짐으로 일을 대해야 할지 깊게 고민할 수 있는 자리였다


</details>


<details>
<summary>2023-09-17</summary>

- 삶 돌보기 : 식습관 관리, 주니어 플래너(주니어리)
- 트래커스 브랜딩 모임 참여

</details>

<details>
<summary>2023-09-18</summary>

- 삶 돌보기 : 식습관 관리, 주니어 플래너(주니어리)
- 트래커스 브랜딩 모임 인증

</details>



<details>
<summary>2023-09-19</summary>

- 삶 돌보기 : 식습관 관리, 운동(필라테스)
- 트래커스 브랜딩 모임 참여, 인증
- 업무 스터디 : Python 스터디

</details>


<details>
<summary>2023-09-20</summary>

- 삶 돌보기 : 식습관 관리, 개인 운동
- 트래커스 브랜딩 모임 참여, 인증
- 업무 발전 : Python
    - 엄청 멋지고 대단한 코드가 아니더라도 이가 없으면 잇몸으로의 정신으로, 내가 할 줄 아는 방법을 동원해서 해냈다!! 멋진 코드, 대단한 코드도 좋지만 내가 할 수 있는 방법을 동원해서 due date를 맞추는 게 더 중요하다

</details>



<details>
<summary>2023-09-22</summary>

- 삶 돌보기 : 식습관 관리
- 트래커스 브랜딩 모임 참여, 인증
</details>



<details>
<summary>2023-09-22</summary>

- 삶 돌보기 : 식습관 관리, 운동 (PT)
- 트래커스 브랜딩 모임 참여, 인증
- 업무 발전 : SQL - Redash Alert
    - 처음 하는 앨럿 만들기 업무라 많이 헤메고 어려웠고, 내가 못 할 것 같았지만 결국 해냈다. 다 사람이 하는 일이고 못 할 일은 없다. 처음이라 미숙할 수는 있지만 할 수 있는 일이라고 생각하고 하나씩 문제를 해결해 나가면 된다는 걸 배운 하루.
</details>



<details>
<summary>2023-09-23</summary>

- 삶 돌보기 : - 
- 트래커스 브랜딩 모임 참여, 인증
- 개인 회고 : 나를 돌보지 않으니 하루가 무너지는 걸 알았다. 내일은 조금 더 힘내서 나를 돌아보고, 챙겨보자!
</details>


<details>
<summary>2023-09-24</summary>

- 삶 돌보기 : 식습관 관리
- 트래커스 브랜딩 모임 참여, 인증 - 일 주일 회고
- 이력서, 경력기술서 업데이트
</details>


<details>
<summary>2023-09-25</summary>

- 삶 돌보기 : 식습관 관리
- 트래커스 브랜딩 모임 참여, 인증
- 이력서, 경력기술서 업데이트
</details>



<details>
<summary>2023-09-26</summary>

- 삶 돌보기 : 식습관 관리
- 트래커스 브랜딩 모임 참여, 인증
- 성과 : 열심히 해온 결과가 있었던 날!! 대견하다. 스스로에게 자신감을 갖고 앞으로도 계속 앞으로 나아가자.
</details>



<details>
<summary>2023-09-27</summary>

- 삶 돌보기 : 식습관 관리
- 트래커스 브랜딩 모임 참여, 인증
- 영적 시간 : 가족들과 시간 보내기 (아버지 생신!) 가족의 소중함을 알게 된 하루
- 지적 시간 : 채용 과제 초안 그리기
</details>



<details>
<summary>2023-09-28</summary>

- 트래커스 브랜딩 모임 참여, 인증
- 영적 시간 : 가족들과 시간 보내기
- 지적 시간 : 채용 과제
</details>




<details>
<summary>2023-09-29</summary>

- 트래커스 브랜딩 모임 참여, 인증
- 영적 시간 : 가족들과 시간 보내기 (추석 당일!)
- 지적 시간 : 채용 과제 -> 가족들과 시간도 보내고, 채용 과제 하러 오후에 내 시간도 잘 사용했다. 트래커스 덕분이다. 앞으로도 지금처럼 시간을 잘 관리해서 시간 관리의 마스터가 되어보자!
</details>


<details>
<summary>2023-09-30</summary>

- 트래커스 브랜딩 모임 참여, 인증
    - 트래커스 모임 참여율 100% !! 진짜 대견하다
- 지적 시간 : 채용 과제
- 영적 시간 : 놀고 싶은 마음 이겨내고 과제 하러 서울로 왔다. 아쉽지만 지금 당장 내 눈 앞에 놓인 task에 집중하자!
</details>

<details>
<summary>2023-10-01</summary>

- 트래커스 브랜딩 모임 참여, 인증
    - 트래커스 모임 참여율 100% 으로 완주 끝!!
- 지적 시간 : 채용 과제
- 영적 시간 : 아침 시간 활용하기 위해서 일부러 당근 약속 잡고 일찍 일어났다. 오후에 낮잠 꾹 참고 지금 해야할 일에 집중했다. 
</details>


<details>
<summary>2023-10-02</summary>

- 지적 시간 : 채용 과제
- 영적 시간 : 아침에 일어나서 바로 샤워하고 정신 깨워서 할 일 수행했다! 수면시간을 컨트롤 하지 못하는 게 내심 불만이었는데, 앞으로도 오늘처럼만 해도 좋을 것 같다
</details>




<details>
<summary>2023-10-03</summary>

- 지적 시간 : 채용 과제
- 영적 시간 : 아침에 일어나서 운동 다녀오고, 컨디션 조절을 아주 잘 했다!! 아주 아주 뿌듯하다
- 업무 : 라이브 모니터링 별 문제 없이 잘 수행되었다. 모니터링 시간 전에 제대로 작동하는 지 다시 한 번 확인했기 때문에 문제가 없을 수 있었다.
</details>




<details>
<summary>2023-10-04</summary>

- 지적 시간 : 채용 과제
</details>


<details>
<summary>2023-10-05</summary>

- 지적 시간 : 채용 과제
</details>



<details>
<summary>2023-10-06</summary>

- 지적 시간 : 채용 과제
</details>




<details>
<summary>2023-10-06</summary>

- 지적 시간 : 트래커스 열정상, 트래커스 서포터 회의
</details>




<details>
<summary>2023-10-09</summary>

- 지적 시간 : 브랜딩 트래커스 서포터 회의, 트래커스 참여
</details>





<details>
<summary>2023-10-10</summary>

- 지적 시간 : 브랜딩 트래커스 참여, 면접 준비
- 영적 시간 : 나 돌보기, 미뤄둔 일 해치우기 (집안일)
</details>




<details>
<summary>2023-10-11</summary>

- 지적 시간 : 브랜딩 트래커스 참여, 면접 준비
- 영적 시간 : 나 돌보기, 미뤄둔 일 해치우기 (분갈이)
</details>


<details>
<summary>2023-10-12</summary>

- 지적 시간 : 브랜딩 트래커스 참여, 면접 준비
- 영적 시간 : 나 돌보기, 미뤄둔 일 해치우기 (분갈이)
</details>



<details>
<summary>2023-10-13</summary>

- 지적 시간 : 면접 준비
</details>



<details>
<summary>2023-10-14</summary>

- 지적 시간 : 면접 준비
- 영적 시간 : 냉장고 정리, 무한한 서포트를 돕는 옆 사람에게 감사
</details>



<details>
<summary>2023-10-15</summary>

- 지적 시간 : 면접 준비
- 영적 시간 : 무한한 서포트를 돕는 옆 사람에게 감사!
</details>


<details>
<summary>2023-10-16</summary>

- 지적 시간 : 면접 준비, 화상 연습
</details>


<details>
<summary>2023-10-16</summary>

- 지적 시간 : 면접, 지원
</details>


<details>
<summary>2023-10-23</summary>

- 영적 시간 : 운동(필라테스)
</details>

<details>
<summary>2023-10-25</summary>

- 영적 시간 : 운동(피티)
</details>


<details>
<summary>2023-10-26</summary>

- 사회적 시간 : 데잇걸즈 - 카타출 모임
- 지적 시간 : 멘토링 발표자료 준비
</details>
