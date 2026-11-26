# Time Imposter (술자리 파티 게임)

여럿이 한 폰으로 돌려 하는 술자리 게임 앱. 안드로이드(Capacitor) + AdMob 광고. 앱 ID `com.markstudio.timeimposter2`.

## 파일 구조
- `www/index.html`: 게임 전체 (화면·디자인·기능이 한 파일, 약 210KB라 필요한 부분만 찾아서 읽어요)
- `privacy.html`: 개인정보처리방침
- 안드로이드 빌드: GitHub Actions의 `build-aab.yml` 수동 실행

## 이 프로젝트만의 규칙
- 공개돼도 괜찮은 프로젝트예요. 게임 대사·문구 대량 작성은 Gemini(무료)에 맡기고 Claude가 검수해도 돼요.
- 게임 기획은 game-designer, 개발은 game-developer, 홍보는 sns-writer·store-writer.

## 진행 상황
- 출시용 앱 형태로 만들어져 있어요. 다음 할 일은 아직 정해지지 않았어요 (사장님께 물어보기).

## 본부 기록 (My-project)
- 자세한 계획은 비공개 저장소 `My-project`의 `time-imposter/계획.md`에 있어요.
- 작업이 끝나면 `My-project/time-imposter/작업일지.md`에 한 줄 기록하고, 계획이 바뀌면 `계획.md`도 고쳐요.
- 아이디어는 `My-project/time-imposter/ideas/`, 홍보·영업·스토어 글은 `My-project/time-imposter/marketing/`에 저장해요.
- 이 세션에 `My-project`가 연결돼 있지 않으면 연결해서 기록해요 (연결이 안 되면 사장님께 알려요).

## 공통 규칙
- 사장님은 코딩 초보예요. **쉬운 한국어**로, 결론 → 이유 → 사장님이 할 일 순서로 보고해요.
- **토큰 절약**: 큰 파일·폴더는 통째로 읽지 않아요. `grep`, `head`, 작은 스크립트로 필요한 부분만 봐요. 간단한 일은 부서원을 부르지 않고 바로 처리해요.
- 부서원은 `my-ai-team` 플러그인(자동 설치)에 있어요: idea-maker, researcher, reviewer, tester, marketer, sns-writer, sales-writer, store-writer, game-designer, game-developer.
- 작업이 끝나면 이 파일의 **진행 상황**을 짧게 고치고, My-project 작업일지에도 기록해요.
