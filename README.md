# ISUCON14 Revenge
予選用リポジトリ

## 初期設定
- SSH後に実行
```bash
$ ssh-keygen -t ed25519 -C "" -f ~/.ssh/id_ed25519 -N "" && \
  sudo apt update -y && \
  git clone https://github.com/melanmeg/isucon14_revenge.git /tmp/isucon14_revenge && \
  mv /home/isucon/webapp /home/isucon/webapp.bk && \
  mv /tmp/isucon14_revenge/{*,.gitignore,.github,.git} /home/isucon/ && \
  rm -rf /tmp/isucon14_revenge
```
