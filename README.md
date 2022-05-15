## mac os git setting
1. homebrew 설치하기
> - [Homebrew 설치 홈페이지](https://brew.sh/)
> - Homebrew 설치 홈페이지 내에 설치 코드 복사
> ```
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
> ```
> - command+space 눌러서 'terminal.app' 열기
> - 복사한 코드 붙여넣은 후 Enter 누르기
> - ``` brew help ``` 코드 입력 후 Enter 누르기
> - 만약에 ```zsh: command not found: brew``` 코드가 나온다면 오류 해결 필요
> > #### zsh: command not found: brew 해결 방법
> > - xcode-select 설치 필요
> > - terminal.app 새로 열기
> > - ```xcode-select --install``` 입력하여 설치(시간 소요됨.) 거의 마지막에 ```==> Installation successful!``` 코드가 나타남
> > - ``` brew help ``` 코드 입력 후 Enter 눌러서 잘 설치되었는 지 확인
> > - [오류해결 참고 영상자료](https://www.youtube.com/watch?v=1oolnK1g6jw)

2. git 설치하기
> - ```brew install git``` 입력하여 git 설치
> - ``git --version``` 입력하여 버전 git 버전확인, 버전이 잘 나온다면 잘 설치
