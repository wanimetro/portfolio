# Sowon Oh — Portfolio

Live: https://wanimetro.github.io/portfolio/

정적 HTML 한 페이지라 빌드 없이 바로 열립니다. 로컬에서는 `index.html`을 브라우저로 열면 돼요.

## 프로젝트 수정
`index.html` 아래쪽 `<script>`의 `projects` 배열만 고치면 카드와 상세 모달이 같이 바뀝니다.
XR 프로젝트는 `projects` 배열에 `cat:['xr']`로 추가하면 XR 그룹(맨 위)에 들어가요.

## 이미지·영상 넣을 위치
없는 파일은 화면에 안 나오고 일러스트로 대체됩니다.

```
img/sagye/cover.jpg  (+ screens.jpg)
img/planflow/cover.jpg (+ 1-login, 2-dashboard, 3-ai-planning, 4-screen-spec .jpg)
img/lookitup/cover.jpg
img/lookitup/results.jpg
img/petitparis/cover.jpg (+ giant-feet, hide, tech-slide .jpg)
media/petitparis-demo.mp4
media/petitparis-presentation.pdf
media/lookitup-demo.mp4           (YouTube 링크로 대체 가능)
media/lookitup-presentation.pdf
```
썸네일은 16:10 비율이 가장 잘 맞아요.
