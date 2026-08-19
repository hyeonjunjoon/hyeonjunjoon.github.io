# web-resume

`docs/소개서_이스트게임즈.md`와 `docs/간단소개글.md`를 바탕으로 만든 정적 웹 이력서. [promm.dev/about](https://promm.dev/about/)의 미니멀한 타이포그래피 중심 레이아웃(단일 컬럼, 시스템 폰트, 얇은 구분선, 프로젝트별 기술스택 태그)을 참고해 만들었습니다.

빌드 도구 없이 `index.html` + `style.css`만으로 동작하는 순수 정적 페이지입니다.

## 미리보기

`index.html`을 브라우저로 바로 열면 됩니다 (Google Fonts를 CDN에서 불러오므로 인터넷 연결 필요).

```
open index.html
```

## 채워야 할 부분

- 연락처는 GitHub(`hyeonjunjoon`)와 이메일(`wannagohome718@gmail.com`)만 넣어뒀습니다. 블로그나 다른 채널이 있으면 `.contact` 목록에 추가하면 됩니다.
- 하단 "마지막 업데이트" 날짜는 수동으로 관리합니다.

## 배포

빌드 과정이 없어서 정적 호스팅 아무 곳에나 바로 올릴 수 있습니다. GitHub Pages가 가장 간단합니다.

1. 이 폴더(`web-resume`)를 별도 저장소로 만들거나, 기존 저장소의 `docs/` 폴더로 넣기
2. 저장소 Settings → Pages에서 배포 브랜치/폴더 지정
3. `https://hyeonjunjoon.github.io/<repo>/` 형태로 접근 가능

Cloudflare Pages(이미 DeltaX에서 써본 스택)에 올리는 것도 좋은 선택입니다: 저장소 연결 후 빌드 명령 없이 루트 디렉토리를 그대로 배포하면 됩니다.
