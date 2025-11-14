# profile

2025/11月時点

## スキルセット

### Web系
|カテゴリ|内容|習熟度|
|--|--|--|
|言語|JavaScript|高|
||TypeScript|高|
|UIフレームワーク|Backbone.js|中|
||jQuery|高|
||Lit|中|
||Preact|中|
||React|低(学習中)|
|css|SCSS|高|
||goober|中|
||Emotion|低(学習中)|
|WebGL|Phaser.js(ゲームフレームワーク)|高|
||Create.js(キャンバス描画ライブラリ)|高|
||mattar.js(2D物理エンジン)|低|
|他ツール等|Electron|低|
||websocket|中|

### ネイティブ系
|カテゴリ|内容|習熟度|
|--|--|--|
|言語|C++|中(ブランクあり)|
||C#|中(ブランクあり)|
||C|中(ブランクあり)|
||Java|低(ブランクあり)|
|エンジン|DirectX|中(ブランクあり)|
||opneGL|低(ブランクあり)|
||cocos2d-x|中(ブランクあり)|
||Unity|中(ブランクあり)|

## プライベートで作ったもの(でギリギリ人様に見せられる完成度のもの)
### ペグソリティア
ビー玉を飛び越えて移動させ、飛び越したビー玉を取り除いていき、最終的に盤面のビー玉を1つにするゲーム。  
▼ リポジトリ  
https://github.com/yuduriha/peg_solitaire  
▼ github pages  
https://yuduriha.github.io/peg_solitaire/  

使用言語/ライブラリ
* ts
* React  

### 弾幕STGっぽいもの  
▼ リポジトリ  
https://github.com/yuduriha/mathematicshooter  
▼ github pages  
https://yuduriha.github.io/mathematicshooter/  
▼操作方法
```
PC: キーボード十字キー  
スマホ: ドラッグ操作  
```

使用言語/ライブラリ
* ts
* Phaser.js  

敵のHPゲージのドーナツ型の円弧を頑張った記憶があります。  

### ビリヤードの球の反射シミュレーター  
ビリヤードで直接目的の球を狙えない時に、壁に反射させて球を狙うテクニックのシミュレーターです。  
(入射角と反射角を計算しているだけです。実際には摩擦や回転なども影響するので完全にこの通りにはなりません。)

▼ リポジトリ  
https://github.com/yuduriha/kick_shot  
▼ github pages  
https://yuduriha.github.io/kick_shot/  
▼操作方法
```
球をドラッグで移動  
反射させる壁をタップで選択
```

使用言語/ライブラリ
* ts
* Phaser.js  

## 曲線上を等速で移動する点P  
数学の問題を読んでいてなんとなくプログラムで再現するにはどうしたらいいかなと思いついて作ってみたもの。  
  
「xy平面上の y = sin(x) に沿って等速で移動する動点Pの時刻tにおける位置を求めよ」という問いの答えの想定。  
※ 実際にはこの問題はかなり複雑なので簡単には解けず、近似値で実装しています。

▼ リポジトリ  
https://github.com/yuduriha/mathematicshooter  
▼ github pages  
https://yuduriha.github.io/sin_curve/  

## アクションシューティングゲーム  
自機は攻撃手段を一切持たず、敵が発射する弾でギミックを解いたり、敵を同士撃ちさせながら進んでいくゲームです。  
自機が加速すると周囲が遅くなり、敵の弾を避けやすくなります。  

元は DirectXでPC向けに複数人で作ったものを、ブラウザ向け用に私が1人で移植したものです。  
オリジナルは3Dだったのですが、ブラウザ版は私が仮で絵素材を作ったものになります。  

オリジナルの開発人数: 企画1人、ディザイナー1人、プログラマー1人、サウンド2人。  
(ブラウザ版にはサウンドは入っておりません)

▼ github pages  
https://meganekake-gohan.github.io/bihw_pub/

▼操作方法
```
キーボード操作のみ。
メニューは十字キーで操作、エンターで決定。
自機は十字キーで移動、zで加速。
```

使用言語/ライブラリ
* ts
* Phaser.js  

---

(ここに記載なくとも public になっているリポジトリは閲覧いただいてもちろん構いません。) 