# 07_4주차

## 0725

- 게으름++;

## 0726

21:20 ~ : git add, commit, push 연습

> ### 특이사항 1. : 
> 이전 파일 명을 바꾸니까 add 는 되는데 commit가 안되는 경우 발생!?  
> 이후 다른 md 파일을 생성하여 add를 시도하였으나 fatal: Unable to create ... Another git process seems to be running in this repository  > 메세지 발생
>   > #### 해결시도 : 
>   > - rm -f ./.git/index.lock -> ???
>   > #### 해결법 : 
>   > 명령어 제대로 쳐 ㅄ아 git commit file 명으로 치고 있으니 안되잖아

> ### 특이사항 2 : 
> fatal: invalid gitfile format: July_Week4.md; fatal: Could not read from remote repository.
>   > #### 해결시도 : 
>   > - git remote -v 사용하여 정상 remote가 정상적으로 연결되어있는지 확인
>   > - '미등록 기기에서의 접근..으로 인해 발생..?'
>   > - 쥰내 복잡하네 쒸바거
>   > #### 해결법 :
>   > - 그냥 포기하고 명령어 하라는데로 입력하니까 됨.. 뭐한거냐 나?

22:00 ~ 22:15 : 김버그 강의 수강
> - escape code
> - <a> attr. 재확인.

내일 할 일
> 일단 무지성 강의 따라하기 보다는, 먼저 예제를 보고 만들어 본 후, 맞는지 확인하는 방식으로 가는게 좋을 것 같음
> add;commit;push 연습도 좀 해보기.
> 그리고 내일은 진도좀 빼자,,,


## 0727

13:15 ~ 14:40 : 출근, 김버그 강의 따라하기

> 1. < !DOCTYPE html> 작성법 숙지하기
>   > < head>  
>	> < meta charset="UTF-8">  
>	> < title>FratureBox</title>  
>	> < meta name="viewport" content="width=device-width, initial-scale=1.0,">  
>	> < title>Google Search Result Item</title>  
>	> < link rel="stylesheet" href="./styles.css">  
>   > < /head>  
> 2. < img>태그
>   > src attr. alt attr
>   > 설명하기 모호한 경우 alt값은 비워두는 것을 권장.
> 3. 본 강의에서는 뭔가 박스가 만들어졌는데 내가 만든건 쥰내 조잡하게 생김.
>
> 4. 그리고 가운데 정렬은 어케했누
>   > CSS의 영역인듯 합니다. 빠르게 진도를 나가십시오 휴-먼
> aria-label="" attr (< a>)
> 5. pagination는 table가 아닌 list로 처리하는 것
> 6. WAI-aria 사용 방법  
> -> Breadcrumble&Pagination 을 참고하세요.
> 7. 웹 페이지상에서 어떠한 정보를 담고 있지 않은 대상은 굳이 html markup을 해 줄 필요가 줄어든다는 것.  
> -> 대신 css에서의 처리가 필요.
> 8. 와 가볍게 볼 생각이었는데 하나하나 듣는게 시간이 되게 오래걸리네;  
> ㄴ ㅈ밥은 본인이었구여 ㅋㅋ

16:50 ~ 18:30 : 게으름++;
> - dl 사용법 숙지하기 (선언(dl), key(dt)-value(dd))
> - 뭔가 부가정보 혹은 별도의 분화된 양식이 필요한 경우에 span을 쓰는 듯 함.
> - 왜 내가 하면 저양반이랑 항상 다르게 나오는거냐?  
> < div>를 어떻게 조직하는지에 따라서 달라지는거같은데,,, 결국 나는 외부에서 정해진 css 파일을 기반으로 만드는 것이기 때문에, 해당 css 파일이 의도한 대로 html markup을 하지 않으면 개판나는거겠지?  
> 그러면 결국 css 파일 읽는 법이나, 조직하는 법을 배워야겠다는 결론으로 귀결되는 긋 함. 
> - 이미지만 보고 마크업 한 후, 스스로 피드백 하는 방식으로는 많은 진도를 나가기에 약간의 어려움이 있는 듯 하다. 너무 미련한 방식인가 싶다.