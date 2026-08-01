# ミックス・リファレンス

自分の曲をミックスするときに参照するドキュメント。

## 公開サイト

mainブランチにpushすると GitHub Actions が自動でビルドし、GitHub Pages に公開される。

## ローカルでプレビュー

```bash
pip install -r requirements.txt
mkdocs serve
```

http://127.0.0.1:8000 で確認できる。

## 編集

`docs/` 以下のmdファイルを直接編集する。ナビゲーションの順序は `mkdocs.yml` の `nav:` で管理。
