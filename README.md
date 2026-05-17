# BackLink

> Windows용 WordPress 자동 포스팅 + 백링크 빌더 — 다중 사이트 / AI 본문 생성 / 예약 발행.

[ReWorld](https://reworld.kr) 데스크톱 앱의 **release 배포 채널**입니다. 소스 코드는 별도 모노레포(`reworld-kr/ReWorld`)에서 관리되고, 이 repo는 빌드 산출물(`backlink.exe`, NSIS installer, checksums)만 호스팅합니다.

## 다운로드

[**최신 버전 다운로드 ↓**](https://github.com/reworld-kr/BackLink/releases/latest)

- `backlink.exe` — bare 실행 파일 (압축/설치 없이 즉시 실행)
- `backlink_setup.exe` — NSIS 설치 마법사 (사용자 디렉터리에 설치, UAC 불필요)
- `checksums.txt` — SHA-256 무결성 검증

설치 후 자동 업데이트가 켜져 있어 새 버전 출시 시 다음 실행에 백그라운드 적용됩니다.

## 주요 기능

- 다중 워드프레스 사이트 계정 관리
- 제목 / 본문 / 이미지 자동 합성 파이프라인
- OpenAI 연동으로 본문 변형 생성
- 발행 큐 + 실행 로그
- 이미지 자동 가공 (워터마크, 리사이즈)
- 예약 / 반복 발행

## 시스템 요구사항

- Windows 10 / 11 (x64)
- 사용자 디렉터리 설치 → 관리자 권한 / UAC 불필요
- 자동 업데이트 — GitHub Release 채널 모니터링

## 라이선스

- **첫 실행 시 3일 무료 체험** 자동 발급
- 정식 라이선스는 [reworld.kr/pricing](https://reworld.kr/pricing) 에서 구매
- 라이선스 관리 / 본인 라이선스 조회: [reworld.kr/account](https://reworld.kr/account)

데스크톱 + 모바일 + HomePage 모두 **동일 ReWorld 계정**을 공유합니다. 한 번 로그인하면 보유한 라이선스가 모든 플랫폼에 동일 적용됩니다.

## 문의 / 버그 리포트

- 일반 문의: [reworld.kr/contact](https://reworld.kr/contact)
- 버그 / 기능 요청: [Issues](https://github.com/reworld-kr/BackLink/issues)

## 관련 링크

- [BackLink 제품 페이지](https://reworld.kr/apps/backlink)
- [ReWorld 앱 그리드](https://reworld.kr/apps)
- [이용약관](https://reworld.kr/legal/terms) / [개인정보처리방침](https://reworld.kr/legal/privacy)
