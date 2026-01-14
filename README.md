# 經典小瑪莉 - 復古麻仔台 / Classic Mary Arcade Game

## 🇹🇼 繁體中文

### 項目簡介
這是一個使用網頁技術開發的經典復古「小瑪莉」麻仔台模擬器。重現了 80-90 年代街機廳的懷舊氛圍，具有動態跑燈、電子音效以及豐富的押注互動。

*   **開發日期**: 2026年01月14日
*   **版本**: v1.0.0

### 操作方法
1.  **押注**: 點擊畫面下方的圖案按鈕（如：🍒、🍊、🏆 等）進行押注。
2.  **清除**: 若想重置押注，點擊「清除押注」按鈕。
3.  **啟動**: 按下紅色的「啟動 START」按鈕開始遊戲。
4.  **結算**: 跑燈停止後，若停在有押注的項目，得分會自動加入總分。

### 使用技術
*   **HTML5 & Semantic Tags**: 構建遊戲佈局與結構。
*   **CSS3 & Tailwind CSS**: 實現復古霓虹燈 UI、玻璃擬態（Glassmorphism）與動畫效果。
*   **JavaScript (ES6+)**: 處理隨機演算法、賠率判定、跑燈動畫與狀態管理。
*   **Web Audio API**: 實時合成電子 Beep 音效，不需外部音檔。

---

## 🇺🇸 English

### Project Overview
A web-based simulation of the classic "Little Mary" (Mary's Bar) arcade machine from the 80s and 90s. This project recreates the nostalgic atmosphere of retro arcades with dynamic lights, electronic sound effects, and interactive betting.

*   **Development Date**: January 14, 2026
*   **Version**: v1.0.0

### How to Play
1.  **Betting**: Click on the symbol buttons at the bottom (e.g., 🍒, 🍊, 🏆) to place your bets.
2.  **Clear**: Click "Clear Bets" to reclaim points and reset the betting area.
3.  **Start**: Press the red "START" button to spin the lights.
4.  **Winning**: If the lamp stops on a symbol you bet on, you win points based on the multiplier.

### Technologies Used
*   **HTML5**: Project structure.
*   **Tailwind CSS**: Modern styling and retro neon effects.
*   **Vanilla JavaScript**: Game logic, random weight calculation, and animation control.
*   **Web Audio API**: Real-time synthesized arcade sound effects.

---

## 🇯🇵 日本語

### プロジェクト概要
80年代から90年代にかけて大人気だった「小瑪莉」（リトルメアリー）風のレトロアーケードゲームシミュレーターです。動的なライト演出、電子音、インタラクティブなベッティングにより、ノスタルジックな雰囲気を再現しています。

*   **開発日**: 2026年01月14日
*   **バージョン**: v1.0.0

### 操作方法
1.  **ベット**: 下部の各アイコン（🍒、🍊、🏆など）をクリックしてポイントを賭けます。
2.  **クリア**: 「クリア」ボタンを押すと、賭けたポイントが戻ります。
3.  **スタート**: 赤い「START」ボタンを押してランプを回転させます。
4.  **勝利**: ランプが自分の賭けたアイコンに止まると、配当に基づいたポイントを獲得できます。

### 使用技術
*   **HTML5/CSS3**: ゲームのビジュアル構造。
*   **Tailwind CSS**: ネオンエフェクトとレスポンシブデザイン。
*   **JavaScript**: ゲームロジック、乱数生成、アニメーション制御。
*   **Web Audio API**: 電子ベープ音のリアルタイム合成。

---

## 🇮🇹 Italiano

### Panoramica del Progetto
Una simulazione basata sul web della classica "Little Mary" (Mary's Bar), la slot machine arcade tipica degli anni '80 e '90. Il progetto ricrea l'atmosfera nostalgica delle sale giochi vintage con luci dinamiche, effetti sonori elettronici e puntate interattive.

*   **Data di Sviluppo**: 14 Gennaio 2026
*   **Versione**: v1.0.0

### Come Giocare
1.  **Puntate**: Clicca sui pulsanti dei simboli in basso (es. 🍒, 🍊, 🏆) per piazzare i crediti.
2.  **Cancella**: Clicca su "Cancella Puntate" per recuperare i crediti e resettare l'area.
3.  **Inizio**: Premi il pulsante rosso "START" per avviare la rotazione delle luci.
4.  **Vittoria**: Se la luce si ferma su un simbolo su cui hai scommesso, vincerai punti in base al moltiplicatore.

### Tecnologie Utilizzate
*   **HTML5 & CSS3**: Struttura e stile del gioco.
*   **Tailwind CSS**: Effetti neon e design moderno.
*   **JavaScript**: Algoritmi di gioco, calcolo delle probabilità e gestione delle animazioni.
*   **Web Audio API**: Sintesi audio in tempo reale per effetti sonori arcade.

---

## 🎬 劇本 / Scenario

1.  **The Entry**: 玩家進入頁面後，會看到一個充滿霓虹感的麻仔台介面，總分預設為 1000。
2.  **The Strategy**: 玩家根據直覺在不同的圖案上押注。可能是「全押」小賠率的櫻桃和橘子來尋求穩定成功，或者將重註放在 100 倍的 BAR 上追求一夕致富。
3.  **The Tension**: 按下 START 後，跑燈伴隨著電子聲由慢變快，然後再緩緩進入終點前的減速。這段「減速」過程是遊戲的最高潮。
4.  **The Result**: 燈光最終跳動在圖案上。如果是大獎，全螢幕會閃爍「WINNER!」，並伴隨著勝利的電子旋律，讓玩家體驗街機廳贏分時的快感。
