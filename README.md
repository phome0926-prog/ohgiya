# 扇屋 法面提案アプリ v0（骨格）

## 公開
扇屋のGitHubアカウントでリポジトリを作り、このフォルダの中身を上げて GitHub Pages を有効化。iPadのSafariで開き「ホーム画面に追加」。

## 写真の入れ方（ファイル名を合わせて置くだけ）
- 工法：img/koho/<工法ID>.jpg （seed, kyakudo, kiban, mortar, kanni, fukitsuke-waku, nail, anchor, ropenet, pocket, saku, heavy, jet, chem, monorail）
- 実績：img/cases/<事例ID>.jpg（case3〜case8, tejikara, higashikuwabara, mitsuikitamachi, ichinomiya, iwasaka, saam, iwado, gujo, seki, toki）

## 中身の書き換え
index.html 内の「データ」ブロック（FAMILIES / K / CASES）と、アドバイザーの judge() の分岐。
check:true の工法は「技術確認待ち」タグが出る。扇屋の技術者が確認したら false にする。

## 更新したら
sw.js 先頭の V を ohgiya-v1 のように上げる（iPadに古い版が残らないように）。
