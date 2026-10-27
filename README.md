# Double Command

오른쪽 ⌘(또는 선택한 수정키) 한 번 탭으로 한/영 입력 소스를 전환하고, 두 번 탭(⌘⌘)하면 방금 입력한 마지막 단어를 반대 자판으로 바로 고쳐 주는 macOS 메뉴 막대 앱.

## 설치

```sh
brew install --cask cgpathos/tap/double-command
```

또는 [Releases](https://github.com/cgpathos/double-command/releases)에서 `.dmg`를 받아 `Double Command.app`을 응용 프로그램 폴더로 옮긴다. macOS 13 이상, Apple Silicon·Intel 모두 지원.

## 권한

키 입력을 읽고(탭 판정) 치환할 글자를 입력하기 위해 **손쉬운 사용** 권한이 필요하다. 첫 실행 때 안내 창이 열리며, 시스템 설정 › 개인정보 보호 및 보안 › 손쉬운 사용(macOS 27은 "Device Control and Data Access")에서 Double Command를 켠다.

입력 내용은 메모리의 마지막 단어 버퍼에만 머물고 디스크·로그·네트워크로 나가지 않는다. 암호 입력(보안 입력) 중에는 기록하지 않는다.

## 업데이트

앱이 하루 한 번 업데이트를 확인하고(메뉴 › 업데이트 확인…), brew로 설치했다면 `brew upgrade --cask double-command`로도 올릴 수 있다.

이 저장소는 배포 전용이다(Releases·appcast). 소스는 비공개.
