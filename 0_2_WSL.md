윈도우에서 WSL을 설치하는 가장 간단한 방법은 다음과 같다:

1. 관리자 권한으로 PowerShell을 실행한다.

2. 다음 명령어를 입력한다:

```powershell
wsl --install
```

3. 설치가 완료되면 컴퓨터를 재시작한다.

4. 재시작 후 Ubuntu가 자동으로 실행되며, 사용자 이름과 비밀번호를 설정하면 설치가 완료된다.

이 방법은 WSL 2와 Ubuntu를 기본으로 설치한다. 설치 후 WSL을 통해 Windows에서 Linux 환경을 사용할 수 있다.

또는 설치 후 다음 명령으로 실행 할 수 있다.

```powershell
wsl.exe -d Ubuntu
```
