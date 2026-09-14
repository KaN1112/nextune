# NexTune Download Site

NexTuneの公開用ダウンロードサイトです。GitHub Pagesでそのまま公開できます。

## 構成

```text
NexTune-download-site/
├─ index.html
├─ style.css
├─ script.js
└─ downloads/
   ├─ NexTune_1.0.0_x64-setup.exe
   └─ NexTune.exe
```

## GitHub Pagesで公開する

1. このフォルダの中身をGitHubリポジトリにアップロードします。
2. GitHubで `Settings` → `Pages` を開きます。
3. `Build and deployment` のSourceを `Deploy from a branch` にします。
4. Branchを `main`、フォルダを `/(root)` にして保存します。
5. 数分後、表示されたURLからサイトを確認できます。

## ダウンロードファイルを更新する場合

新しいexeを `downloads` に配置し、`index.html` 内の以下のリンクを新しいファイル名へ変更してください。

- `downloads/NexTune_1.0.0_x64-setup.exe`
- `downloads/NexTune.exe`

## Credit

Created by KaN.  
inspired by VyLite.
