# 인터넷응용보안 코드

**2025년 1학기 인터넷응용보안** 수업의 실습 및 과제 코드 저장소입니다.
<br>

## 📂 Source Code Index

| 파일명 | 주제 | 설명 |
|:---|:---|:---|
| **week_02.pdf** | HTTP 프로토콜 기초 | HTTP GET/POST 요청 구조 분석 및 매직 넘버를 이용한 패킷 검증 실습 |
| **week_03.pdf** | 세션 하이재킹 (Hijack Session) | Burp Suite를 통해 로그인 통신 패킷을 캡처하고 유효한 세션 ID를 탈취하는 과정 분석 |
| **week_04.pdf** | IDOR 및 쿠키 변조 | Insecure Direct Object Reference 취약점을 이용한 타 사용자 프로필 접근 및 인증 쿠키 변조 실습 |
| **week_05.pdf** | 암호학적 결함 (Crypto Basics) | RSA 개인키 분석을 통해 Modulus 값을 도출하고 OpenSSL 기반의 디지털 서명 생성 실습 |
| **week_06.pdf** | SQL Injection 기초 | `' OR 1=1 --` 등을 활용한 인증 우회 및 데이터베이스 테이블 삭제를 통한 가용성 침해 실습 |
| **week_07.pdf** | Blind SQL Injection | 참/거짓 응답 차이를 이용한 계층적 데이터 추출 및 신규 계정 등록을 통한 관리자 권한 우회 |
| **week_09.pdf** | DOM 기반 XSS | JavaScript 라우터(`GoatRouter.js`) 분석을 통해 URL 파라미터로 악성 스크립트를 삽입하는 기법 학습 |
| **week_11.pdf** | XXE (XML External Entity) | JSON 형식을 XML로 변환 후 외부 엔티티를 정의하여 서버 내부 파일(`file:///`)을 조회하는 공격 분석 |
| **week_12.pdf** | 인증 메커니즘 우회 | 패킷 변조를 통해 2단계 인증(2FA) 및 보안 질문 검증 로직을 무력화하는 기법 실습 |
| **week_13.pdf** | JWT 보안 및 권한 상승 | JSON Web Token의 구조(Header, Payload, Signature)를 분석하고 위조된 토큰으로 관리자 권한 획득 |
