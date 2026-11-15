# alphaworks-cli

알파웍스 CLI(`corp-platform`) 실행 파일을 내려받는 곳이에요. 소스 코드는 여기 없어요.

## 설치

맥, 리눅스, 윈도우 Git Bash

```sh
curl -fsSL https://github.com/AlphaBrothers-Corp/alphaworks-cli/releases/latest/download/install.sh | bash
```

윈도우 PowerShell

```powershell
irm https://github.com/AlphaBrothers-Corp/alphaworks-cli/releases/latest/download/install.ps1 | iex
```

자세한 안내는 사내 포털의 시작 가이드를 봐 주세요. 설치한 뒤에는 `corp-platform self-update`로 새 판을 받아요.

## 채널

- **stable**: 최신 릴리스
- **beta**: 사전 릴리스로 올린 것. `curl -fsSL …/install.sh | CORP_PLATFORM_CHANNEL=beta bash` 또는 `corp-platform self-update --channel beta`

## 파일 확인

릴리스마다 `SHA256SUMS`와 그 서명 `SHA256SUMS.minisig`가 같이 올라가요. 설치 스크립트는 받은 파일의 sha256을 확인하고, `corp-platform self-update`는 거기에 더해 서명까지 확인한 뒤에만 바꿔요.
