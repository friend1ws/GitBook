# 一塩基変異、欠失・挿入の検出

記載するべきポイント

* pileup formatの説明？
* 変異検出の原理
  * 縦に見て塩基数を数えて検出するということ
  * germlineではないということ、シークエンスエラーではないことの２点を証明する必要があること
  * Fisher検定に基づく方法
  * 他の方法論\(例えばmutectなど）についても少し説明
* IGVの利用法
* post-processing \(filteringについて）
  * strand bias
  * 周辺
  * indelによるエラー
  * simple repeatなど、repeatまわりのエラー
  * oxoG
  * non-matched controlを利用して、偽陽性を除去する方法
* 実践的なフィルタリング方法（実際のデータで、どういったところに注意して、パラメータのチューニングをしていくかについて）



