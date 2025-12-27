# ポートフォリオサイト

このリポジトリは **私のポートフォリオサイト** のコードです。
制作物や自己紹介、私のスキルや学習記録をまとめて公開するために作成しました。

---

## 📌 概要

このポートフォリオサイトは、以下の目的を持って作成したサイトです。

- 自分のスキルや学習歴を整理して紹介する
- 制作したWebアプリを一覧で見せる
- 採用担当者や開発者と共有できる個人用 Web ページとして運用する

サイトは Flask を使って構築しており、HTML/CSS で UI を整えています。
将来的にはリンクから各プロジェクトページに遷移できるようになっています。 :contentReference[oaicite:0]{index=0}

---

## 📂 技術スタック

このサイトの実装には以下の技術を使用しています。

- Python / Flask
- HTML / CSS
- Jinja2（Flask のテンプレートエンジン）
- JavaScript（必要に応じて）
- GitHub によるソースコード管理

---

## 🚀 実行方法（ローカル）

ローカルでポートフォリオサイトの動作を確認したい場合は以下の手順でできます。

### 1. リポジトリをクローン

- git clone https://github.com/kyohei0014/portfolio_site.git
- cd portfolio_site

### 2. 仮想環境を作成・有効化
 
- python -m venv .venv

Windows（PowerShell）

- .\.venv\Scripts\activate


macOS / Linux

- source .venv/bin/activate

### 3. 依存関係のインストール

- pip install flask


   - 必要であれば requirements.txt を作成し、そのまま pip install -r requirements.txt でも構いません。

### 4. サーバー起動
- python app.py

ブラウザで以下にアクセス：

http://127.0.0.1:5000