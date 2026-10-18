# kacastc-redirect

`https://kacastc.mooo.com` 으로 들어오는 모든 요청을 `https://astc-lms.web.app` 의 **같은 경로·쿼리**로 넘기는 리디렉션 전용 저장소.

- 운영 시스템 저장소를 private으로 전환하면서 GitHub Pages를 이 저장소로 옮겼다.
  기존에 인쇄·배포한 QR 코드와 링크(`kacastc.mooo.com/...`)가 계속 동작하게 하기 위함.
- `index.html` 과 `404.html` 은 같은 파일이다(없는 경로도 404 페이지가 받아 넘긴다).
- DNS: FreeDNS `kacastc.mooo.com` A 레코드 → GitHub Pages IP 4개(185.199.108~111.153).
- 이 저장소에는 리디렉션 파일만 둔다. 코드·설정·내부 문서는 넣지 않는다.
