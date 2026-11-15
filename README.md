# alphaworks-cli

알파웍스 CLI(`corp-platform`) 실행 파일을 내려받는 곳이에요. 소스 코드는 여기 없어요.

## 설치

맥 · 리눅스

```sh
curl -fsSL https://github.com/AlphaBrothers-Corp/alphaworks-cli/releases/latest/download/install.sh | bash
```

윈도우와 자세한 안내는 사내 포털의 시작 가이드를 봐 주세요.

## 파일 확인

릴리스마다 `SHA256SUMS`와 그 서명 `SHA256SUMS.minisig`가 같이 올라가요. 설치 스크립트와 `corp-platform self-update`가 서명과 해시를 확인한 뒤에만 설치해요.

- **stable**: 최신 릴리스
- **beta**: 사전 릴리스로 표시한 것
