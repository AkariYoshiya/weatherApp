# weatherApp

世界各地の天気を検索できるアプリ。
OpenWeatherMapのAPIを使用してタイムリーな天気情報を取得。


💻使用言語
HTML/CSS, JavaScript

🔧
OpenWeatherMap
https://openweathermap.org/

🎞️参考チュートリアル
https://youtu.be/MIYQR-Ybrn4


<学習メモ>
✅API
- APIはバックエンドが作っている。
- フロントエンドはバックエンドが作ったAPIを使ってUIを作る。
- APIデータはJSON形式で記述されている。

✅fetch() method(=function)を使いAPIを呼び出す
- 外部からデータを取得する。引数にデータのパスやURLを指定。
- fetch()はPromise<pending>オブジェクトを返す
→Promiseの中身を取得するために…、
  
✅非同期処理のasync非同期関数を使う
- await fetch()にするとResponseオブジェクトが返ってくる
- ResponseオブジェクトにはAPI取得に成功してるか等の情報が入ってる
→Responseの情報はプログラミング上だと見れない…、
  
✅Responseが持っている.json() methodを使ってプログラミングで使いやすいデータに変換する
- json()の前にもawaitをつける

