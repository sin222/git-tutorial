#GIT 자주 사용하는 명령어정리

자주 사용하는 기본적인 명령어들을 정리했습니다.
- 최근 수정일 : 2018-09-16

##저장소 생성(초기화) 하기
'''bash
git init # 저장소 생성
'''

##커밋하기
'''bash
git add README.md
git status
git commit -m "init: README.md"
git log --decorate=full --oneline --grah

##브랜치 생성하기
'''bash
git checkout -b readme
'''

## 머지하기
'''bash
git merge readme --no-ff
'''

# LICENSE
이 저장소는 WTFPL 라이선스에 의해 보호를 받습니다.

