# alphaworks-cli

알파웍스 CLI(`alphaworks`)는 이제 **공개 npm**으로 받아요. 이 저장소의 릴리스(실행 파일)는 0.77.0이 마지막이에요.

## 설치

Node 22 이상이 있으면 맥, 리눅스, 윈도우 모두 같은 한 줄이에요.

```sh
npm install -g @alphabro/alphaworks-cli
```

Node가 없으면 먼저 깔아요. 윈도우는 `winget install OpenJS.NodeJS.LTS`, 맥은 `brew install node`예요.

설치한 뒤에는 `alphaworks setup`으로 PC를 점검하고, `alphaworks self-update`로 새 판을 받아요.

자세한 안내는 사내 포털의 시작 가이드를 봐 주세요.

## 예전에 실행 파일로 깔았다면

1. 위 한 줄로 npm 판을 깔아요.
2. 예전 폴더를 지워요. 맥과 리눅스는 `~/.alphaworks/bin`이나 `~/.corp-platform/bin`, 윈도우는 `%USERPROFILE%\.alphaworks\bin`이나 `%USERPROFILE%\.corp-platform\bin`이에요.
3. 셸 시작 파일에 넣었던 그 폴더의 PATH 줄도 지워요. `alphaworks setup`이 지울 줄을 알려 줘요.

예전 릴리스는 지우지 않고 남겨 둬요.
