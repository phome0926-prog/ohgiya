# 扇屋 法面提案アプリ v0（骨格）

## 公開
phome0926-prog/ohgiya（GitHub Pages）で公開。このフォルダの中身をリポジトリ直下に上げる。iPadのSafariで開き「ホーム画面に追加」。

## 写真の入れ方（ファイル名を合わせて置くだけ）
- 工法：img/koho/<工法ID>.jpg （seed, kyakudo, kiban, mortar, kanni, fukitsuke-waku, nail, anchor, ropenet, pocket, saku, heavy, jet, chem, monorail）
- 実績：img/cases/<事例ID>.jpg（case3〜case8, tejikara, higashikuwabara, mitsuikitamachi, ichinomiya, iwasaka, saam, iwado, gujo, seki, toki）

## 中身の書き換え
index.html 内の「データ」ブロック（FAMILIES / K / CASES）と、アドバイザーの judge() の分岐。
check:true の工法は「技術確認待ち」タグが出る。扇屋の技術者が確認したら false にする。

## 更新したら
sw.js 先頭の V を ohgiya-v1 のように上げる（iPadに古い版が残らないように）。

## 写真の出どころ
- 工法写真のうち吹付・法枠・種子吹付・枠内植生・ロックボルト・アンカー・モノレールと、トップ・チーム写真・マスコットは、2022年のHP制作素材（写真フォルダ）から img/hp/ に取り込んだ。
- 残りの工法写真（モルタル吹付、法枠、種子吹付、植生マット、ロープネット、ニューレスプ、ロックボルト・アンカー、モノレール、地盤改良）のうち、HP制作素材にないもの（植生マット・ロープネット・ニューレスプ・地盤改良・アンカーの一部）は扇屋HP（ohgiya.link）からダウンロードして img/site/ に同梱した（HPの画像を消してもアプリ側は影響を受けない）。HP側でWebP配信されていたもの（植生マット・ロープネット・ニューレスプ・地盤改良）はJPEGに変換してある。
- 事例写真は検討書・技術検討会資料などから抜き出して img/cases/ に置いた。
- EPMとDKドレーンパイプの写真はメーカー資料から（画面に出典を表示）。
