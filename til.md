# 学んだこと

## 2025-04-02
- Rubyの**宇宙船演算子（＜＝＞）**は、左辺と右辺の大小関係に応じて異なる値を返す比較演算子。三方比較演算子とも呼ばれる。
【宇宙船演算子の使い方】
左辺と右辺を比較して、左辺が大きければ正の整数、小さければ負の整数を返す。
双方等しければ 0、比較できなければ nil を返す。

## 2025-04-03
- **plugin**はJavaScriptのライブラリであるJQueryを入れることで様々なpluginを利用することができる。
- JQuery plugin
- 通常の画面遷移を伴う通信を**同期通信**、JavaScriptを使った画面遷移を伴わずにサーバーと通信して画面の更新を行うことを**非同期通信**と呼ぶ。
- **Promise**とは非同期処理を特徴に持っているJavaScriptを同期処理として扱えるようにしたもの.

## 2025-04-04
- **レインボーテーブル**とはハッシュ関数を用いて生成された「ハッシュ値」と、それに対応する元の「平文（パスワードなど）」を大量に格納したデータベースのこと。 このデータベースを使った攻撃が、**レインボーテーブル攻撃**。
- **ハッシュ化**とは、平文をハッシュ関数によってハッシュ値に変換する処理を指す。

## 2025-04-05
- **Assets: precompile**とはRailsアプリケーションのアセット（JavaScript、CSS、画像など）を事前にコンパイルするためのコマンド.これにより、本番環境でのパフォーマンスを向上させるために、アセットを最適化してバンドルすることができる。

## 2025-04-06
- **salt**とは
パスワードをハッシュ化する際にランダムな値を加えることで、パスワードを破られることを防ぐ技術におけるランダム文字列を意味する用語。 パスワードごとに個別のランダム値が加えられることで、ハッシュからパスワードを推測する**レインボーテーブル攻撃**などを防ぐことができる

## 2025-04-07
- **ビットパターン**とは、コンピュータが扱うデータ（バイナリデータ）を「0」と「1」の組み合わせ（ビット）で表したもの

## 2025-04-09
- **エラーハンドリング**とは、コンピュータプログラムが実行中にエラーが発生した際に、あらかじめ用意した処理を行うこと。例外処理とも呼ばれる。

## 2025-04-10
- **N+1問題とは**
データベースから取得した1つのレコードに対して、関連するデータを取得するために、関連するテーブルに対して複数のSQLクエリを発行してしまう問題のことを指す。

## 2025-04-11
- **DevOps（デブオプス）**とは、ソフトウェアの開発と運用を連携して進める開発手法。開発（Development）と運用（Operations）を組み合わせた言葉で、開発チームと運用チームの協力体制を指す。