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