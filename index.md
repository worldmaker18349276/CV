---
title: 黃昱維
---

## 基本資料
- 姓名：黃昱維
- 人格類型：INFP-T
- GitHub：https://github.com/worldmaker18349276
- 聯絡信箱：worldmaker18349276@gmail.com
- 聯絡電話：0916662641
- 聯絡地址：台南市東區

## 學經歷

- 2012/09 ~ 2016/06 成功大學物理系畢業
- 2016/09 ~ 2023/01 成功大學物理所博士畢業

## 專長

### 擅長的程式語言
- Python + numpy／scipy／matplotlib
- JavaScript／HTML／CSS
- Rust
- Haskell
- LaTeX
- Java

### 擅長的技術
- 資訊安全
- 數值計算
- 架構設計

## 專案

### EZPrivacy （成大資工黃宗立教授主導）
- _main language_: Java
- _description_: A service to provide privacy without pain.

  大二時開始參與的計畫。
  核心想法為藉由對稱加密方法建構一套資訊安全系統，以此抵禦因量子加密興起而產生的資安破口。
  作為初期成員，曾與其他成員討論並設計系統架構，學習到了由上而下的開發過程。
  也有參與 protocol 的設計與除錯。

### [nu](https://github.com/worldmaker18349276/nu)  (private)
- _main language_: Python
- _description_: All numerical techniques for our group.

  這是集合了我於研究所使用的數值計算工具的函式庫。
  其中包括定積分，不定積分，捲積，相關函數，傅立葉轉換，希爾伯特轉換等常用數值方法，
  以及 integro-differential equation 的數值方法。
  其中數值積分和數值微分的矩形法，梯形法，辛普森法，不同階的龍格-庫塔法都可以調整。
  此專案還包含以上所有方法的推導和解釋，以及針對 integro-differential equation 對於數值方法各種組合的詳細分析。
  還有推導與演示各種問題（例如：擾動函數的計算，電流的計算）的已知最佳數值演算法。

### [twisty sphere](https://github.com/worldmaker18349276/twisty-sphere)
- _main language_: JavaScript
- _description_: An emulator for twisty puzzle, especially for single-core jumbling twisty puzzle.

  魔術方塊發展至今早已脫離群論的範疇，其中由些許對稱性破壞造成的 jumbling 的行為更是難以捉摸。
  一般的魔術方塊模擬器沒辦法模擬 jumbling 的操作，因為所有魔術方塊元件的可動範圍已被寫死了。
  這個專案以另外一種方式模擬魔術方塊的運作，其中魔術方塊元件的移動靠的是分析與其相鄰元件的關係，從而實現高自由度的行為。
  本專案未來將著重於分析所有元件的組態，並以演算法直接計算出任意魔術方塊的解法。

### [K-AIKO](https://github.com/worldmaker18349276/K-AIKO)
- _main language_: Python
- _description_: A sound-controlled terminal-based one-line Taiko-liked rhythm game.

  為了證明終端機上也能做出好遊戲，我開始了這個專案，其中結合了許多意想不到的概念。
  為了在只能顯示文字的終端機上順暢地顯示遊戲畫面，我放棄使用 ncurses library，自己寫了一套著重於單行顯示的函式庫。
  為了能有效率的分析聲音以判斷打擊點，我自己寫了一套能實時處理串流資訊的函式庫。
  其中音訊的輸出輸入依賴於 [PyAudio](https://pypi.org/project/PyAudio/)，它在終端機上會印出一些系統資訊。
  這個行為沒辦法控制，我索性就將整個遊戲風格做的像駭客一樣，其中遊戲選單模擬了現代終端機的行為，包括自動完成選字，參數提示，指令歷史瀏覽等。
  我也自己寫了一套類似於 [Rich](https://github.com/Textualize/rich) 的函式庫，以對此專案的需求進行微調。
  本遊戲的設定檔和自製譜面的語法都是模仿 Python，為了正確地解碼設定檔，我自己寫了一套類似於 [parsec](https://hackage.haskell.org/package/parsec) 函式庫。
  本專案未來將實作譜面編輯器，譜面偵測等高階功能。

### [cuboard](https://github.com/worldmaker18349276/cuboard)
- _main language_: Rust
- _description_: Turn your smart cube into a keyboard.

  智慧魔術方塊能透過內建的偵測器判斷方塊的狀態，這使得魔術方塊也能作為輸入裝置使用。這個想法早已出現於 20 幾年前的動漫中。
  為了將魔術方塊的狀態與操作轉換成文字輸出，我對其拓樸性質進行分析，並設計了一個不錯的方案。
  將魔術方塊作為鍵盤非常不切實際，但這顯示了它的可能性。
  未來本專案將會繼續拓展智慧魔術方塊的應用範圍。

### [BAC](https://github.com/worldmaker18349276/bac)  (unfinished, private for now)
- _main language_: Haskell
- _articles_: ["Abstract Orientable Incidence Structure and Algorithms for Finite Bounded Acyclic Categories. I. Incidence Structure"](https://arxiv.org/abs/2303.04306), "Abstract Orientable Incidence Structure and Algorithms for Finite Bounded Acyclic Categories. II. Data Structure and Fundamental Operations" (coming soon)
- _description_: A data structure for bounded acyclic categories.

  在專案 [twisty sphere](https://github.com/worldmaker18349276/twisty-sphere) 中，我用幾何方法模擬了二維魔術方塊的運作。
  若要推廣到任意維度的魔術方塊，需要對任意維度的幾何有更深的認識。
  二維的情況作為特例非常簡單，而在任意維度下這個問題很複雜，而且似乎沒有文獻探討過。
  為了分析任意維度的幾何，需要將幾何物件之間的關係建模成 bounded acyclic categories（類似於 directed acyclic graphs）。
  此函式庫即為此數學模型的資料結構與相應的演算法。
  具體細節將會以學術文章的形式發布於 arXiv 上。

## 自我評價

- 不擅長使用工具
- 擅長思考，分析問題
- 擅長學習新技術
- 內向，不擅長溝通
- 缺少硬體相關的知識
