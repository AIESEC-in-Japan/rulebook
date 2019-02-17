# アカウント名・グループ名命名規則
################################
:Date: 2017-03-27
:Authors: - genta.mochizawa
:URL: https://gist.github.com/mc-is/c2dc870ed8e2a72555d6800dadd13168
:Updated: |date| at |time|
.. |date| date::
.. |time| date:: %H:%M
.. contents::

 この命名規則はMCISが修正・向上させることができる．また，すべてのメンバーが改善の
提案をコメントすることができる．
 アカウント名
============
 個人としてのアカウント
----------------------
 - {givenName}.{familyName}@aiesec.jp
- 小文字アルファベットを使用する．
- “.” を区切り文字として使用する．
- 名前と苗字をこの順に繋げたものとする．
  ただし，アカウント名の重複があった場合，苗字を先に名前を後に繋げる．
- これ以降の重複は苗字の後に連番を入れる．
 組織としてのアカウント
----------------------
- {組織区分名}.{役割}@aiesec.jp - 小文字アルファベットを使用する．
- “.” を区切り文字として使用する．
- 代表する組織の区分を接頭辞として用途や役割を追加する．
- 外部とのコミュニケーション用には組織区分の名前を適切にローマ字で表現したものを
  使用することができる．
 外部用LC名
~~~~~~~~~~
LC名はこの `リスト <http://resources.aiesec.jp/lcname>`_ に従う::
    ag: aoyama
    apu: apu
    ch: chuo
    do: doshisha
    hd: hokkaido
    hi: hitostubashi
    hu: hiroshima
    jo: sophia
    kb: kobe
    kg: kwansei
    ko: keio
    kt: kyoto
    mj: meiji
    na: nagoya
    ni: nagoya-city
    nz: nanzan
    oi: osaka-city
    os: osaka
    sd: sendai
    sfc: sfc
    sg: shiga
    sp: rikkyo
    tkb: tsukuba
    to: tokyo
    wa: waseda
 例
~~
 #. | 苗字: Tanaka 名前: Taro の個人アカウント
   |   標準アドレス → taro.tanaka@aiesec.jp
   |   1人目の重複 → tanaka.taro@aiesec.jp
   |   2人目以降の重複 → taro.tanaka1@aiesec.jp, taro.tanaka2@aiesec.jp, …
 #. | SFCの管理者アカウント
   | → fc.admin@aiesec.jp
 #. | JOの外部コミュニケーション用
   | → shophia@aiesec.jp
 グループ名
==========
 -  小文字アルファベットを使用する．
-  アンダースコア(``_``)を区切り文字として使用する．
-  グループが使用される組織区分を接頭辞とし，それ以外を利用する場合は mc_is_com
   へ申請を行う必要がある
    - ただし組織外部とのコミュニケーション用には組織区分の名前を適切にローマ字で
     表現したものを使用することができる．
 -  ``aj_``, ``mc_``, ``nc_`` を接頭辞とする名前はMCのみが作成することができる．
 例::
     LC: SFC Area: OGX での情報共有グループ
    → sfc_ogx@aiesec.jp
 サブドメイン名
==============
 - LCは，{`外部用LC名`_}.aiesec.jp と，そのサブドメインを申請し利用することができる
- 3語以上の言葉は，ハイフン(``-``)で区切る
- 上位ドメイン名の中で意味が重複する単語を，サブドメインに利用することはできない
   - 例: aiesec-japan-sp.rikkyo.aiesec.jp は aiesec, japan, spが重複している
 - コンテンツを説明する単語のみを利用し，HP, LPのようなメタな単語は，避ける．
- 内部用語は避ける (MarCo広報物使用許可の基準に準じる)
 .. note:: 1516のMarCo地区M開催時に練習のため，lp.{lc}.aiesec.jp というサブドメイン
          が全LC分登録されているが，これは命名規則に合わないものであり参考には
          しないこと．そのまま公開してしまっているページが複数存在するため，
          停止はしないが，今後新たな登録は行わない．
