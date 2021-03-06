# Repのパブリックリポジトリ

![Rep](https://user-images.githubusercontent.com/15076603/43436692-80f43430-94c0-11e8-8931-1b819a093065.png)

このリポジトリは[Rep](https://www.rep-riiyko.com)の公開できる部分をさらけ出したリポジトリです。  
あくまでプログラミングの勉強やRailsでの開発の **参考** 程度に利用してください。  

2018/07/31の段階でのコードであり、更新はあまりしません。  

# プログラミングの勉強をしている方へ

- まずは[Rep](https://www.rep-riiyko.com)を見てみてください
- 気になる機能がありますか？ `config/routes.rb` を見て、その機能のURLはどのcontrollerか把握しましょう
- 該当controllerの該当アクション内を理解しましょう。わからないメソッドがあればgrepや全文検索で定義元を見つけましょう。
- 該当viewを見ましょう。
- 以上の繰り返しである機能の一連の流れがわかると思います。

### そのままcloneしても正常に動きません

- PDF生成機能が動かない（ライブラリが必要です。）
- 授業データが不足（全授業データは搭載していません。）

# いくつかの重要なこと

- dev環境ではletter_opener_webを利用しており、立教アドレスを持っていない方でも登録/ログインできます。
- 授業データはseed_fuというgemを利用してインポートしています。 `db/fixtures/` の 中に授業データの一部が入っています。
- このコードは私の初めてのwebサービスです。拙いところもあるので、完全な信頼はしないようにしましょう。

# MIT

Repで重要なのは、今まで築いた立教大学生に対する知名度と、シラバス検索を支える2万を超える授業データ、そして何より大切なのは立教生によって入力された授業のレビューです。  
そのため、それらが含まれないソフトウェア部分はMITライセンスで公開します。

Copyright (c) 2018 Kento Sugita  
Released under the MIT license（＊）  
https://opensource.org/licenses/mit-license.php  

＊このリポジトリ内の画像（png, jpeg, jpg, ico形式のファイル）は個人目的・商用目的共に利用禁止。

# さいごに

> この芝居がお気に召したのなら、どうか拍手喝采を

Starをいただけると嬉しいです☺️
