# GitHub Branch Naming Convention

## Purpose

브랜치 이름을 일관되게 사용하면 작업 목적을 빠르게 파악할 수 있고, 협업과 리뷰가 더 쉬워집니다.

## Recommended Format

다음 형식을 기본으로 사용합니다.

```text
type/short-description
```

필요하면 이 형식도 사용할 수 있습니다.

```text
type/issue-number-short-description
```

## Branch Types

자주 쓰는 타입은 아래와 같습니다.

- `feature`: 새로운 기능 개발
- `fix`: 버그 수정
- `hotfix`: 운영 중 긴급 수정
- `refactor`: 동작 변경 없이 구조 개선
- `docs`: 문서 수정
- `test`: 테스트 추가 또는 수정
- `chore`: 설정, 패키지, 빌드, 기타 유지보수 작업
- `style`: 코드 포맷팅, 공백, 세미콜론 등 비기능 변경

## Naming Rules

- 모두 소문자를 사용합니다.
- 단어 구분은 하이픈(`-`)을 사용합니다.
- 공백은 사용하지 않습니다.
- 브랜치 이름은 짧고 의미 있게 작성합니다.
- 가능하면 한 브랜치에는 한 가지 목적만 담습니다.
- 이슈 번호가 있다면 앞쪽에 포함해 추적하기 쉽게 합니다.

## Examples

좋은 예시:

```text
feature/login-page
feature/123-user-profile
fix/navbar-overlap
hotfix/payment-timeout
refactor/auth-service
docs/api-setup-guide
chore/update-eslint-config
```

피해야 할 예시:

```text
Feature/LoginPage
fix bug
mybranch
test123
feature/fix-login-and-navbar-and-footer
```

## Team Tips

- Pull Request 제목과 브랜치 목적이 자연스럽게 연결되도록 작성합니다.
- 브랜치를 오래 유지하지 말고, 가능한 작게 나눠서 자주 머지합니다.
- 공통 규칙은 팀 문서나 README에 함께 명시해 두는 것이 좋습니다.

## Suggested Team Standard

우리 팀에서는 아래 규칙을 기본값으로 추천합니다.

```text
type/issue-number-short-description
```

예:

```text
feature/128-add-social-login
fix/241-resolve-mobile-header-bug
docs/310-update-deployment-guide
```
