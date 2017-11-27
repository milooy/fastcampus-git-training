# fastcampus-git-training


## Tutorial

### part.1 Fork Style (commit, push,fetch, pull request)
- 본인 이름의 새로운 폴더 만들기 (e.g. milooy)
- 팜므어 번역기 만들기 (라이브러리, simple hcj, 배포) (참고: http://milooy.github.io/femme-translator/)
    - index.html를 만들고, input의 텍스트를 button을 누르면 변환된 텍스트를 보여주도록 한다
    - ![hangul.js](https://github.com/e-/Hangul.js)로 자모음 재배치
    - github pages로 배포
- master저장소 추가
- fetch하고 최신 master 커밋에서 rebase하기
- Push하고 master브랜치로 pull request
- `git subtree push --prefix 본인폴더이름 origin gh-pages`


### part.2 Single Repo Style (rebase, branch, pull request)
- 원본 리포 클론받기
- 'feature/본인아이디'로 브랜치 만들기
- README의 contributers에 본인 이름 적고, github pages로 배포한 url 적기
- fetch하고 최신 master 커밋에서 rebase하기
- 만든 브랜치에서 master로 pull request

## Contributor
- @milooy: http://milooy.github.io/femme-translator/