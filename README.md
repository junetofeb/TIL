# TIL 

## 2022-09-21

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

```
vim // 문자 편집기
```
- vim test.txt 등으로 없는 파일 즉시 생성 가능
- 입력모드 : i
- 입력모드 -> 명령모드 전환 : esc
- 저장하고 빠져나오기 -> :wq!
> - :wq (write and quit)

```
vim 에서 문서 비정상적 종료 되었을 경우
```
- 리커버리 모드가 켜짐
- 대문자 R로 들어가서 저장하고, :wq로 나옴
- 다시 들어가도 attention 명령 출력됨
> - 이 경우, 메세지에 출력되는 .파일명.txt.swp 파일 삭제
> - rm.파일명.txt.swp로 지우거나, 디렉토리에서 바로 삭제

