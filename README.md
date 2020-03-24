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
* 未収載トゥートをタグタイムラインに載せる。　
  【[v2.9.2.18#costom](https://github.com/lucida3rd/mastodon/commit/585723f69d4724ca65813e784883a382ea4ab39c)】
* ドメインブロック画面で「メディアファイルを拒否」表示を復活させた。　
  【[v2.9.3.5#costom](https://github.com/lucida3rd/mastodon/commit/2884d927058e088dfee4c874997019497e921833)】
* about/more にドメインブロック一覧を表示するのをやめて、別ページにした。　
  【[v3.0.0.1#costom](https://github.com/lucida3rd/mastodon/commit/ce59361bf7c9cff7ae130f52d403c4b0d0459504)】
* about/moreにドメインブロック一覧のリンクを出すようにした。　
  【[v3.0.0.2#costom](https://github.com/lucida3rd/mastodon/commit/d4575fc2abf4e89a04d51597ba72f1e82ea7e803)】
* タイムラインのトゥートに公開範囲をつけた。　
  【[v3.0.1.8#costom](https://github.com/lucida3rd/mastodon/commit/d94ae6762f2844abcaa7861e977de0e68c06f28c)】
* ブラウザによってはタイムラインのトゥート公開範囲をクリックするとエラーになるのに対応した。　
  【[v3.0.1.9#costom](https://github.com/lucida3rd/mastodon/commit/e08c3b7be6da584dab725c9d7dd48167e2003bb1)】
* cld3を使わないよう対応。(再対応)　
  【[v3.1.2.2#costom](https://github.com/lucida3rd/mastodon/commit/b1c594199b64b617e58c4c8b02b173538dafa738)】
* 鍵付きアカウントを[L]で表示するようにした。　
  【[v3.1.1.1#costom](https://github.com/lucida3rd/mastodon/commit/41664b1946cc8de8d76745ee9c9cd6e8fed5fa92)】
* 時限ミュート機能の実装。　
  【[v3.1.2.3t#costom](https://github.com/lucida3rd/mastodon/commit/d6445ab89c05d5ef4632c06458046de75cc5cd6f)】



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
**※以下、本家Readme.mdより抜粋**  
  
* Copyright (C) 2016-2019 Eugen Rochko & other Mastodon contributors (see AUTHORS.md)  
* This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.  
* This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Affero General Public License for more details.  
* You should have received a copy of the GNU Affero General Public License along with this program. If not, see https://www.gnu.org/licenses/.  



<a id="iDisclaimer"></a>
## 免責事項
* 当ソースを使用したことによる不具合、損害について当方は責任を持ちません。全て自己責任でお願いします。
* 当ソースの仕様、不具合についての質問は受け付けません。自己解析、自己対応でお願いします。
* 使用の許諾、謝辞については不要です。
