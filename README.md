## NotionHub
#### Notion에서 작성한 마크다운 파일로 손쉽게 포스팅을 연동하는 기술블로그 서비스

0. 일정
- 21.05.14 : initial commit
- 21년 말까지 운영환경 구축 및 release

1. Tech stack
- SpringBoot2.4 / Java11

2. Branch
- `master` : 추후 release 용
- `dev` : 개발용

2-1. Branch 전략
- `master` 에서 직접 커밋 금지
- `dev` 또는 하위 브랜치에서 commit 후 `master` 로 merge.