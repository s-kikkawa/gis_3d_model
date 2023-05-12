# 概要
3D都市モデル（Project PLATEAU）のGMLファイルをB3DM に変換したものです。  
出典：国土交通省ホームページ（ https://www.mlit.go.jp/plateau/ ）

# 変換手順
変換は以下の手順で実施しました。
1. Project PLATEAUの手順に従いGMLからglbを作成  
（ https://project-plateau.github.io/PLATEAU-SDK-for-Unity/ ）
1. 3d-tiles-tools を使用してglbからB3DMに変換  
コマンド例）
```
npm install --save-dev 3d-tiles-tools
npx 3d-tiles-tools glbToB3dm -i input/564037_dem_6697_00_op.glb -o output/564037_dem_6697_00_op.b3dm
```

# ライセンス
Project PLATEAU のライセンスに従ってください。
（ https://www.mlit.go.jp/plateau/site-policy/ ）
