このサンプルデータは QGIS 2.16以上で正常に作動します

***利用手順************************************** 

注意：1)-3)はatlastool_sample.qgsを起動する前にやること

1) QGIS 2.16 を起動(まだプロジェクトファイルは開かない)

2) プラグイン→プラグインの管理とインストールを開き
TileLayer Pluginをインストールする

3) Web→タイルレイヤプラグイン→タイルレイヤを追加する→設定を開き
このディレクトリ内に格納されているtilelayer_infoを指定する

4) atlastool_sample.qgsを開く

5) プロジェクト→プリントコンポーザ→atlastestを開く

6) 地図帳→地図帳のプレビューをクリックする(アクティブにする)

7) 地図帳の出力を試す(地図帳→地図帳をイメージとして出力する、など)

****************************************************

このディレクトリ直下に格納されているファイルの概要

atlastool_sample.qgs:	帳票作成おためし用のQGISプロジェクトファイル
atlastool_sample.qpt:	帳票作成おためし用のQGISで利用するプリントコンポーザの状態が格納されたファイル
point_u54.shp.geojson:	帳票作成お試し用のポイントデータ

各ディレクトリ内に格納されているファイルの概要

output_sample:	出力サンプル画像(jpeg)が格納されている
pic:		帳票に挿入するためのサンプル画像が格納されている
tilelayer_info:	TileLayer Plugin用の設定ファイルが格納されている

ライセンスについて

当該ディレクトリ内のデータ全て:CC BY 4.0
https://creativecommons.org/licenses/by/4.0/legalcode

Yoshio MISHIMA

