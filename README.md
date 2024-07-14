# first-step
入学式で使う、「プログラミングのはじめの一歩」の資料です！

## 今日のゴール！
- HTML,CSSをはじめて触って画面に文字や画像を表示してみる
- 「できた！」「お〜！」を体験する！（ぜひ大きなリアクションを！！）

## HTMLとは
![HTML5_Logo](https://github.com/user-attachments/assets/2261be21-b6f3-4b71-a014-ecc78cef55a1)
- 「Hyper Text Markup Language」の略で、Webページを制作するためのマークアップ言語です
- タグというものを使って、Webページ内のテキスト情報の構成（タイトル・段落など）などをコンピュータさんが構造的に理解できるようにします！　　
 ![image](https://github.com/user-attachments/assets/a9ea9a3b-2c0a-4993-83f9-ac65274af353)


## CSSとは
![CSS_logo](https://github.com/user-attachments/assets/9822a85f-c33d-4a5b-b20b-a857896b1546)
- 「Cascading Style Sheets」の略で、Webサイトのサイズや色、レイアウトなどを設定するためのスタイルシート言語です
- CSSではHTMLで作られたページを装飾し、Webサイトの「見え方」を決めることができます！　　
  ![image](https://github.com/user-attachments/assets/824e5320-b7ed-412e-be59-fc47e2ef27d3)

### ページの構成要素を見るためには
- Chromeのデベロッパーツール（検証画面）で画面を構成しているHTMLやCSSを確認することができます　　
<img width="621" alt="image" src="https://github.com/user-attachments/assets/75aa325c-8c2c-4138-ae81-d0e35f781b0c">　　<br>
<img width="889" alt="image" src="https://github.com/user-attachments/assets/1737cda0-fd64-4337-836a-bc78f1a6cdbb">



## ここからハンズオン！

### STEP1：必要なファイルをダウンロードしてVSCODEで開いてみよう！
- GithubからZipファイルをダウンロード<br>
　![image](https://github.com/user-attachments/assets/5a8f90a1-6edd-4d50-95ee-f10cbc4851b8)

- ダウンロードしたZipファイルを解凍する<br>
![image](https://github.com/user-attachments/assets/fa4e67c8-0716-40dd-bf09-5458b6c5db40)

- VSCODEを開く<br>
![image](https://github.com/user-attachments/assets/f6d50d3a-06d4-4daa-96e5-3a8b97814fa9)

- 「開く」をクリックして解凍したフォルダを選択<br>
![image](https://github.com/user-attachments/assets/bd37a6af-c778-4a91-b91e-16968a66a2a1)
- ここまで来ればOK!<br>
![image](https://github.com/user-attachments/assets/3ac705aa-47d9-45d2-8f68-d7ecc49285a0)



### STEP2：HTMLファイルを触ってみよう！<br>
- practiceフォルダのindex.htmlを開く<br>
![image](https://github.com/user-attachments/assets/bfad92a3-814e-4612-a339-3c4fc517656f)


- 「!(半角のビックリマーク)」を打って、「Tab」を押下　<br>
![image](https://github.com/user-attachments/assets/ba99718f-955b-41c7-941c-33c795d9207e)<br>
![image](https://github.com/user-attachments/assets/56dc93f1-c363-48e3-a9aa-c1477e11181f)　　
- （余裕があれば、"en"を”ja”に変えておきましょう） 

-　bodyタグの中に下記のコードを書いてみよう！<br>
```
<h1>プログラミングはじめの一歩！</h1>　　
```
　　
![image](https://github.com/user-attachments/assets/ac6b54ee-a516-4013-b3c7-303ded2900a7)

- 記載できたら、Liveserverを起動　　<br>
![image](https://github.com/user-attachments/assets/801f2f5c-f94e-4268-a080-0b85e768c8a3)　　

- 下記の画面のようになればOK！　　<br>
![image](https://github.com/user-attachments/assets/a07bbafd-0407-4546-b080-ad08fb02699d)　　

- 次は下記のコードを、先ほどのコードの下に書いてみよう！<br>
```
<p>これは改行タグです</p>
```
![image](https://github.com/user-attachments/assets/513acb91-f995-44d8-89ab-dfe5e1577581)　　


- 下記の画面のようになればOK！　　<br>
![image](https://github.com/user-attachments/assets/cc90ce35-d977-4980-a405-128cc740f71e)


### STEP3:CSSファイルを触ってみよう！
- HTMLとCSSのファイルを繋げるためにindex.htmlのファイルに下記を書きましょう！<br>
```
<link rel="stylesheet" href="style.css">  
```
![image](https://github.com/user-attachments/assets/f8243cdf-fd37-420a-a6e5-0aa9c9cbb61c)


- practiceフォルダのstyle.cssを開く　　<br>
![image](https://github.com/user-attachments/assets/2e327956-4c23-4a91-bccb-d27877d27b88)


- 下記を書いてみよう！<br>
```
h1{
    color: red;
}
```

- 下記の画面のようになればOK！　　<br>
![image](https://github.com/user-attachments/assets/8eb6dc11-18e3-4edc-b82e-a5add1e6de65)



### STEP4：画像を表示させてみよう！
- imgタグをindex.htmlに書く（ img -> tabキー で表示されます！）　　<br>
![image](https://github.com/user-attachments/assets/4e4df6d9-3b26-4b5d-be1b-7d23436369c8)
```
<img src="" alt="">
```
- imgタグに必要な情報を入力する<br>
```
<img src="img/neko_sample.png" alt="猫の画像">
```
【補足】imgタグに必要な情報とは<br>
![image](https://github.com/user-attachments/assets/672c0599-3771-4b70-a71a-22961ab1f095)


- 下記の画面のようになればOK!<br>
![image](https://github.com/user-attachments/assets/5dc8a213-d424-460d-8856-c454c6f6688e)


- 画像にもCSSをあてることができます！<br>
![image](https://github.com/user-attachments/assets/3dd2eb6e-32a6-49c7-a2df-f294450c3416)

- 下記の画面のようになればOK!<br>
![image](https://github.com/user-attachments/assets/2a80185c-5282-4677-b3ec-c09b0736e250)



## さいごに　

- わからない場合は
- まずは自分で調べてみる
- 試してみる
- 試してみてわからない場合は、質問する！

- わからないことや同期やチューターと一緒に学んでいきましょう！
<img width="661" alt="image" src="https://github.com/user-attachments/assets/4e3764bc-cd37-4114-bb07-25f000e1a03f">



## サンプルサイト
- [G'sACADEMYホームページ](https://gsacademy.jp/)
- [Google](https://www.google.co.jp/)

## おすすめサイト
- [基本のタグを知れるサイト](https://makusan.ne.jp/html-tag/)
- [CSSセレクタのチートシート](https://webliker.info/css-selector-cheat-sheet/)
- [質問は恥ではないし、役にたつ](https://qiita.com/seki_uk/items/4001423b3cd3db0dada7)


