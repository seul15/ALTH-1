
## 🏆 ALTH
알쓰들의 Algorithm Study (2022)

- 김민겸
- 원민재
- 이슬

## 👩‍💻 시간

> 월요일 9시
> 수요일 9시 
> 금요일 9시


## 😎 운영 방식

1. 일주일에 한 챕터씩, 그 챕터에 해당하는 문제를 푼다. 

2. 스터디원은 하루에 하나 이상 씩 문제를 가져와서 백준 그룹에 문제를 게시한다. (전주 토, 일요일에 시간제한 없이 올리도록 한다.)

3. 줌을 이용한 모임 시, 이전 스터디 모임에서 올린 문제를 풀이하고 다음 사람이 문제를 게시하고 스터디를 종료한다. 

## 📕 교재 및 언어

- 코딩 테스트를 위한 자료 구조와 알고리즘 with C++
- 언어 : C++

## 👀 새로 바뀐 ALTH 사용법
README2.md 에 정리해두었으니 확인해주세요 (관리자의 요청으로 여기에도 넣습니당)     
[README2.md 연결](https://github.com/m2nja201/ALTH-1/blob/96bad69512aa5b5f870d580cadb366dc00c60227/README2.md)    
### 📣 어떻게 했능가!!
1. **fork** 를 해준다.
2. ``` git clone {저장소 url} ```작성 => 새로운 파일이 생성된다.
3. ``` git branch {branch_name} ``` 작성 => 새로운 branch 생성
4. ``` git checkout {branch_name} ``` 작성 => 해당 branch로 작업 위치가 변경
5. ``` git add {file_name} ``` 작성
6. ``` git commit -m "[자신이름] 날짜 시간 update " ```   ex) ```[원민재] 0211 13:25```  📌📌📌
7. ``` git checkout main ``` 작성 => main으로 작업 위치 변경
8. ``` git merge {branch_name} ``` 작성 => merge
9. ``` git push origin main ``` 작성 => push

### ⭐ 주의 해야 할 점
**push 하기 전에 항상 pull 해주기!**
```
git checkout main
git pull upstream main // ALTH 레포 자신의 레포로 pull 하기
git push origin main // 내 레포에 반영하기
git checkout {branch_name}
git merge main
```
### 💬 그 이후
1. 자신의 레포에서 pull request를 새로 만든다.
2. organization의 레포에서 **모든 팀원들**은 새로바뀐 사항을 읽어보고, comment 혹은 approve를 남긴다.
3. 관리자는 해당 pull request를 merge한다.       
         
### 🚨 이상한 에디터가 뜬다 ! 
뭔가 충돌이 나서 merge가 자동적으로 되지 않을 때 나오는 에디터입니다       
무조건 이걸로 해결해야지! 하지 마시고 뭐가 문제인지 충분히 생각 후 괜찮다 생각되면 그때 사용하세용          
![Untitled](https://user-images.githubusercontent.com/80443295/156373356-765e8268-36ae-4599-8222-de906a4896bf.png)
```
i // i 키를 눌러서 insert 모드로 바꾸기
// 노란색 부분에 commit message 적기
// esc 키를 눌러서 insert 모드에서 나가기
:wq // :wq를 누르면 merge 성공
```
---

## 💕 How to initiate and collaborate?

**0. 해당 저장소를 fork하여 자신의 깃허브의 Repository로 가져간다.**

**1. Visual Studio에서 빈 프로젝트를 하나 판 뒤, 터미널 창에서 (Ctrl + ` )**

``` cd [프로젝트 이름] ```

소스파일은 제일 루트 디렉터리가 아닌 한 디렉터리 더 들어가서 저장되기 때문에 폴더 안에 들어가줘야 함.

```
git remote add origin https://github.com/seul15/ALTH.git

git remote add upstream https://github.com/MingyeomKim/ALTH.git
```

이렇게 두 개의 저장소를 현재 프로젝트에 위치 시킨다. 

``` git remote -v ```

이 명령어를 통해 저장소를 확인할 것


**2. 브랜치 생성하기**

```
git branch MingyeomKim
```


**3. 소스 코드 생성 후 원격 저장소에 Push할 경우**

```
git add "파일이름.cpp"

git commit -m "[김민겸] 1931 회의실 배정"

git push origin MingyeomKim
```

**4. Pull Request 만들기**

위의 과정까지 완료하면 MingyeomKim/ALTH에 자동으로 PullRequest가 올라간다. 
다른 팀원이 Pull Request 확인 후 Comment 달 수 있음. 더 좋은 코드를 고민할 기회를 만들어주자!
모든 팀원이 해당 Pull Request에 Approve를 누르면 MingyeomKim/ALTH 의 MingyeomKim 브랜치에 Merge 가능

![image](https://user-images.githubusercontent.com/67851124/151692409-a1ba2114-e40e-4cfc-8d17-9c1313bba3f1.png)



![image](https://user-images.githubusercontent.com/67851124/151692819-7963470b-0b2d-4341-857d-c0240d1f06f4.png)
