# research_shooter_agents

**検証活動のご参加の際には、このREADME.mdをよく読んだうえで行うようにお願いいたします。m( _ _ )m**

## PDⅢ検証用リポジトリ

このリポジトリは、PDⅢの研究で実装した、ゲームAIの有効性を確かめるため、実装したゲームAIを対戦相手としたゲームのプレイと、対戦相手の様子をアンケート調査を行うためのものです。このリポジトリでは、そのゲームデータとアンケートフォームのリンクが含まれます。

## 研究概要

テーマ名：「戦局認識型ゲームAIの実装」

本研究の目的は、試合形式のゲーム上で、機械学習を利用し、スコアから読み取れる対戦の優劣によって、一方的な試合を回避するように学習させ、プレイヤーとエージェントとの実力差を感じさせないゲーム体験を目指すことです。

## 検証方法

検証は以下の手順で行ってください。

1. 検証用アプリケーションのZipを[ダウンロード](#検証用アプリのダウンロード)
1. Zipを解凍し、ファイルの中にある、「ShooterAgents.exe」を起動(すぐにゲームが開始されます)。
1. [操作方法](#ゲームの操作方法)と[ゲームのルール](#ゲームの主なルール)に従って、何試合か(回数は任意)ゲームをプレイ。
1. アプリケーションを閉じて、[アンケートフォーム](#アンケートフォーム)に解答を入力。

## ゲームについて

本研究で作成したゲームは対戦型のシューティングゲームです。以下は、ゲームの内容を説明します。

### ゲームの操作方法

このゲームは主にキーボードで操作します。

キャラクター操作方法は以下の通りです。

- 移動：  WASDキーで、前後左右に移動
- 回転：  JとLキーで左右に回転
- 弾丸発射：  spaceキーで弾丸をキャラクターの前方に発射(長押しすると連続して発射可能)

![alt](./imgs/character_moving.png)

### ゲームの主なルール

検証用のゲームの主なルールは以下の通りです。

- 両者とも、前後左右の移動と、左右の回転ができる。
- 弾丸はキャラクターの前方に発射できるが、弾丸発射後0.5秒間は次の弾丸を発射できない。
- 弾丸を相手にヒットさせることで、相手にダメージを与えることができる。
- 相手のHPを先に0にすることで得点できる。(得点時には、初期位置に戻される)
- 先に5得点先取で勝利(得点と位置がリセットされ、再度ゲームがスタートする)

## ゲーム画面の説明

![img](./imgs/game_image.png)

## 検証用アプリのダウンロード

以下のリンクから、検証用アプリケーションをダウンロードしてください。

[ダウンロードリンク(testAppData.zip)](https://github.com/KenjiIsAEiji/research_shooter_agents/releases/download/v0.1-pre-release/testAppData.zip)

(Zip状態で約29MB、解凍後は約73.8MB）

このGitHubの[Releases](https://github.com/KenjiIsAEiji/research_shooter_agents/releases)から、Assetsのプルダウンの中にある「testAppData.zip」でもダウンロードできます。

ゲームは、**Windows10搭載のパソコンで実行可能です**。**MacOSには対応しておりませんのでご注意ください**。
(なお、Windows10搭載のノートパソコンで動作が可能であることを確認しました。)

解凍したフォルダの中の、「ShooterAgents.exe」を実行すると、ゲームが起動し、ロゴマークが表示されたのちに、すぐにゲームがスタートします。

ゲームは小さなウィンドウで起動するため、必要に応じてウィンドウの大きさを変更してください。

ある程度プレイした後は、ウィンドウ右上の×ボタンで終了してください。

もし、途中で不具合が発生し、検証ができなくなってしまった際には、ご連絡ください。

## アンケートフォーム

ゲームをプレイした後は、ゲーム全般やプレイ中の対戦相手に関するアンケート調査にご協力お願いします。

以下のGoogleフォームのリンクにアクセスし、アンケートの解答を入力してください。

[アンケートフォーム(Google forms)](https://forms.gle/F6FR5tVW24SATp928)

このアンケートで得た情報は、PDⅢの研究による検証や論文のみ使用されますので、予めご了承ください。

また、このアンケートフォームは**2021年12月23日までで、以降はアクセスが出来なくなります**のでご注意ください。

## リリースノート

- 2021/12/21：本文章作成

## 作成情報

- 作成者: 宮澤瑛至
- 所属：鷹合研究室
- E-mail：b1800722@planet.kanazawa-it.ac.jp
