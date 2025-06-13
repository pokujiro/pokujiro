# 岡優太's Portfolio

### 混沌を構造へ、アイデアを形へ。

はじめまして、岡 優太です。山口大学大学院で、VRと人の学習に関する研究をしています。

私が開発において最も大切にしているのは**「仕組みで人を自由にする」**ことです。優れた仕組みは作業を効率化し、人に時間的・精神的な余裕を生み出します。その余裕こそが、新しい挑戦や成長への「きっかけ」になると信じています。

研究で取り組んでいるVR動作学習システムのUI/UXデザインも、この信念に基づいています。複雑な情報を直感的に伝え、誰もが「優しいテクノロジー」の恩恵を受けられる。そんなユーザ中心のプロダクト開発で、社会に貢献したいと考えています。

---

## 🔧 Skills & Certifications

| Category          | Skills                                                                                                                                                             |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Languages** | <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white"> |
| **Frameworks** | <img src="https://img.shields.io/badge/Unity-FFFFFF?logo=unity&logoColor=black"> <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black"> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white"> |
| **Tools & Others**| <img src="https.img.shields.io/badge/Git-F05032?logo=git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"> |
| **Certifications**| <img src="https://img.shields.io/badge/基本情報技術者-FE-orange"> <img src="https://img.shields.io/badge/色彩検定-2級-9cf"> |

---

## 💻 主な制作物 (Major Projects)

### 1. 研究：個人差を考慮したVR全身動作学習支援システム (卒業論文)
<details>
  <summary><strong>クリックして詳細を表示</strong></summary>
  
  ユーザー一人ひとりの「体格の違い」を吸収し、誰でも公平かつ正確に全身の動きを学べるVRトレーニングシステムを設計・開発しました。
  
  - **課題背景:** 従来のシステムでは、指導者と学習者の身長や手足の長さが違うと、正しい動作をしても「ズレ」と誤判定される問題がありました。 
  
  - **主な実装と貢献:**
    - **① 体格差補正アルゴリズムの開発:** 身長・腕・脚の長さの比率をリアルタイムで計算し、お手本動作を学習者の体格に合わせて自動で正規化する独自のアルゴリズムを設計・実装しました。  これにより、体格に依存しない公平な動作評価を実現しました。 
    - **② リアルタイム3Dフィードバック:** ユーザーとお手本アバターの位置・回転の誤差を即座に計算。  誤差の種類（位置/回転）と大きさに応じて、アバターの各部位の色を青や赤に変化させる直感的なフィードバックシステムを構築しました。 
    - **③ 少数トラッカーでの全身動作再現:** HTC VIVE Ultimate TrackerとMeta Quest 3を組み合わせ、計5点のトラッカーだけで自然な全身の動きを再現する効率的なシステムをFinalIKを用いて実現しました。 
    
  - **検証と成果:** 12名の被験者実験を行った結果 、本システムを使用したグループは、お手本動画のみで練習したグループに比べ、**動作の一致度が約2倍向上**しました。  また、独自開発した体格補正機能は、被験者から「自然で真似しやすい」と高く評価されました (平均評価 6.0/7.0)。 
  
  - **使用技術:** Unity, C#, FinalIK, HTC VIVE Ultimate Tracker, Meta Quest 3, SteamVR 
</details>

### 2. マンドリンクラブの楽譜DXプロジェクト | チームの合意形成と業務改革
<details>
  <summary><strong>クリックして詳細を表示</strong></summary>
  
  約50名が所属する大学マンドリンクラブで、紙でアナログ管理されていた約1500曲の楽譜の電子化を提案・主導しました。
  
  - **課題:** 楽譜探しに時間がかかり、練習効率が悪い。紛失・劣化のリスク。
  - **行動:**
    - **合意形成:** 当初の「慣習を変えたくない」という抵抗に対し、試験導入でデジタル化の利便性を体感してもらい、歓喜の声と共に全部員の合意を取り付けました。
    - **仕組み化:** 全楽譜をスキャンし、曲名・作曲者別に分類。部員が瞬時に楽譜を取得できる仕組みを構築し、運用マニュアルも作成して後輩へ引き継ぎました。
  - **成果:** 楽譜準備の時間を**1時間から5分に短縮**し、練習効率を飛躍的に向上させました。技術導入と並行して、利用者の理解と合意を得る「人間中心のDX推進」の重要性を学びました。
  - **使用技術:** PCファイリング, スキャナ, USB共有, マニュアル作成(Notion)
</details>

### 3. NASA Space Apps Challenge 2024 (ハッカソン)| "People's Choice"賞 受賞
<details>
  <summary><strong>クリックして詳細を表示</strong></summary>
  
  NASA主催の世界同時開催ハッカソンにて、チーム「Space Browse」として参加。NASAのオープンデータを用い、「背景画像と説明文とBGMをランダムに表示できるように」というテーマでWebアプリケーションを2日間で開発しました。
  
  - **役割:** 主にアイデア出しとチームの意見集約を担当。多様な意見を一つのコンセプトにまとめ上げました。
  - **成果:** ユーザー体験の楽しさが評価され、**People's Choice賞**を受賞。短期間でのアイデアソンとチームでのプロトタイピング能力を証明しました。
  - **使用技術:** JavaScript, React, HTML, CSS
  - **リポジトリ:** [[リポジトリへのリンク](https://github.com/T-yao-K/NASA-space-apps-teamb)]
</details>

### 4. 個人開発：TodoPet | ゲーミフィケーションを取り入れたタスク管理アプリ
<details>
  <summary><strong>クリックして詳細を表示</strong></summary>
  
  日々のタスク管理に、ペット育成の要素を加えてモチベーションを維持しやすくするWebアプリケーションです。タスクをチェックして完了するとペットの「愛情度」が上がり、一定の値に達するとレベルアップします。
  
  - **主な機能:** タスクの追加・削除、完了チェックリスト、タスク完了と連動したペットの育成システム、カレンダー機能
  - **使用技術:** React, FastAPI, Python, JavaScript, HTML, CSS
  - **リポジトリ:** [リポジトリへのリンク](https://github.com/pokujiro/Development)
</details>

### 5. 共同開発：スマートコンセント電力モニター
<details>
  <summary><strong>クリックして詳細を表示</strong></summary>
  
  Pythonと`tinytuya`ライブラリを用いて、家庭のスマートコンセントの電力使用量を定期的に取得・記録し、そのデータをブラウザ上で可視化するWebアプリケーションです。リアルタイムの電力状況や過去の使用量推移をグラフで確認できます。
  
  - **主な機能:** リアルタイム電力表示、期間別のグラフ表示（Chart.js）、月間目標設定
  - **使用技術:** Python, tinytuya, HTML, CSS, JavaScript, Chart.js
  - **リポジトリ:** [[リポジトリへのリンク](https://github.com/pokujiro/OutletApp)]

</details>

---

## 🏆 Awards
- **卒業論文審査会 優秀賞** (2024年2月) - [記事リンク](http://www.csse.yamaguchi-u.ac.jp/2024/02/20240228.html)
- **EMaT(工学系数学統一試験) 成績優秀者** (2023年12月) - [記事リンク](https://www.yamaguchi-u.ac.jp/eng/news/3832/index.html)
- **常盤賞** (学部4年間の学業成績優秀者に授与)- [記事リンク](http://www.csse.yamaguchi-u.ac.jp/2025/03/20250321.html)
- **学業特待生** (学部3, 4年次)

---

## 📖 Other Activities & Experience

- **VRオンライン留学 (2023年1月〜3月)**
  - 英国シェフィールド大学のVR語学留学プログラムに参加しました。世界中の参加者とアバターとして仮想空間に集い、従来のオンライン留学とは異なる高い没入感の中で、実践的な英会話を学びました。VR技術の教育分野への応用可能性を実体験する貴重な機会となりました。

- **[デジテック for YAMAGUCHI](https://digitech-ymg.org/) (メンバー)**
  - 山口県のDX(デジタル変革)を推進する官民連携コミュニティ「デジテック for YAMAGUCHI」に、メンバーとして参画しています。地域の企業や学生と共に、IT技術を活用した地域課題の解決（少子高齢化、若者流出など）に向けた勉強会やアイデア創出ワークショップに参加し、知見を深めています。

---
