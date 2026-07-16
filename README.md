### 조현찬 · Cho HyeonChan

국민대학교 인공지능학부

**AI가 내놓은 답을 그대로 믿지 않는 서비스를 만듭니다.**
LLM의 출력에는 항상 검증 계층을 둡니다. 판정만 던지는 대신 "왜 그런 판단인지"를 함께 내놓는 것이, 사용자가 다음 판단을 스스로 할 수 있게 만든다고 생각합니다.

---

### Projects

**[CoinMaster AI](https://github.com/ChoHyeonChan/coinmaster-ai)** · 개인 프로젝트 (단독 개발)
LLM이 내놓은 매매 판단을 그대로 신뢰하지 않고, 기술지표 기반 검증 계층으로 독립 검증·차단하는 암호화폐 트레이딩 어시스턴트.
`Next.js 14` `TypeScript` `OpenAI API` `Binance API`

**[받을각](https://github.com/ChoHyeonChan/badeulgak)** · 2026 K-AI 콘텐츠 공모전 출품 — **팀장 · 기획 · 개발** · 🔗 [라이브 서비스](https://chohyeonchan.github.io/badeulgak/)
로그인·개인정보 수집 없이 나이·상황 6문항으로, 지금 신청 가능한 정부·지자체 지원제도를 30초 안에 찾아주는 웹앱. 100% AI 바이브코딩으로 개발·배포했습니다.
복지 정보는 환각이 섞이면 치명적이라 매칭을 LLM 호출 없는 결정론적 규칙(자격 하드필터 → 스코어링)으로 설계했고, 입력 가능한 1,184개 조합을 전수 감사해 **자격 위반 추천 0건**을 검증했습니다.
`JavaScript` `GitHub Pages` `GitHub Actions` `공공데이터 API`

**[Pawsitive](https://github.com/ChoHyeonChan/Pawsitive)** · 캡스톤 디자인 — **팀장 · 풀스택 개발**
반려견 통합 관리 AI 플랫폼. 산책 매칭 · 건강 분석 · AI 상담 · 전문가 매칭 · 커뮤니티 · 교육을 하나의 플랫폼으로.
`JavaScript`

**[밥BTI](https://github.com/ChoHyeonChan/2026-kookmin-ai-workflow-team1)** · 국민대 AI 플랫폼 개발 특강 (KMU · NxtCloud · AWS) — **팀장 · 기획 · 개발** · 🏆 **대상**
음식 취향 30초 입력 → 밥메이트 매칭 + 메뉴 추천 + AI 코멘트. 하루 만에 기획부터 S3 배포까지 완주.
결과물 완성도와 Git upstream 협업 과정을 종합 심사해 3인 팀 대상 수상.
상호작용 이력이 없는 콜드스타트 상황이라 행렬분해(ALS/SVD++) 대신 항목별 유사도 가중합을 택했습니다. 정확도를 조금 내주는 대신 **"왜 이 사람과 묶였는지"가 설명되는** 매칭을 얻었습니다.
`HTML` `Firebase Realtime DB` `AWS Bedrock` `S3`

---

### Currently

**unmask** — 계약서의 독소조항과 스미싱 문자의 정체를 판독하는 AI 생활 리스크 서비스
차단하거나 조회해주는 데서 끝나지 않고, 원문의 어느 문장에서 위험이 도출됐는지 근거와 함께 설명합니다.
*CODEGATE 2026 AI 스타트업 해커톤 예선 제출 (2026.07)*
