# simple-quiz-setting

simple-quizの設定を担当するリポジトリ。

## Nginxのインストール

```bash
sudo apt install nginx

sudo systemctl enable nginx
```

## ポート管理

| ポート | プログラム |
| ---- | ---- |
| 80 | Nginx |
| 443 | Nginx(tls) |
| 8181 | api-server |
| 7878 | ws-server |
