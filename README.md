# git repository 복제 테스트
`git clone` 할 때 `mirror` 옵션으로 모든 이력을 그대로 복제
1. `git clone --mirror [ 복제할 git repository 주소 ]`
2. `cd [ repository이름.git ]`
3. `git remote set-url --push origin [ 새로운 git repository 주소 ]`
4. `git push --mirror`

### 수학 계산을 위한 코드를 제공하는 프로젝트
**1. calculator.py** : `계산기`에 있는 기능들을 제공하는 모듈
- add, subtract 등
