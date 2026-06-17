# FROSTLINK Alpha 0.1

スマホブラウザ向け 3D FPS 試作です。

## 起動方法
1. `index.html` をブラウザで開く
2. iPhone/Androidの場合はSafari/Chromeで開く
3. PCの場合は画面クリックでマウスロック

## 実装済み
- Three.js 3D FPS視点
- スマホ用左スティック移動
- スマホ用右スティック視点操作
- Falcon-5射撃 / ADS / リロード
- ダッシュ / スライディング
- HP100
- 短めTTK
- ヘッドショット判定
- 敵AI 5体 / 味方AI 4体
- 5vs5 Team Deathmatch風スコア
- キルログ
- ミニマップ
- Frost Base風の雪マップ
  - 通信塔エリア
  - 中央格納庫
  - 発電施設
  - 外周雪原

## 注意
CDNからThree.jsを読み込むため、ネット接続が必要です。
ローカルで開いて動かない場合は、簡易サーバーで起動してください。

例:
```bash
python3 -m http.server 8000
```
その後 `http://localhost:8000` を開く。
