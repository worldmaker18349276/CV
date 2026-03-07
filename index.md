---
title: 黃昱維
---

## 基本資料
- 姓名: 黃昱維 (Yu-Wei Huang)
- 信箱: worldmaker18349276@gmail.com
- GitHub: [worldmaker18349276](https://github.com/worldmaker18349276)
- LinkedIn: [昱維-黃-3a1326132](https://www.linkedin.com/in/%E6%98%B1%E7%B6%AD-%E9%BB%83-3a1326132/)

## 學經歷

- 2012/09 ~ 2016/06 成功大學物理系畢業
- 2016/09 ~ 2023/01 成功大學物理所博士畢業
- 2023/05 ~ now     藏識科技軟體工程師

## 專長

- **量子開放系統** (Open Quantum Systems)
- **程式語言**  
  C/C++, C#, Java, Rust, Python, TypeScript, Haskell, LaTeX
- **資料庫系統**  
  SQLite, PostgreSQL, MySQL, Microsoft SQL Server
- **數值計算與科學分析**  
  Python (NumPy, SciPy, Matplotlib)
- **演算法**  
  Path Finding, Motion Planning, Visual–Inertial Odometry
- **計算幾何與空間分析**  
  Geometric Algorithms, Mesh Simplification, Viewshed Analysis

## 學術論文

- Yu-Wei Huang, Pei-Yun Yang, and Wei-Min Zhang,
  _Quantum theory of dissipative topological systems_,
  Phys. Rev. B **102**, 165116 (2020).

- Yu-Wei Huang and Wei-Min Zhang,
  _Exact master equation for generalized quantum Brownian motion with momentum-dependent system-environment couplings_,
  Phys. Rev. Research **4**, 033151 (2022).

- Yu-Wei Huang,
  _Bosonic/Fermionic Tensor Network Diagram and Normal Ordering Super-Fock Space_,
  博士畢業論文 (2023).

- Yu-Wei Huang,
  _Abstract Orientable Incidence Structure and Algorithms for Finite Bounded Acyclic Categories. I. Incidence Structure_,
  arXiv preprint arXiv:2303.04306 (2023).

- Yu-Wei Huang,
  _Abstract Orientable Incidence Structure and Algorithms for Finite Bounded Acyclic Categories. II. Data Structure and Fundamental Operations_,
  arXiv preprint arXiv:2307.00357 (2023).

## 專案

### EZPrivacy （成大資工黃宗立教授主導）
- _main language_: Java
- _description_: A service to provide privacy without pain.

  大二時開始參與的計畫。
  核心想法為藉由對稱加密方法建構一套資訊安全系統，以此抵禦因量子加密興起而產生的資安破口。
  作為初期成員，曾與其他成員討論並設計系統架構。
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

### [BAC](https://github.com/worldmaker18349276/bac)
- _main language_: Haskell
- _description_: A data structure for bounded acyclic categories.

  在專案 [twisty sphere](https://github.com/worldmaker18349276/twisty-sphere) 中，我用幾何方法模擬了二維魔術方塊的運作。
  若要推廣到任意維度的魔術方塊，需要對任意維度的幾何有更深的認識。
  二維的情況作為特例非常簡單，而在任意維度下這個問題很複雜，而且似乎沒有文獻探討過。
  為了分析任意維度的幾何，需要將幾何物件之間的關係建模成 bounded acyclic categories（類似於 directed acyclic graphs）。
  此函式庫即為此數學模型的資料結構與相應的演算法。
  詳細理論請見 [arXiv:2303.04306](https://arxiv.org/abs/2303.04306) 與 [arXiv:2307.00357](https://arxiv.org/abs/2307.00357).

### [twisty-space-rift](https://github.com/worldmaker18349276/twisty-space-rift)
- _main language_: TypeScript
- _description_: 2D twisty puzzles on Riemann surface.

  黎曼空間具有一些特別的屬性：繞著某個點一圈會跑到不同的空間中，就像有一道時空裂縫連接著平行宇宙一樣。
  在遊戲《Antichamber》中就使用了這種概念，通過不同的窗戶看到的景色是不同的。
  這個專案試圖在這種特殊的空間中模擬魔術方塊，必須轉動720度才能轉回原本的位置，甚至能讓裂縫本身跟著轉動。
  其中使用了幾何方法判斷空間的連接性與裂縫的拓樸，從而實現高自由度的模擬。
  這個專案拓展了我對分支空間與繩結理論的了解，並讓我更熟悉離散拓樸的數值方法。

### [aperiodic-tilings](https://github.com/worldmaker18349276/aperiodic-tilings)
- _main language_: TypeScript
- _description_: Any-precision aperiodic tilings generator.

  非週期性密鋪是不具週期性的密鋪，也就是你隨便挑一個點，所看到的景色都是不同的，而且這個空間是無限大的。
  基於這個想像，我想把它做成能像地圖一樣輸入任意座標就能瞬間跳躍到指定位置的程式。
  然而大部分非週期性密鋪的實做都是從原點生成，這使得要生成距離 D 的密鋪時需要 O(D^2) 的計算量。
  而且當範圍太大時，會有數值計算的捨入誤差，使得超遠距離的密鋪出現明顯的位移。
  這個專案使用體擴張理論與 BigInt 實現任意精度的數值運算，並使用緩存方法讓計算時間降到 O(log D) 的計算量。

### [interaction_circuit](https://github.com/worldmaker18349276/interaction_circuit)
- _main language_: Go
- _description_: Minimal evaluator for interaction nets.

  為什麼電腦工程/科學都是以命令式編程為主，而非函數式編程。上到高階程式語言，前後端框架，下到硬體架構與計算理論。
  因此我小時候曾經想過在電路層面實做基於 lambda calculus 的電腦，就像現代電腦是在電路層面實做類似於 Turing mechine 的 Von Neumann architecture 一樣。
  然而當時遇到一個難以解決的問題：變數遮蔽在電路層面實做起來非常困難。
  而後來我學到了比 lambda calculus 更強大與美麗的 interaction calculus，並意識到它的線性屬性使它更容易在電路層面實做。
  這個專案就是試圖先使用程式實做一個極小的 interaction net 求值引擎，以證明其可行性。
  下一步便是試圖在硬體模擬軟體中設計邏輯電路。

### 精細模型簡約化 (PilotGaea)
- _main language_: C++
- _description_: 簡約化精細模型以優化遠距離的圖資展示。

  在地圖中我們不可能載入所有建物模型展示在畫面上，而是根據視野遠近載入適合的精細度 (LOD) 的模型。
  對於一些特殊場景，可能需要非常高精細度的模型，這時可以透過簡約化產製低精細度的模型以優化展示效能。
  這個專案透過將精細模型點雲化並使用 SfM 重建具有拓樸的模型，再使用基於拓樸的簡約化方法，已達到降低負載的目的。

### 視域分析 (PilotGaea)
- _main language_: C++
- _description_: 根據給定地形資料，分析從某處能夠看到的範圍。

  這個專案結合 PDERL 投影算法，分區法，四叉樹，資料緩存優化與平行運算，實現了高效率的視域分析 (時間複雜度 O(n))。
  分析半徑 300 km 的範圍只需要不到 1 秒的時間 (地形資料的網格為 20 m)。

### 無人船路徑規劃 (PilotGaea)
- _main language_: C++
- _description_: 無人船避障路徑規劃與編隊航行。

  此專案使用基於 hybrid A* 路徑搜尋算法實現多艦實時路徑規劃，以達成指定任務如包圍敵艦。
  其中會考量迴轉半徑，避免船艦互相碰撞或是與障礙物碰撞。
  另外還能夠在盡量維持隊形的情況下實現避障路徑規劃。
  為了實現避免碰撞與實時路徑規劃，算法中的代價函數與啟發函數需要做一些魔改。
  而為了順暢地迴轉與維持隊形，需要對轉向與速度做進一步的控制。

### 無人機視覺避障 (PilotGaea)
- _main language_: C++
- _description_: 適用於旋翼無人機的視覺避障路徑規劃，與基於視覺的姿態估計算法。

  此專案參考 EGO Swarm 實現實時視覺避障路徑規劃，以及多機協同與編隊飛行。
  並參考 D2SLAM 實現實時視覺姿態估計算法與深度圖估計算法。
  其中使用了梯度下降優化算法，繞路法路徑避障，邏輯迴歸障礙物估計，
  以及光流法特徵點追蹤，束調整法，虛擬雙目等技術。
