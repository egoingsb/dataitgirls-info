# dataitgirls 정보 공유 페이지

# 설치해주세요.
(순서대로 설치해주세요. 동시에 설치하지 말아주세요.)
- https://git-scm.com/
- https://www.sourcetreeapp.com/
- vscode : https://code.visualstudio.com/
  <br> git config --global core.editor "code --wait"
- gistory : python3 설치 후 pip3 install gistory
- p4merge : https://www.perforce.com/ko/perforce/product/10

## p4merge 설정법
```
mac
git config --global mergetool.p4merge.path /Applications/p4merge.app/Contents/MacOS/p4merge
git config --global merge.tool p4merge
git config --global mergetool.prompt false

windows
git config mergetool.p4merge.path 'C:\Program Files\Perforce\p4merge.exe'
git config merge.tool p4merge
```

# 가입해주세요
- https://github.com/

# 혼자 공부할 때 이용해주세요. 
- 지식지도 - https://seomal.org
- GIT - https://opentutorials.org/module/3733
- CLI - https://opentutorials.org/module/3747

# 수련
```
1. 프로젝트 폴더 만들기
2. VS CODE에 프로젝트 폴더를 등록
3. 프로젝트 폴더를 저장소로 만든다. git init 
4. 새로운 파일을 만들고 수정한다. (work.txt)
5. 스테이지로 등록한다. git add filename
6. 버전을 만든다. git commit -am "commit message"
7. 실험적인 프로젝트를 위해서 브랜치를 만든다. git branch exp
8. exp에서 작업을 진행한다. git checkout exp
9. 버전을 생성한다. 
10. master에서 작업을 진행한다. git checkout master
11. 버전을 생성한다. 
12. exp의 작업을 master로 병합한다. git checkout master && git merge exp
13. 충돌 상황을 재현해본다. 
14. github에 원격 저장소를 만든다. 
15. 지금까지 작업한 지역 저장소를 github에 원격 저상소에 등록한다. git remote add origin ....
16. 지역 저장소를 원격 저장소로 업로드 한다. git push
17. 각자의 컴퓨터에 지역 저장소를 복제한다. git clone ...
18. 각자 작업해서 버전을 만들고 push 동시에 해본다. 
```
