# Daily Todo 웹 파일

Daily Todo 앱과 스토어에서 사용하는 공개 웹 파일 모음이다.

| 파일 | 게시 주소 | 쓰는 곳 |
|---|---|---|
| `app-ads.txt` | 공개 웹 루트 | AdMob 앱 인증 |
| `dailytodo/index.html` | `dailytodo/` | 앱 홈페이지 |
| `dailytodo/privacy.html` | `dailytodo/privacy.html` | 개인정보처리방침 |
| `dailytodo/terms.html` | `dailytodo/terms.html` | 이용약관 |
| `dailytodo/delete-data.html` | `dailytodo/delete-data.html` | 데이터 삭제 요청 안내 |
| `dailytodo/config/ads.json` | `dailytodo/config/ads.json` | 프로덕션 광고 운영 설정 |
| `dailytodo/style.css` | (위 페이지 공용) | |

루트 `index.html`(기존 사이트)은 이 폴더에 없으므로 건드리지 않는다.

## 게시 전에 채울 값

페이지 안의 `［입력 필요: …］`를 모두 채운다. 운영자만 알 수 있는 값이라 추측으로 넣지 않았다.

| 값 | 들어가는 곳 | 비고 |
|---|---|---|
| 운영자 이름 또는 상호 | index, privacy(머리말, 영어 요약), terms | 개인이면 실명 또는 활동명, 사업자면 상호 |
| 시행일(YYYY-MM-DD) | privacy(2곳), terms | 게시하는 날 |
| 개인정보 보호책임자 이름 | privacy 9장 | 개인 운영이면 본인 |
| 사업자등록번호, 통신판매업 신고번호 | terms 머리말 | 해당 없으면 문구 삭제(국내 판매 의무 확인은 RELEASE_USER_ACTIONS D7) |
| 대상 연령 | privacy 6장 | Play 타겟층 설정과 같게 |
| 국외 이전 구체화 여부 | privacy 3장 | 법률 검토 권장. 필요 없으면 표시 줄 삭제 |
| 운영자 직접 환불 정책 | terms 3장 | 없으면 그 줄 삭제 |
| 유료 기능 변경 예고 기간 | terms 6장 | 예: 30일 |
| 관할 법원 | terms 8장 | |
| 구독 기록 삭제 처리 기한 | delete-data 3장 | 예: 요청 후 30일 이내 |

공개 배포 환경의 주소와 연결 방법은 앱·스토어 설정에서 관리한다. 이 문서에는 특정 계정 정보를 기록하지 않는다.
