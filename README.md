# Team Handbook

Git과 GitHub의 이슈, 작업 브랜치, PR 리뷰를 연습하는 공개 조직 저장소입니다.

## 역할

A(wpalswpa), B(zozu001), C(tlswlgus960-prog, 팀장) 세 명이 진행합니다. 각자 맡은 일은 docs/01-intro.md의 "팀원 역할"에 있습니다.

## 진행 상태와 사용 방법

초기 설정을 완료하고 문서 PR 리뷰를 진행 중입니다. 세 명 모두 조직 구성원이며 B는 write 권한, A와 C는 조직 Owner입니다. 모든 문서 작업은 이슈를 만든 뒤 브랜치에서 진행하고, 작성자가 아닌 팀원의 승인 후 PR로 병합합니다.
초기 설정 이후 main에 직접 push하지 않습니다. 공개 전환 후 main에 PR 승인 1회 보호를 설정했습니다. 관리자에게도 같은 규칙이 적용됩니다.

## 문서와 읽는 순서

문서는 각각의 PR 승인·병합 뒤 main에 나타납니다.

1. docs/01-intro.md: 프로젝트 소개
2. docs/02-branch-strategy.md: 브랜치 전략
3. docs/03-commit-convention.md: 커밋 컨벤션
4. docs/04-faq.md: FAQ

.github/ISSUE_TEMPLATE/documentation.md는 문서 이슈 양식, .github/pull_request_template.md는 PR 양식입니다.
코드 실행이나 패키지 설치가 필요한 프로젝트는 아닙니다. 클론한 뒤 문서를 읽고 GitHub의 이슈와 PR 상태를 확인합니다.
