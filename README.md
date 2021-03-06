experimental_cp
================
国土地理院ベクトルタイル提供実験（基準点）
# 基準点の GeoJSON タイル
基準点の配点図（日本全国）をズームレベル 7～12の GeoJSON タイルに変換したものを提供実験
いたします。データの仕様は次のとおりです。

## 基準点
テンプレート URL: http://cyberjapandata.gsi.go.jp/xyz/cp/{z}/{x}/{y}.geojson

サンプル：http://cyberjapandata.gsi.go.jp/xyz/cp/12/3638/1612.geojson

ベクトルタイルスタイル定義：http://cyberjapandata.gsi.go.jp/xyz/cp/style.js

# データについて
データに含まれる基準点の種類は以下の通りです。


ズームレベル 7：

電子基準点



ズームレベル 8：

電子基準点、経緯度原点、水準原点、一等三角点


ズームレベル 9：

電子基準点、経緯度原点、水準原点、一等三角点


ズームレベル 10：

電子基準点、経緯度原点、水準原点、一等三角点


ズームレベル 11：

電子基準点、経緯度原点、水準原点、一等三角点


ズームレベル 12：

電子基準点、経緯度原点、水準原点、一等三角点、
二等三角点、三等三角点、四等三角点、基準水準点、
一等水準点、二等水準点、道路水準点、準基準水準点、
交点


データは毎週更新予定です。

# デモサイト
地理院地図
http://maps.gsi.go.jp/?ll=38.27727,140.712204&z=12&base=std&ls=controlpoint&vs=c0j0l0u0

github
http://gsi-cyberjapan.github.io/experimental_cp/


# 提供の位置づけ
国土地理院ベクトルタイル提供実験におけるデータの提供の位置づけは次のとおりです。
- 本提供実験は、ベクトルタイル提供における技術的・施策的課題を国土地理院が把握するとともに、外部からの技術的な提案を受け取り、外部との技術的な議論を通じてベクトルタイルの適切な提供方法を研究開発することを目的とするものです。
- 本提供実験の期間は、2014年8月1日から本提供実験終了までとなります。
- 本提供実験は、予告なく内容変更したり提供停止したりする場合があります。
- 本提供実験のベクトルタイルは基本測量成果と位置付けているものではありませんが、基本測量成果としての提供を検討するにあたって、提供を行うものです。
- 本提供実験の利用により生じた損失及び損害等について、国土地理院はいかなる責任も負わないものとします。

# 履歴
2015-03-25 基準点の提供実験を開始
