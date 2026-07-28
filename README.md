# 피닉스 디지털 전환 — 시안 (가안 v0.2)

레거시 홈페이지/대리점 업무를, 고객과 대리점을 잇는 요즘 플랫폼으로 전환하는 프로젝트의 **검토용 정적 시안**입니다.

## 구성

| 파일 | 내용 |
|---|---|
| `index.html` | 허브 (두 시안으로 가는 링크) |
| `phoenix-homepage-mockup.html` | 고객용 홈페이지 시안 |
| `phoenix-daerijeom-mockup.html` | 대리점 웹앱 시안 |
| `images/` | 실제 제품 사진(누끼컷) |

> 이 HTML들은 **눈으로 방향을 합의하기 위한 버리는 시안**입니다.
> 승인 후 실제 서비스는 **Next.js(App Router) + Supabase + Vercel**로 새로 구축합니다.

## 지금 바로 보기 (로컬)

`index.html`을 브라우저로 더블클릭하면 됩니다.

## 장인어른께 주소로 드리기 (GitHub Pages, 무료)

1. GitHub에서 새 저장소 생성 (예: `phoenix-mockup`, **Public**)
2. 아래를 복사해 실행 (`USER`/저장소명은 본인 것으로):
   ```bash
   git remote add origin https://github.com/USER/phoenix-mockup.git
   git push -u origin main
   ```
3. 저장소 → **Settings → Pages** → *Deploy from a branch* → `main` / `/(root)` → Save
4. 1~2분 뒤 주소가 나옵니다:
   `https://USER.github.io/phoenix-mockup/`

이 주소를 그대로 장인어른께 드리면 됩니다. (PC·모바일 모두 열림)

## 다음 단계

- [ ] 시안 피드백 반영
- [ ] 실제 제품 가격 확정 (현재는 가안)
- [ ] 83°C 등 위생 문구 법령 근거 확인
- [ ] Next.js + Supabase로 실제 서비스 구축 (견적 폼 저장 → 대리점 자동 배정 → 세제 재주문 알림톡 순)
