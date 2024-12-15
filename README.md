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

## 各人サーバー割り当て

1. melanmeg, 52.198.45.15, 192.168.0.11
2. megumish, 18.180.233.35, 192.168.0.12
3. nwiizo, 54.250.48.240, 192.168.0.13

- 計測サーバー, 18.178.0.235, 192.168.0.179

- test
