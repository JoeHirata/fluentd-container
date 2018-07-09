
## ファイル修正後のDockerhubへのpush

```
## Githubへ反映
$ git add .
$ git commit -m "commit comment"
$ git push

## Git hub のwebhookにより自動でDockerhubへ反映されます
```

## 手動ビルドする場合(auto buildなので基本やらないと思いますが)

```
## DokcerHubへの反映
$ docker push xxjoexx/fluentd
```

