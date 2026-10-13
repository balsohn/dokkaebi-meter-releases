# 도깨비 미터기

Windows용 전투 피해량 미터기입니다. 이 저장소는 배포·사용 안내·오류 제보용이며 소스를 제공하지 않습니다.

## 다운로드

[배포 버전 보기](https://github.com/balsohn/dokkaebi-meter-releases/releases)

## 실행

1. [Npcap](https://npcap.com/#download)을 설치합니다. Wireshark·별도 Python 설치는 필요하지 않습니다.
2. Releases에서 `DokkaebiMeter-Portable.exe` 하나를 받아 실행합니다. 설치 화면이나 압축 해제 작업이 필요하지 않습니다.
3. 미터기가 열린 뒤 게임에 접속합니다. 캐릭터가 안 잡히면 타이틀 화면에서 다시 접속합니다.

창을 종료해도 연결 수집기는 유지됩니다. 연결까지 종료하려면 트레이의 ‘연결 수집기까지 종료’를 선택합니다. 전투 기록은 로컬에 저장되며 서버 공유는 별도 선택입니다.

## 오류 제보

[Issues](https://github.com/balsohn/dokkaebi-meter-releases/issues)에 버전·증상·재현 순서를 남겨 주세요. 로그인 키·인증서·원본 패킷·인증 토큰은 첨부하지 마세요.

프로그램 자체 코드의 오픈소스 사용 허가는 제공하지 않습니다. 타사 구성 요소에는 해당 라이선스가 적용됩니다.

첫 실행 때 필요한 내부 파일을 사용자 계정의 `%LOCALAPPDATA%/DokkaebiMeterPortable`에 자동으로 준비합니다. 다음 실행부터 재사용하며, 실행 파일을 다른 폴더로 옮겨도 사용할 수 있습니다.
