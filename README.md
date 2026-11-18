# sinae-apps

작은 웹앱 모음 (GitHub Pages).

## 주소

- 전체 목록: https://shiny7093-sudo.github.io/sinae-apps/
- This Is Us 영어공부: https://shiny7093-sudo.github.io/sinae-apps/this-is-us/
- 우리집 부부·육아 허브: https://shiny7093-sudo.github.io/sinae-apps/couple/ (4자리 비밀번호 잠금)

## 구성

| 경로 | 내용 |
| --- | --- |
| `index.html` | 앱 목록 페이지 |
| `this-is-us/index.html` | 〈This Is Us〉 시즌1 대사로 배우는 영어공부 웹앱 (단일 파일, 외부 의존 없음) |
| `couple/index.html` | 부부 일기·가계부·출산 준비 허브 (첫 화면 4자리 PIN 잠금, 데이터는 각 기기 브라우저에만 저장) |

새 앱은 `폴더명/index.html` 형태로 추가하고 `index.html` 목록에 링크를 걸면 됩니다.
GitHub Pages는 `gh-pages` 브랜치를 배포 소스로 사용하므로, `main`에 반영한 뒤 `gh-pages`도 함께 갱신해야 사이트에 나타납니다.
