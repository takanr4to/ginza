# 引継ぎ資料｜ALIGNMENT BODY

## 現在の状況

GitHub Pages にて公開中。

URL：
https://takanr4to.github.io/ginza/

---

# 現状課題

## 1. サイト密度不足

現在かなり余白が多く、
情報量不足に見える。

改善必要。

---

## 2. 店舗写真の弱さ

実写真が生活感寄り。

対策：
- 加工
- トリミング
- 高級感オーバーレイ
- 光素材
- ガラスUI

で補強する。

---

## 3. 高級感不足

白系のみで締まり不足。

対策：
- チャコールグレー
- ガラスUI
- 影
- 奥行き
- ブラー

を追加。

---

# 素材方針

## 有効素材

- 水面反射
- 光ライン
- 白銀背景
- ガラス板

## 注意

キラ粒系は使いすぎ禁止。

---

# コピー方向性

## NG

- 癒し全面
- 女性向け感
- エステ感

## OK

- 技術
- 身体理解
- 可動
- 重心
- 筋肉
- 調整
- 観察

---

# UI方針

高級SPA × Apple UI × 医療感

---

# 実装優先順位

1. TOP改善
2. 固定LINE/TEL
3. ガラスUI導入
4. スクロール演出
5. メニュー再構築
6. 写真配置改善
7. パララックス
8. アニメーション追加

---

# 注意事項

## 必須

- スマホ最優先
- 動きすぎ禁止
- 軽量維持
- 白飛び禁止
- 安っぽいエフェクト禁止

---

# GitHub運用

Repository:
https://github.com/takanr4to/ginza

Default branch:
main

Published URL:
https://takanr4to.github.io/ginza/

画像は img フォルダ。

相対パスで指定。

例：

./img/sample.webp

---

# 今後

このファイルは、
会話内容・設計・修正内容を継続追記し、
常に最新状態を維持すること。



# 追加引継ぎ情報

## 現在のファイル構成

/
├── index.html
├── img/
├── PROJECT_SPEC.md
├── HANDOVER.md
└── TODO.md

現状は単体LP構成。CSSとJSは index.html 内に直接記述。

---

## 使用技術

- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages

Reactは未使用。

---

## ローカル確認方法

VSCodeで開き、Live Serverで確認。

または以下。

python -m http.server 5500

http://localhost:5500

---

## 画像フォルダ説明

img/ には以下を入れる。

- 店内写真
- 施術写真
- 白銀背景素材
- 水面反射素材
- ガラスUI素材
- シルバーライン装飾
- 透過PNG装飾

店内写真と施術写真はそのまま使わず、CSSで明るさ・彩度・コントラスト・オーバーレイを調整して使う。

表示用の軽量画像は img/optimized/ を使用する。
元画像は img/ に残し、サイト表示では optimized 配下を優先参照する。

ロゴ原本は img/logo-alignment-body.jpg に保管。
サイト表示では img/optimized/logo-alignment-body.jpg を使用する。

---

## 主に編集すべきファイル

現状は index.html を主に編集。

将来的には以下へ分割推奨。

- index.html
- style.css
- script.js

---

## 直近の変更履歴

- 新ロゴを反映し、表示ブランド名を ALIGNMENT BODY に更新
- ヒーローと予約セクションにロゴを配置
- ロゴ画像を軽量化し、img/optimized/logo-alignment-body.jpg として追加
- 売上改善を目的に、LP全体を予約導線重視へ再構成
- TOPに施術写真を追加し、初見で整体サロンと分かる構成へ変更
- 表示用軽量画像を img/optimized/ に作成
- 主要背景画像を1MB超のPNGから軽量JPEGへ差し替え
- 下部画像に lazyload を追加
- LINE相談・LINE予約へのCTAを複数箇所に追加
- FLOW / FAQ を追加し、予約前の不安を減らす構成へ変更
- TOPセクションを全面改修
- ヒーローに技術訴求コピーを追加
- PC向け固定LINE/TEL導線を追加
- スマホ下部のTEL/LINE固定追従メニューを維持
- ヒーロー背景に白銀素材、水面反射、光ライン演出を追加
- 店舗写真をガラスUIパネル内に配置
- 店舗名を ALIGNMENT BODY に更新
- LINE予約リンク追加
- TEL追加
- Instagram追加
- 恵比寿アクセス追加
- スマホ下部に TEL / LINE 固定追従メニュー追加
- 高級感ある白銀・水面・ガラス系素材を追加
- 店内写真と施術写真をサイト素材として使用予定
- メニュー構成を技術訴求・完全個別対応寄りへ変更予定

---

## 完成判断基準

- スマホで見たときにTOPが高級整体サロンとして成立している
- LINE予約導線が明確
- TEL導線がスマホで分かりやすい
- 店内写真の生活感が抑えられている
- 技術力と個別対応が伝わる
- 普通の整体院っぽさがない
- 表示速度が重すぎない
- Lighthouse Performance 80点以上を目標
- スマホで文字が読みやすい
- 予約まで迷わない
