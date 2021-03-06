![DODO](https://raw.githubusercontent.com/alwaysdodo/works/master/static/logo.png)

Do! What do want to do!
매달 모여서 두두 하는 두두!

## What is DODO?

두두는 **"해야지 해야지 하면서 미루던 것"** 들을 다같이 모여서 밤새 해치우는 일입니다. <br>
혼자 하는 것 보다 모여서 하는 것이 집중력에 더 도움이 되며, <br>

각 분야의 여러사람들을 만나 서로 이야기도 나눠보아요.

Do 에서 Done 으로 !!  
Do! What do want to do!  
해해안해, 해야지해야지 하면서 안하는 것들 해!  
뭐든지, Do두 Do두 !!  


## 파일 작성 방법

날짜 디렉토리 하위에 자신의 영어 이름으로 된 파일을 하나 만드시면 됩니다.

Raw 버튼을 누르면 파일 소스가 보이니까 그걸로 복사해서 사용하세요. :smile:

[참고용 디렉토리](./1970-01-01)

- 자신이 할일 목록만 간략히 적고 싶을 때 : [샘플파일](./1970-01-01/dummy.md)
- 자신이 한일을 길게 상세하게 적고 싶을 때 : [샘플파일](./1970-01-01/wan2land.md)

## Console TIP

Pull request 를 날리는 과정에서 Fork를 하게 되실텐데 다음
명령어가 도움이 되실 겁니다.

```
# Fork 한 곳에서 clone
git clone https://github.com/<USER_ID>/works.git

# origin 을 fork 원격 저장소로, upstream 을 alwaysdodo 원격 저장소로 지정
git remote add upstream https://github.com/alwaysdodo/works.git

# fork repository 는 내가 작업할 때만 fetch 하여 사용하시면 됩니다.
git fetch --all

# --ff-only: fast-forward 가 정상적이지 않을경우 에러
git pull --ff-only upstream master
```
