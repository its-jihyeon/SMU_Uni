# 시스템보안 코드

**2025년 2학기 시스템보안** 수업의 실습 및 과제 코드 저장소입니다.
<br>

## 📂 Source Code Index

| 파일명 | 주제 | 설명 |
|:---|:---|:---|
| **week_04.pdf** | SetUID 및 권한 분석 | `system()`과 `execve()` 함수의 차이점 분석 및 `/etc/shadow` 접근을 통한 권한 상승 실습 |
| **week_05.pdf** | Buffer Overflow (BoF) | 스택의 리턴 주소(RET)를 조작하여 쉘코드를 실행하고 루트 권한을 획득하는 공격 분석 |
| **week_07.pdf** | Return-to-libc (ret2libc) | NX(No-Execute) 기법을 우회하기 위해 공유 라이브러리 함수 주소로 실행 흐름을 변경하는 공격 |
| **week_09.pdf** | ROP 및 Chain Attack | 다수의 가젯(Gadget)을 연결하여 `setuid()`, `system()` 등을 연속 호출하는 연쇄 공격 구현 |
| **week_10.pdf** | Format String Attack | `%n`, `%hn` 포맷 스트링을 이용해 메모리 특정 주소에 데이터를 기록하고 값을 변조하는 실습 |
| **week_11.pdf** | Race Condition (TOCTOU) | `renameat2()`를 활용해 권한 검사 시점과 사용 시점의 차이를 악용한 파일 심볼릭 링크 교체 공격 |
| **week_12.pdf** | Dirty COW (CVE-2016-5195) | 리눅스 커널의 COW 결함을 이용해 읽기 전용 파일인 `/etc/passwd`를 수정하는 익스플로잇 실습 |
| **week_13.pdf** | 64-bit Shellcoding | x86-64 아키텍처 환경에서 `syscall`을 이용한 `execve` 시스템 콜 기반 쉘코드 제작 및 실행 |
| **week_14.pdf** | Redirection & Reverse Shell | 표준 출력 재지정과 `/dev/tcp` 장치를 활용하여 원격지에서 시스템 쉘을 제어하는 공격 분석 |
