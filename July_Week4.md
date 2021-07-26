# 07_4주차

## 0725

## 0726

21시20분 ~ : git add, commit, push 연습

### 특이사항 1. : 
이전 파일 명을 바꾸니까 add 는 되는데 commit가 안되는 경우 발생!?  
이후 다른 md 파일을 생성하여 add를 시도하였으나 fatal: Unable to create ... Another git process seems to be running in this repository 메세지 발생
#### 해결시도 : 
- rm -f ./.git/index.lock -> ???
#### 해결법 : 
명령어 제대로 쳐 ㅄ아 git commit file 명으로 치고 있으니 안되잖아

### 특이사항 2 : 
fatal: invalid gitfile format: July_Week4.md; fatal: Could not read from remote repository.
#### 해결시도 : 
- git remote -v 사용하여 정상 remote가 정상적으로 연결되어있는지 확인
- '미등록 기기에서의 접근..으로 인해 발생..?'
- 쥰내 복잡하네 쒸바거
#### 해결법 :
- 그냥 포기하고 명령어 하라는데로 입력하니까 됨.. 뭐한거냐 나?

