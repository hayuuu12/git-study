# 소개. Blog Service
-------------------
-블로그 검색과 관련된 서비스를 제공합니다.

# 빌드 결과물
------------
- [결과물 다운로드](https://google.com)

# 환경 소개
- JAVA 17
- SprongBoot 2.7.3
- ...
# modile - application
----------------------
- 도메인 엔티티, 입력 포트, ....
  - `domain`
  - `service`
  - `port/input`


### 사용

> $ `http GET http://localhost8080...`


### 요청

Parameter

| Name    | Type | Description | Required |
|---------|------|-------------|----------|
| `keyword` | `String` | 검색 키워드 | O |
| `url`     | `String` | 블로그 | X |
