## Mastodon mynoghra.jp costom version, Readme
::Admin= Lucida（lucida3rd@mstdn.mynoghra.jp）  
::Server= [mynoghra.jp](https://mstdn.mynoghra.jp/)  
::github= [https://github.com/lucida3rd/mastodon](https://github.com/lucida3rd/mastodon)  
::Fork Source= [https://github.com/tootsuite/mastodon](https://github.com/tootsuite/mastodon)  
  
![Mastodon](https://media.mynoghra.jp/mstdn-backet/web_pocket/mynoghra_mastodon_bnr.jpg)



## このMastodonリポジトリについて
このリポジトリはMastodonの [本家ソースコード](https://github.com/tootsuite/mastodon) をForkしたものです。  
ソースコードはカスタマイズし、Mastodonサーバのひとつ「[Mynoghra.jp](https://mstdn.mynoghra.jp/)」にて運用しています。  
  
ソースコードの再利用、免責事項については下記をご参照ください。  
* [ライセンス](#iLicence)
* [免責事項](#iDisclaimer)
* [本家Readme](https://github.com/tootsuite/mastodon/blob/master/README.md)



## カスタム内容
Branchは以下の通りです。下以外はFork当時のままで未使用です。  
* master  
  本家の最新のリリースバージョンに追従してます。コードのカスタムはしてません。  
* newbranch  
  本家のmaster追従＋カスタムコード、Mynoghra.jpで運用しているブランチです。  
  無計画でmergeをおこなってます。  

Mynoghra.jp用にカスタムした内容は次の通りです。

* バージョン表示をリポジトリに合わせた。　
  【[v2.9.2.1#costom](https://github.com/lucida3rd/mastodon/commit/8c049e58150985eb8fe748cd17e0b35913a8a863)】
* プロフィールの文字数を増やした。 500文字→1200文字　
  【[v2.9.2.1#costom](https://github.com/lucida3rd/mastodon/commit/8c049e58150985eb8fe748cd17e0b35913a8a863)】
* プロフィールの項目数を増やした。 4つ→10つ　
  【[v2.9.2.2#costom](https://github.com/lucida3rd/mastodon/commit/dd38301fe5843a0bfb8a1a1a338e8dbb61b526a7)】
* 固定トゥート数の上限を増やした。 5個→12個　
  【[v2.9.2.3#costom](https://github.com/lucida3rd/mastodon/commit/9bb99b66eb8a98c3870440b10fb72c1979ce7eae)】
* aboutページにサーバ接続数を表示するようにした。　
  【[v2.9.2.12#costom](https://github.com/lucida3rd/mastodon/commit/5b4508b74d12afc1da9eb8ba43056e11451cfa34)】
* フィルター時、タイムラインに"フィルターされました"を表示しないようにした。　
  【[v2.9.2.5#costom](https://github.com/lucida3rd/mastodon/commit/a7ea0307724f02bf5789b583b557cc72b5742536)】
* 役割り名の変更。（★Forkする際に変えたほうがいいです。たぶん。）　
  【[v2.9.2.6#costom](https://github.com/lucida3rd/mastodon/commit/f0385d123f34d2e931557d5300cd1c9573dacff4)】
* 語尾伸ばしを直した。（ユーザ、サーバ）　
  【[v2.9.2.7#costom](https://github.com/lucida3rd/mastodon/commit/ef64fbec2a14a98983dc1b1efe55e6dc57e3e93b)】
* ヒーローイメージの推奨サイズ表示を実際に合うサイズを示すようになおした。過去に使用したファイル名を使わないように促した。　
  【[v2.9.2.8#costom](https://github.com/lucida3rd/mastodon/commit/8c5ec0e861a5610d7925b596e6182d58cf9a827e)】
* リスト名の後ろに + がついているとき、自分のトゥートがリストに入るようにした。　
  【[v2.9.2.9#costom](https://github.com/lucida3rd/mastodon/commit/d0c9d2340d271c436d8eec2eb9b07baf955999c2)】
* 固定トゥート数の上限　5個→12個
* aboutページにサーバ接続数を表示した。
* 語尾伸ばしを直した。（ユーザ、サーバ）
* フィルター時、タイムラインに"フィルターされました"を表示しないようにした。
* 役割り名の変更。（★Forkする際に変えたほうがいいです。たぶん。）
* ロール「bot」に対するCSS追加。
* メニューの位置をかえた。
* 表メニューの位置をかえた。
* ヒーローイメージの推奨サイズ表示を実際に合うサイズを示すようになおした。
* 過去に使用したファイル名を使わないように促した。
* プロファイル絵文字挿入機能の追加。（best-friends対応）
* アバター絵文字のキャッシュクリア変更。（best-friends対応）
* 自動サジェスチョンの改良。



<a id="iWhatsMastodon"></a>
## 「Mastodon」とは？
Mastodonは、ActivityPubをベースにした無料のオープンソースのソーシャルネットワークサーバーです。  
* 友達をフォローして新しい友達を見つけましょう。
* リンク、写真、テキスト、ビデオなど、必要なものをすべて公開します。
* Mastodonのすべてのサーバーは、連合ネットワークとして相互運用可能です。  
  つまり、あるサーバー上のユーザーは、別のサーバーからのユーザーとシームレスに通信できます。  
  これには、ActivityPubも実装しているMastodon以外のソフトウェアも含まれています。  



<a id="iLicence"></a>
## ライセンス
このソースコードはGUNフリーソフトライセンスで保証されています。  
再配布の条件については、Fork元であるMastodon本家のルールに帰属します。  
**※以下、本家Readme.md直訳**  
  
* Copyright（C）2016-2019 Eugen Rochkoおよびその他のMastodon貢献者。  
  （[AUTHORS.md]（AUTHORS.md）参照）
* このプログラムはフリーソフトウェアです。フリーソフトウェア財団によって公開されているGNU Affero一般公衆利用許諾契約書のバージョン3、または（あなたの選択により）それ以降のバージョンのいずれかに従って再配布または修正できます。  
* このプログラムは役に立つことを願って配布されていますが、いかなる保証もありません。 商品性や特定の目的への適合性についての暗黙の保証すらありません。 詳細については、GNU Affero General Public Licenseを参照してください。  
* このプログラムと一緒にGNU Affero General Public Licenseのコピーを受け取っているはずです。 そうでない場合は、<https://www.gnu.org/licenses />を参照してください。  



<a id="iDisclaimer"></a>
## 免責事項
* 当ソースを使用したことによる不具合、損害について当方は責任を持ちません。全て自己責任でお願いします。
* 当ソースの仕様、不具合についての質問は受け付けません。自己解析、自己対応でお願いします。
* 使用の許諾、謝辞については不要です。


[![GitHub release](https://img.shields.io/github/release/tootsuite/mastodon.svg)][releases]
[![Build Status](https://img.shields.io/circleci/project/github/tootsuite/mastodon.svg)][circleci]
[![Code Climate](https://img.shields.io/codeclimate/maintainability/tootsuite/mastodon.svg)][code_climate]
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/mastodon/localized.svg)][crowdin]
[![Docker Pulls](https://img.shields.io/docker/pulls/tootsuite/mastodon.svg)][docker]

[releases]: https://github.com/tootsuite/mastodon/releases
[circleci]: https://circleci.com/gh/tootsuite/mastodon
[code_climate]: https://codeclimate.com/github/tootsuite/mastodon
[crowdin]: https://crowdin.com/project/mastodon
[docker]: https://hub.docker.com/r/tootsuite/mastodon/

