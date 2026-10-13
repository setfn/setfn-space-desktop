# SetFN Space 데스크톱

SetFN Space 데스크톱 앱(Windows)의 설치 파일을 배포하는 저장소입니다. 소스 코드는 이 저장소에 없습니다.

This repository hosts the installers for the SetFN Space desktop app (Windows). It does not contain source code.

## 내려받기

- [최신 버전](https://github.com/setfn/setfn-space-desktop/releases/latest)
- [모든 버전](https://github.com/setfn/setfn-space-desktop/releases)

릴리스에 첨부된 `setfn-space_{버전}_windows_x64-setup.exe`를 받아 실행합니다.

## 파일 확인

- 설치 파일은 코드 서명되어 있습니다. 파일 속성 > 디지털 서명에서 서명자를 확인할 수 있습니다.
- 릴리스마다 첨부된 `SHA256SUMS`에 파일별 SHA-256이 있습니다. 받은 파일의 값은 PowerShell에서 이렇게 봅니다.

  ```powershell
  Get-FileHash .\setfn-space_{버전}_windows_x64-setup.exe -Algorithm SHA256
  ```

## 문의

https://setfn.com/
