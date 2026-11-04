# 개발자 포트폴리오

채용 담당자에게 대표 프로젝트와 기술 역량을 소개하는 한국어 포트폴리오 초안입니다.

## 로컬 미리보기

탐색기에서 `index.html`을 브라우저로 엽니다. 내용을 수정한 뒤 브라우저를 새로고침하면 반영됩니다.

## 콘텐츠 수정

- `index.html`의 소개 영역에서 이름, 지원 직무, 한 줄 소개를 수정합니다. 브라우저 탭 제목과 페이지 설명도 실제 내용에 맞게 수정합니다.
- 대표 프로젝트 두 개를 실제 사례로 바꾸고, 문제와 본인의 역할, 기술적 판단, 확인한 결과를 적습니다. 공개할 저장소나 데모 URL이 있으면 해당 프로젝트 제목 아래에 링크를 추가합니다.
- 기술 역량에는 직접 적용한 기술과 사용 맥락을 적습니다. 연락처에는 공개할 GitHub 프로필이나 이메일 링크를 추가합니다.
- 실제 콘텐츠를 모두 채운 뒤 화면의 ‘작성 중’, ‘작성 예시’, ‘초안’ 표시와 대괄호로 표시된 작성 안내를 정리합니다.
- 색상, 간격, 모바일 레이아웃은 `styles.css`에서 수정합니다.

## GitHub Pages에 게시

1. 개인 사이트 주소를 쓰려면 GitHub에 `<username>.github.io` 저장소를 만듭니다. 프로젝트 주소를 쓰려면 포트폴리오용 저장소를 선택합니다.
2. `index.html`, `styles.css`, `.nojekyll`, `README.md`를 저장소 루트에 두고 `main` 브랜치로 푸시합니다.
3. 저장소의 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**를 선택합니다. 브랜치를 `main`, 폴더를 `/(root)`로 지정하고 저장합니다.
4. 배포가 완료되면 Pages 설정에 표시된 주소를 열어 스타일과 링크를 확인합니다. 기본 주소는 개인 사이트의 경우 `https://<username>.github.io/`, 프로젝트 사이트의 경우 `https://<username>.github.io/<repository>/`입니다.

[GitHub Pages 게시 소스 설정](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
