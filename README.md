# 기기괴담 참가 신청 안내

공개 주소: https://gigi-invitation.vercel.app/

기존 GitHub Pages QR 주소는 위 Vercel 사이트로 자동 이동합니다. 기존 QR 코드 자체에 저장된 GitHub 주소는 변경되지 않으므로, 스캔할 때부터 GitHub 아이디를 보이지 않게 하려면 Vercel 주소로 만든 새 QR을 사용하세요.

## 수정 및 배포

- `site/index.html`: 초대장 화면
- `site/assets/fonts/`: 자체 호스팅 폰트와 라이선스
- `site/config.json`: 안내 화면 오픈 시각과 신청폼 주소
- 루트 `index.html`: 기존 QR 주소의 이동 안내

Vercel 프로젝트는 `gigi-invitation`이며, `site` 폴더에서 `vercel deploy --prod --scope yejins-projects-eeb48249`로 배포합니다. 로컬 프로젝트 연결 정보는 `.vercel/`에 저장되며 Git에 포함하지 않습니다. 새로운 환경에서는 기존 프로젝트에 연결한 뒤 배포하세요.

현재 오픈 시각은 2026년 10월 13일 오후 7시(한국시간)입니다. 이 페이지의 신청 버튼 표시와 Google Forms의 접수 허용은 별도로 작동합니다. 실제 Google Forms 오픈 예약은 폼에 연결된 Apps Script에서 관리합니다.
