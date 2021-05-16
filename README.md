### 프로그래밍 격언
---
![Screen Shot 2021-05-16 at 3.20.18 PM](static/src/Screen%20Shot%202021-05-16%20at%203.20.18%20PM.png)

- 개발을 하면서 느낀점이나, 책을 읽으면서 좋은 구절을 기록해 놓는 저장소입니다.
- `fortune` 명령어를 쉘에 설정해 놓으면 터미널이 실행될 때마다 구절을 확인할 수 있습니다.

### 설정
---

우선 `fortune` 및 `cowsay` 를 다운로드 합니다.

```
brew install fortune
brew install cowsay
```

그리고 나서, 사용하고 있는 쉘 설정파일에 들어 갑니다. 제가 사용하는 쉘은 `zsh` 이므로 `zsh` 설정 파일에 들어가면 됩니다.

```
vim ~/.zshrc

fortune ~/my-fortune | cowsay
```

쉘 설정 파일 마지막에, 위의 명령어를 저장하면 끝입니다.

### 기록하는 방법

원하는 구절을 입력한 후에 아래 명령어를 입력하면 끝입니다.

```
strfile {*}.fortune
```
