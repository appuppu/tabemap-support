# 地図コレ - サポートページ

地図コレアプリの利用規約とプライバシーポリシーを公開するためのGitHub Pagesプロジェクトです。

## 公開URL

https://appuppu.github.io/tabemap-support/

または

https://[your-username].github.io/tabemap-support/

## ファイル構成

- `index.html` - トップページ
- `terms.html` - 利用規約
- `privacy.html` - プライバシーポリシー
- `contact.html` - お問い合わせ（Google フォームへの案内）
- `en/` `es/` `zh-Hans/` `zh-Hant/` `ko/` - 上の4ページの各言語版（2026-10-03）。
  日本語版が正。規約・ポリシーを変えたら**全言語版も直す**。
  各ページ上部の言語切り替え（`<!--LANG-NAV-->`〜`<!--/LANG-NAV-->`）で行き来できる。
  直下の `index.html` は日本語以外のブラウザをその言語の版へ送る（アプリは表示言語の版を直接開く）

## GitHub Pagesの設定方法

1. GitHubに新しいリポジトリ `tabemap-support` を作成
2. ローカルでファイルをコミット:
   ```bash
   cd /Users/fukushimatakumi/develop/tabemap-support
   git add .
   git commit -m "Initial commit: Add legal documents"
   ```

3. GitHubリポジトリにプッシュ:
   ```bash
   git remote add origin https://github.com/[your-username]/tabemap-support.git
   git branch -M main
   git push -u origin main
   ```

4. GitHubのリポジトリ設定でGitHub Pagesを有効化:
   - Settings > Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

5. 数分後に `https://[your-username].github.io/tabemap-support/` でアクセス可能になります

## 更新方法

利用規約やプライバシーポリシーを更新する場合:

```bash
# ファイルを編集後
git add .
git commit -m "Update terms/privacy policy"
git push origin main
```

変更は自動的にGitHub Pagesに反映されます。

## ライセンス

© 2026 tabemap. All rights reserved.
