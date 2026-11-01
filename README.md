# 全国小学生バドミントン予選結果ポータル

全国小学生バドミントン選手権大会（およびABC大会等）の都道府県予選・地方ブロック予選の結果リンクをまとめたポータルページです。

- 公開ページ（GitHub Pages）: https://mugiodas.github.io/zenkoku-sho-badminton-yosen/
- 本体は `index.html` の単一ファイルです（HTML/CSS/JS完結）。
- 現在のリンクと更新日はサンプル（ダミー）データです。実データは `index.html` 内の `DATA` 配列を差し替えて更新します。

## 更新方法
1. `index.html` の `DATA` 配列で、対象の都道府県・ブロックのURL・更新日・ステータスを変更する
2. 変更をコミットして `main` ブランチへプッシュする
3. GitHub Pages に自動で反映される（通常1分程度）
