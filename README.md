# AI基礎（工学部）

信州大学「AI基礎（工学部）」教材リポジトリ（新課程用）

## 教材形式

* 【講義】パワーポイント教材（PPT,PDF）＋台本（Word） ⇒ 音読さんTTS（MP4）
* 【演習】以下の通り
* Google colab版: 直接colab環境で実行できる形式（変更したければ個々人のGoogleドライブへコピーが必要）
* HTML版: Jupyter Notebook版からのHTMLエクスポート (HTML)
* PDF版: Jupyter Notebook版からのPDFエクスポート (PDF)
* Reveal.js版: Jupyter Notebook版（Slide指定あり）からのReveal.js slides版をエクスポート (HTML)

## GitHubからeALPSへのデプロイ方法

1. 基本的に，Google colab版をmasterとしてから，Jupyter Notebook版としてコピー後 調整する． (.ipynb)
2. Jupyter Notebook : 印刷プレビュー経由でPDF保存する．(.pdf)
3. Jupyter Notebook : HTML版をエクスポートする． (.html)
4. Jupyter Notebook : Slide指定でRISEの動作を確認後， Reveal.js slides版をエクスポートする． (.slides.html) <https://revealjs.com/>

## 目次

1. AIの歴史と応⽤分野（☆）、AIと社会（☆）【講義】
2. 機械学習の基礎と展望（☆）【講義】
3. 生成AIの基礎と展望（☆改定・追加）【講義】
4. 演習環境の使い方とプログラミング言語の演習【演習】
5. サポートベクターマシンの演習【演習】
6. 深層学習の基礎と展望（☆）【講義】
7. AIの構築と運⽤（☆）【講義】
8. 畳み込みニューラルネットワークの演習【演習】

# memo

2025.2.26 URL変更された (common, otherサーバ)
2025.7.30 【講義】【演習】形式で教材の取り扱いが異なることを記述（杉浦先生、岡野先生）

## 数理DS 新必修2科目（年度更新されない版） URL

* 新DS・DE基礎(構築中) <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=86>
* 新AI基礎(コレ。構築中) <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=89>

## 数理DS コア3科目（年度更新されない版） URL

* DS基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=87>
* DE基礎 <https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=88>
* AI基礎は新AI基礎にマイグレーション済　<https://lms.ealps.shinshu-u.ac.jp/common/course/view.php?id=89>

## 工学部 学部共通科目 データサイエンス科目（2023 R5年度版）　URL

* DS基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=413>
* DE基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=414>
* AI基礎(2023) <https://lms.ealps.shinshu-u.ac.jp/2023/t/course/view.php?id=415>

## 工学部 学部共通科目 データサイエンス科目（2024 R6年度版）　URL

* DS基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=594>
* DE基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=401>
* AI基礎(2024) <https://lms.ealps.shinshu-u.ac.jp/2024/t/course/view.php?id=595>

## 学外連携・その他 eALPS URL

### 経産省 共同研究講座

* 産学連携 / デジタル人材育成共同研究講座
<https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=15>

* データサイエンス(DS)概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=26>
* データエンジニアリング概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=27>
* 機械学習概論I
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=28>
* AIエンジニアリング概論（佐藤真平先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=29>

### 工学教育寄附講座

* 産学連携 / 工学教育寄附講座
<https://lms.ealps.shinshu-u.ac.jp/other/course/index.php?categoryid=16>

* データサイエンス概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=30>
* データエンジニアリング概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=31>
* データマイニングと機械学習概論
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=79>
* 画像認識へのAIの適用（宮尾先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=33>
* AI技術による自然言語処理ツール入門（小形先生）
<https://lms.ealps.shinshu-u.ac.jp/other/course/view.php?id=32>
* 基礎制御設計（千田先生）
<https://lms.ealps.shinshu-u.ac.jp/other/enrol/index.php?id=35>


# jupyter notebook viewer

* sec.3のノートブックを直接表示する例
https://nbviewer.org/github/MDASH-shinshu/MDASH-T-DS/blob/main/3/3_data_search_and_visualization_colab.ipynb
