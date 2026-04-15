# TDR Guide

東京ディズニーリゾートに年1〜2回ほど訪れる遠方ゲスト向けの攻略情報サイトです。  
HTMLとCSSのみを用いて制作し、事前準備から当日の回り方、フード、グッズ、ホテル、便利アイテムまで、万人向けにわかりやすく整理して提供することを目的としています。

## 目的

本サイトは、東京ディズニーリゾートに頻繁には行かない遠方の来園者が、事前に必要な情報を把握し、当日をより快適に過ごせるようにすることを目的としています。  
特に、以下のような悩みを持つユーザーを想定しています。

- 何を準備すればよいかわからない
- 当日にどう動けばよいかわからない
- フード、グッズ、ホテルなどの優先順位が決めにくい
- 季節ごとの持ち物や服装の判断に迷う

## 想定ペルソナ

- 遠方在住
- 年に1〜2回ほど東京ディズニーリゾートに行く
- 年齢は限定せず、万人向け
- コアな知識よりも、まず基本的で必須な情報を知りたい人

## サイト構成

- `index.html`  
  サイト全体の概要とカテゴリ導線をまとめたトップページ

- `prepare.html`  
  事前準備、チケット、公式アプリ、持ち物、服装に関する情報

- `park-guide.html`  
  当日の回り方や優先順位、混雑をふまえた基本的な攻略情報

- `food.html`  
  食事の考え方、タイミング、休憩の取り方

- `goods.html`  
  グッズ購入やお土産選びに関する基本情報

- `hotel.html`  
  遠方ユーザー向けのホテル選び、前泊・後泊の考え方

- `items.html`  
  快適に過ごすための便利アイテム紹介ページ  
  将来的にアフィリエイト導線として拡張することを想定

## 使用技術

- HTML5
- CSS3
- Visual Studio Code
- Git / GitHub
- Live Server（ローカル確認用）

## フォルダ構成

```bash
tdr-guide/
├── index.html
├── prepare.html
├── park-guide.html
├── food.html
├── goods.html
├── hotel.html
├── items.html
├── assets/
│   ├── css/
│   │   ├── reset.css
│   │   ├── style.css
│   │   ├── components.css
│   │   └── responsive.css
│   ├── images/
│   │   ├── hero/
│   │   ├── sections/
│   │   └── icons/
│   └── favicon/
├── docs/
│   ├── figma-notes.md
│   ├── wireframe.md
│   └── content-plan.md
├── README.md
└── .gitignore