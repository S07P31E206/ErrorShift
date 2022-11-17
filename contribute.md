# 컨벤션

# Jira

### EPIC

FE_머시기

BE_머시기

배포

회의

기획

설계

산출물

학습

### 이슈 prefix

[epic이름]

### 이슈 suffix

(이름)

# Git commit

[feat] 새로운 기능 추가

[fix] 버그 수정

[docs] 문서

[test] 테스트 코드

[refactor] 코드 리팩토링(기능말고 성능개선)

[style] 코드 의미에 영향을 주지 않는 변경사항 (형식 지정, 세미콜론 누락, 주석 등)

[chore] 빌드, 설정 파일, 기타 큰 의미 업슨 작업

[sync] 작업 동기화

# Git branch

master : 배포

develop : 개발된 기능(feature)을 통합하는 브랜치

docs : 문서작업 브랜치

feature/[part name]/[function name] : 각 기능별 개발을 진행하는 브랜치

release/[version] : 배포 전, 현재까지의 develop 상태를 가져와서 버그 픽스하고 지금 상태까지를 현재 개발 중인 버전으로.

hotfix/[version] : 배포한 것을 급하게 수정

- 브랜치 흐름 예시
    
    ![./assets/Untitled.png](Untitled.png)
    

```markdown
|-- master
		|-- develop
		    |-- frontend
		        |-- feature/frontend/login
		        |-- feature/frontend/feature2
		    |-- backend
		        |-- feature/backend/login
		        |-- feature/backend/feature2
		    |-- blockchain
		        |-- feature/blockchain/login
		        |-- feature/blockchain/feature2
		|-- docs
```

# 코딩

백엔드

- 파일명: PascalCase (ex: UserRepository)
- 패키지명: 소문자
- 클래스: PascalCase (ex : ClassName)
- 변수: camelCase (ex : getId, userPassword)
- 메소드 : camelCase (ex : getId, userPassword)
- 상수: snake_case (ex: FILE_NUMBER)
