# 와이파이 지킴이 — 위협 정보

[와이파이 지킴이](https://github.com/T0C0-AI/wifi) 앱이 쓰는 공유기 위협 정보 데이터예요.

- 출처: [CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) (미국 정부가
  실제 공격에 쓰인 취약점만 모아둔 공식 목록)
- 가정용 공유기·무선 액세스포인트 제조사 관련 항목만 걸러서 정리해요
  (기업용 방화벽·VPN 어플라이언스는 제외)
- `router-kev.json` 파일이 매일 자동으로 갱신돼요 — 원본 저장소의
  `.github/workflows/threat-intel-sync.yml`이 발행해요

이 저장소는 데이터 발행 전용이라 코드는 없어요. 앱 소스코드는
[T0C0-AI/wifi](https://github.com/T0C0-AI/wifi)(비공개)에 있어요.
