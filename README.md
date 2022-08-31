# vscode-git

vscode git을 사용하기 위한 저장소
- vscode 사용하기 시작.
- toshiba commit push test
- ssh-keygen -t ed25519 -C 메일주소@메일주소
- vim ~/.ssh/config 파일에 아래 내용 저장
Host *
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_ed25519

- ssh-add ~/.ssh/id_ed25519 실행해서 public키 생성
  ~/.ssh/id_ed25519.pub 파일의 내용을 github.com에 등록

