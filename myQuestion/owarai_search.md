# 2026-03-14
### ログイン機能についてsorceryとdeviseどちらを使うか
- sorceryはサポートが終了している
- deviseについて
```
deviseのメリット:
多機能で実装が早い
認証周りの機能が充実
ドキュメントが豊富
deviseのデメリット:
ブラックボックス化しやすく、内部の仕組みが理解しづらい
カスタマイズが複雑になりがち
面接で「認証の仕組みを説明してください」と聞かれた際に答えづらい可能性
```

# 2026-03-15
### 環境構築
- .github/workflows/ci.ymlのDB設定がmysqlになっていてテストが通らなかった
- config/database.ymlのファイルはdefault、development、testそれぞれの記載が必要だった