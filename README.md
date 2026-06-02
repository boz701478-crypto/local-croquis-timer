# Local Croquis Timer (Line of Action Style) ⏱️

[日本語](#japanese) | [English](#english)

<a id="japanese"></a>
## 🇯🇵 日本語

**Local Croquis Timer** は、完全ローカルで動作するジェスチャードローイング（クロッキー）用のタイマーアプリです。
サーバーとの通信を一切行わず、お使いのPC内の作画資料を使ってノイズレスな練習環境を構築します。有名練習サイト「Line of Action」の使い心地をベースに、意図的な練習（Deliberate Practice）における認知負荷を下げるための機能を盛り込みました。

### ✨ 特徴 (Features)
- **完全オフライン・サーバーレス動作**: 外部への画像アップロードは一切発生しません。
- **ノイズレスなUI**: 画面の下部を隠さず、右上に半透明のタイマーが常駐します。
- **キーボードショートカット対応**: ペンを持ったまま片手で操作可能です。
  - `Space`: 一時停止 / 再生
  - `→` / `←`: 前後の画像へ移動
  - `Esc`: 終了
- **カウントダウン警告音**: 残り5秒で文字が赤くなり、1秒ごとに警告音が鳴ります。

### 🚀 使い方 (Usage)
1. `index.html` をブラウザで開きます。
2. 「ファイルを選択」ボタン（またはドラッグ＆ドロップ）で、練習に使いたい画像をすべて選択して読み込みます。
3. 1枚あたりの表示秒数を設定します。
4. **予測させない多様練習（インターリービング）を行いたい場合は、「ランダムな順番で表示」にチェックを入れてください。**（チェックを外すとファイル名順に再生されます）
5. スタートボタンを押してクロッキーを開始します。

---
<a id="english"></a>
## 🇬🇧 English

**Local Croquis Timer** is a completely local, serverless timer application for gesture drawing and croquis practice. 
It operates entirely offline, using your local reference images to create a noise-free practice environment. Inspired by the excellent UI of "Line of Action," it includes features designed to reduce cognitive load during deliberate practice.

### ✨ Features
- **Completely Offline & Serverless**: No images are ever uploaded to an external server.
- **Noise-Free UI**: Unobstructed image view with a semi-transparent timer stationed in the top right.
- **Keyboard Shortcuts**: Operate with one hand while holding your pen.
  - `Space`: Pause / Play
  - `→` / `←`: Next / Previous image
  - `Esc`: End session
- **Countdown Alerts**: Text turns red at 5 seconds remaining, accompanied by a subtle beep every second.

### 🚀 Usage
1. Open `index.html` in your web browser.
2. Select or drag-and-drop your local reference images into the app.
3. Set your desired time per image.
4. **Check the "Randomize order" box if you want the images to appear in a shuffled sequence.** (Uncheck to play in alphabetical order by filename).
5. Click Start to begin your session.
