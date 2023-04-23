# 目次

- [目次](#目次)
  - [更新履歴](#更新履歴)
  - [このツールの目的](#このツールの目的)
  - [前提条件](#前提条件)
  - [導入の前に](#導入の前に)
  - [導入方法](#導入方法)
  - [使わせていただいたもの](#使わせていただいたもの)
  - [参考にさせていただいたもの](#参考にさせていただいたもの)
  - [連絡先](#連絡先)
  - [注意事項](#注意事項)
  - [ライセンス情報](#ライセンス情報)

## 更新履歴

- 2022/12/03 ver1.0.0 配布

- 2022/3/26 ver2.0.0 作成
  - 設定用スクリプト作成

- 2023/04/09 ver3.0.1作成
  - 変更が多岐に渡るため以下に概要を記載
    - 設定用スクリプト作成
      - 設定をアバターごとに保持するように
      - ONOFFアニメーションを自動生成するように
      - ボタンごとの設定を視覚的にわかりやすくするように
    - 説明書を削除
    - このツールの目的などを削除

- 2023/04/09 ver3.0.2作成
  - 指輪のデフォルト位置を左手薬指に変更

- 2023/04/21 ver3.0.3作成
  - 左手人差し指にセットするように明記
  - audioSourceのloading backGroundをONに設定
  - クールタイムを微調整
    - ボタンは0.5秒、サブメニューは1.0秒、ロングクールタイムは5.0秒

- 2023/04/23 ver3.1.0作成
  - 同期ズレ回避のため初期表示にアニメーションを再生するように変更

## このツールの目的

UIsetはVRChatのcontact機能を利用したアニメーション補助ツールです

服の着せ替え、小物の取り出しなどを同梱のツールから設定することができます

同期ズレも対策済みなので次のようなギミックを簡単に実装することができます
   - フレンドからメニューを操作してもらって、小物の出し入れを行う
   - パートナーから衣装を選んでもらって着せ替えさせてもらう
   - ExpressionMenuで行っていたアニメーションをUIsetに移行する

※服の着せ替えを行う方は暴発にくれぐれもお気をつけてください！


## 前提条件

このツールは以下の 2 点の unityPackage の導入を前提としております

<a href="https://booth.pm/ja/items/3087170">lilToon</a>

<a href="https://modular-avatar.nadena.dev/ja/">ModularAvatar</a>

<b>よって最新版の unitypackage 版 VRCSDK を導入しているプロジェクト、もしくは VCC で立ち上げているプロジェクトでないとアバターアップロード時に ModularAvatar でエラーが出てしまいます</b>

基本的なアバターのアップロードができる方を対象としています

2023/4/9現在以下のバージョンでの動作を確認しています

liltoon_1.3.7

modular version1.4.5(LTS)


<img src="./img/VRCSDK.png" alt="SDKの画像">

<img src="./img/VCC.png" alt="VCCの画像">

## 導入の前に

UIsetで統合されるanimatorControllerはアバターをルートとして作成しています

自分で作ったアニメーションをセットされる方は気をつけてください

## 導入方法

1. 以下のリンクから lilToon と ModularAvatar をダウンロードしてプロジェクトにインポートしてください

   <a href="https://booth.pm/ja/items/3087170">lilToon</a>

   <a href="https://modular-avatar.nadena.dev/ja/`">ModularAvatar</a>

   <img src="./img/2-1_1.png" alt="liltonnとmodularAvatarをインポートしている画像">

2. UIset.v(バージョン番号).unityPackage をプロジェクトにインポートしてください

   <img src="./img/2-2_1.png" alt="UIsetをインポートしている画像">

3. 画面上部に表示されるUIsetからウィンドウを開き、手順に沿ってセットアップを行ってください

   <img src="./img/3-1_1.png" alt="UIsetをインポートしている画像">


4. 各ボタンに設置するテクスチャを作成したい場合は、付属のpsdファイルから編集してください

  <img src="./img/4-1_1.png" alt="UIsetをインポートしている画像">


## 使わせていただいたもの

- <a href="https://booth.pm/ja/items/1547585">満天星躑躅だよ様より【Unity】Parallax HUD Shader テクスチャ素材付き(ライセンス情報同梱済み)</a>
- <a href="https://booth.pm/ja/items/3087170">lilLab 様より lilToon </a>
- <a href="https://modular-avatar.nadena.dev/ja/">bd\_様より ModularAvatar </a>
- <a href="https://booth.pm/ja/items/2653422"> ないとまろうど様より Constraint 式ワールド固定ギミック</a>
- <a href='https://fonts.google.com/icons?selected=Material+Icons'>google Material Icons</a>
- <a href='https://soundeffect-lab.info/copyright/'>効果音ラボ 様より 効果音一式</a>

## 参考にさせていただいたもの

- <a href="https://booth.pm/ja/items/4393826">Harukaの実験室様より SimpleObjectSwitch</a>

- <a href="https://naos318.booth.pm/items/4114435">なおの電脳工作室 様より お砂糖同士で甘～いキスができるシステム -OAKS- </a>


## 連絡先

不明な点や不具合は下記の SNS までご連絡するか issue を上げてくださって大丈夫です

<a href='https://twitter.com/hakononaka0001'>hakoiri</a>image.png

## 注意事項

本ソフトウェアは hakoiri がその著作権を有しており、MIT ライセンスに基づいて提供します。

このソフトウェアは、自由に使用することができます。
このソフトウェアの著作権表示と、このライセンスの全文（英語の原文）を、ソースコードや、ソースコードに同梱したライセンス表示用の別ファイルなどに掲載してください。
このソフトウェアには保証はついていません。
このソフトウェアを利用したことで問題が起きた際に、ソフトウェアの製作者は一切の責任を負いません。

## ライセンス情報

MIT LICENCE
Copyright (c) 2022 hakoiri

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

MIT LICENCE
Copyright (c) 2019 Tsutsuji815
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<a href='https://github.com/google/material-design-icons/blob/master/LICENSE'>Apache License 2.0</a>

© 2013-2022 <a href='https://soundeffect-lab.info/copyright/'>効果音ラボ</a> All Rights Reserved

