<p align="center">
  <img src="https://raw.githubusercontent.com/HireDiverSity-Play/.github/main/profile/assets/logo.png" width="96" alt="HireDiverSity Play Logo" />
</p>

<h1 align="center">HireDiverSity Play</h1>

<p align="center">
  HireDiverSity의 실험, 프로토타입, 미니 서비스, QA 검증을 위한 Playground입니다.
</p>

<p align="center">
  <a href="https://github.com/HireDiverSity-Play/playground-hub">Playground Hub</a>
  ·
  <a href="https://github.com/HireDiverSity-Play/loveclinic-web">Loveclinic Web</a>
  ·
  <a href="https://github.com/HireDiverSity-Play/name-matching">name-matching</a>
</p>

---

## About

**HireDiverSity Play**는 새로운 아이디어를 빠르게 만들고, 검증하고, 배포하기 위한 실험 공간입니다.

이 조직에서는 다음과 같은 작업을 다룹니다.

- 신규 서비스 아이디어 검증
- 랜딩 페이지 및 홍보 페이지 제작
- 미니 서비스 / 인터랙션 페이지 제작
- Netlify 기반 Preview / Production 배포 검증
- Supabase 연동 실험
- QA 자동화 및 테스트 환경 검증

---

## Featured Repositories

| Repository | Purpose |
|---|---|
| `playground-hub` | Playground 전체 허브 및 서비스 진입점 |
| `loveclinic-web` | 개별 실험 서비스 |

> 전체 Repository는 상단의 **Repositories** 탭에서 확인할 수 있습니다.

---

## Technical Direction

기술 스택은 프로젝트별로 유연하게 선택합니다.

공통 기준은 단순합니다.

- 빠르게 만들 수 있어야 합니다.
- Preview 배포가 쉬워야 합니다.
- 유지보수 부담이 작아야 합니다.
- 각 Repository의 README에 실제 실행 방법과 사용 기술을 남깁니다.

---

## Development & Deployment Flow

HireDiverSity Play는 `main` 브랜치에 직접 반영하지 않고, Pull Request 기반으로 변경사항을 검증합니다.

```txt
feature branch
  ↓
Pull Request
  ↓
Netlify Deploy Preview
  ↓
Review / QA
  ↓
Merge to main
  ↓
Production Deploy
