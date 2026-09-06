# CHANGELOG — Tim Focaccia 팀포카치아 (timfocaccia-sample)

## v0.3 (2026-09-06) 살루메리아 델리 리스킨 — 이탈리아 감성 최대
- **방향 전환**: v0.2 순백 미니멀 "답 아님"(다올) → 상담 후 **살루메리아 델리** 채택. 이탈리아 동네 정육·샌드위치 가게 감성.
- **폰트**: 디스플레이=**Anton**(초압축 볼드 포스터체, `text-transform:uppercase`·weight무시), 스크립트=**Caveat**(손글씨 액센트), 본문/한글=Pretendard. Bricolage·Inter 제거.
- **팔레트**: 크림 bg#F6EEDB·bg2#EFE3C9·card#FFFDF6 + **토마토 red#C0392B**(red-d#A32E22)·**올리브 olive#5F6B33**(olive-d#4C5628)·모르타델라 **pink#E5A9A9**. v0.2 순백/그레이 폐기.
- **모티프**: 레드/크림 어닝 스트라이프(`.stripe`)+올리브 변형(`.stripe.olive`). 이탈리아어 아이브로(Salumeria · Paninoteca / La nostra storia / Fatto in casa / Il locale / Dove siamo), 스크립트 액센트(hero "fatto a mano ~ every morning"·뱃지 "Fatto a mano"·푸터 "Buon appetito!").
- **버튼/포인트 색 이동**: 구 sky 계열 전부 **올리브**로(loc-name·foot-link hover·보조버튼). 메인 CTA=토마토 레드.
- **구성 유지**(v0.2와 동일, Menu 제외): Header→Hero→red/cream 스트라이프→About(#about tim-ham)→올리브 Band(tim-bread-tim)→Space(#space 갤러리9)→Location(혜화·익선)→다크푸터+퀵바. nav=About/Space/Location.
- **AA**: ink/bg 13.78·ink2 5.54·red/bg 4.71(eyebrow·em)·red-d 6.12(링크)·흰/red 5.44·흰/olive 5.77·olive-d 6.81. 전부 ≥4.5 통과.
- ⚠️미결(승계): 배포 보류(다올: 나중에 한꺼번에 수정 후)·폰트 self-host(납품)·메뉴 가격·영업 시작시간·혜화 별도 IG.

## v0.2 (2026-09-06) 순백 미니멀 + Pretendard + 메뉴 임시제거
- **배경 순백(#FFFFFF)**: 주황베이지 팔레트 제거→화이트+뉴트럴그레이(#F5F5F4), ink 중성(#232020). 레드·스카이 액센트는 유지(어닝 스트라이프·밴드·버튼).
- **폰트 전부 Pretendard**(다올: 일단 Pretendard로, 이후 재검토): Bricolage Grotesque·Inter 링크 제거, --disp/--sans/--kr 모두 Pretendard.
- **메뉴 섹션 임시 제거**(나중에 재검토): #menu 섹션·nav/footer Menu 링크·hero "See the Menu" CTA 삭제. 히어로 CTA=Find us + Instagram. 메뉴 전용 사진(sand-1/2/4/5/6·soup·jambong)은 미사용→`.assetsignore` 제외(메뉴 복귀 시 해제).
- **소개 사진 교체**: tim-jambong → tim-ham(신선한 햄·재료). 미니멀 방향.


## v0.1 (2026-09-06) 최초 빌드 — 이탈리안 샌드위치 · 2지점
- **업종/컨셉**: 서울 혜화·익선 수제 포카치아·바게트 샌드위치 전문점. 톤=**이탈리안 델리·따뜻·영어 위주**. 주황빛 베이지 배경 + 고기빛 레드 + 하늘색 포인트 + 화이트.
- **폰트**: 디스플레이=**Bricolage Grotesque**(다올 지정 protipo[Latinotype 따뜻한 그로테스크]의 무료 대체), UI/본문=Inter, 한글=Pretendard. CDN(납품 self-host).
- **색**: bg 주황베이지 #FAF3E3·bg2 #F2E6CD·cream #FBF6EA·ink #33271C·**red #B8443A(고기빛)**·red-d #9C382F(AA)·**sky #6FA8CC(연한 하늘·awning stripe)**·sky-d #3C7BA2(흰글씨 버튼/뱃지 AA). 어닝 스트라이프 모티프(.stripe).
- **구성**: 헤더(Tim Focaccia 워드마크·o 레드) → 히어로(대형 샌드위치+헤드라인 "Handmade focaccia & baguette"+CTA) → 어닝 스트라이프 → About(수제 빵 스토리) → Menu(샌드위치 쇼케이스 6카드·가격은 매장/IG 안내) → 레드 밴드("Made by hand, every morning"+TIM 각인빵) → Space(12칼럼 갤러리 9컷) → Location(혜화·익선 2지점) → 다크 푸터 + 모바일 퀵바(혜화·익선 지도).
- **실데이터**: 혜화=서울 종로구 대학로11길 18 1층(혜화역 4번출구 189m·소나무길 중간)·L.O.20:30·0507-1491-0837·place **1041424953**. 익선=서울 종로구 돈화문로 81-1 1층(종로3가역 3번출구 374m)·L.O.18:30·02-765-1070·place **2070009857**·추석(9/25) 휴무. IG @timfocacciaiksun(2지점 공용). ⚠️영업 시작시간·메뉴 가격 미확보→L.O.만 표기·가격은 "매장/IG 안내".
- **이미지**: 제공 50중 22 webp(2.7MB, tim-*). 미사용 5컷(cauliflower·ham·logo-draw·sand-3·sketch) `.assetsignore` 제외. favicon/apple(레드+T)·og(히어로+텍스트 밴드).
- **마감/안전**: color-scheme·text-size-adjust·overflow-x·keep-all, 고정바 `<div>`, 리빌 html.js 게이팅+데스크톱전용+2.2s폴백, noscript, 앵커 rAF, reduced-motion 리빌 강제(하우스룰), a11y(aria·focus-visible·alt), JSON-LD Restaurant+department 2지점. 폼 없음.
- **AA**: ink/bg 13.1·ink2 5.7·red 4.84(eyebrow)·red-d 6.29(버튼·링크)·흰/red 5.35·흰/sky-d 4.62(하늘버튼·뱃지). 연한 sky는 무텍스트 스트라이프에만.
- **도메인**: og·canonical·JSON-LD = timfocaccia-sample.lgt3232.workers.dev. 인계 시 치환.
- ⚠️미결: GitHub 업로드(`.assetsignore` 정확명·라이브 404)+CF, 라이브 육안검증(폰트·스트라이프·모바일), 폰트 self-host(납품), 메뉴 가격·영업 시작시간 확보 시 반영, 혜화 별도 IG 유무 확인.
