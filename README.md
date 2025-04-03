## Summary
- Github Action 프로젝트 도입전 이것저것 실험해보자

## Goal
- build variant에 따라 바라보는 backend endpoint 다르게 설정
- test 검증
- branch develop/release/main 에 따라 각각 dev/stg/prod 로 배포
- dev, stg : firebase distribution에 업로드
- prod : playstore 비공개 테스트로 업로드
- CI/CD 완료시 slack에 노티
