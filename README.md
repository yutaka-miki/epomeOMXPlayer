# epomeOMXPlayer
PCで作った「専用2D映像」を読み込み、「3D映像」として再生するアプリケーションです。  
起動すると「/epomeOMXPlayer/bin/data/loadMovie.txt」で指定した「専用2D映像」を再生します。「専用2D映像」と「3D映像」については<a rel="license" href="https://github.com/yutaka-miki/Epometrope#%E3%82%B3%E3%83%B3%E3%83%86%E3%83%B3%E3%83%84%E9%96%8B%E7%99%BA" target="_blank">こちら</a>。  
このアプリケーションは「<a rel="license" href="https://github.com/yutaka-miki/ofxEpometrope" target="_blank">ofxEpometrope</a>」に依存します。

## 操作
#### [Q]動作チェック（全アプリケーション共通）
Qキーを押すと動作のチェック画面になります。向いてる角度に応じて白、赤、青のグラフィックを表示します。

#### [W]回転速度チェック（全アプリケーション共通）
Wキーを押すと回転速度をバーの長さで示します。白が適正速度、赤が速すぎる速度域で有ることを示します。

#### [R]動画リセット
  
## 動画の差し替え方
(1)「/home/pi/openFrameworks/apps/myApps/epomeOMXPlayer/bin/data/movie/」  
の下に動画データを追加します。  
  
(2)「/home/pi/openFrameworks/apps/myApps/epomeOMXPlayer/bin/data/loadMovie.txt」  
を追加した動画データのパスに書き換えます。
  
## 注意点
・ビットレートの高い動画はフレームレートが遅延し、「3D映像」のカクつく可能性があります。カクつきを抑えたい場合は、フレームレートやサイズを落としてください。
