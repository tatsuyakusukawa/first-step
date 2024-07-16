# 入学式で使う、「プログラミングのはじめの一歩」の資料です！

## 今日のゴール！
- HTML,CSSをはじめて触って画面に文字や画像を表示してみる
- 「できた！」「お〜！」を体験する！（ぜひ大きなリアクションを！！）

## Webの仕組み（超ざっくり）
![無題のプレゼンテーション](https://github.com/user-attachments/assets/36d7112a-e8c2-40e6-9fd2-696089ca76ac)

![無題のプレゼンテーション (1)](https://github.com/user-attachments/assets/596e0242-03d3-439d-92e5-8a59f29314e3)

![無題のプレゼンテーション (2)](https://github.com/user-attachments/assets/96fa5d31-61d5-4ef7-8bd7-b68fa9cba999)


## HTML とは
![HTML5_Logo](https://github.com/user-attachments/assets/2261be21-b6f3-4b71-a014-ecc78cef55a1)
- 「Hyper Text Markup Language」の略で、Webページを制作するためのマークアップ言語です
- タグというものを使って、Webページ内のテキスト情報の構成（タイトル・段落など）などをコンピュータさんが構造的に理解できるようにします！　　
 ![image](https://github.com/user-attachments/assets/a9ea9a3b-2c0a-4993-83f9-ac65274af353)


## CSS とは
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
![image](https://github.com/user-attachments/assets/04e4c016-712b-42fc-9082-c46fd3c2dab9)
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
<h1>Hello world!</h1>　　
```
　　
<img width="516" alt="image" src="https://github.com/user-attachments/assets/053edc88-0107-4387-926f-de18d581c0e3">

- 記載できたら、Liveserverを起動　　<br>
![image](https://github.com/user-attachments/assets/801f2f5c-f94e-4268-a080-0b85e768c8a3)　　

- 下記の画面のようになればOK！　　<br>
![image](https://github.com/user-attachments/assets/cd290131-7241-4660-b515-0ef306172b88)

- 次は下記のコードを、先ほどのコードの下に書いてみよう！<br>
```
<p>これは改行タグです</p>
```
<img width="489" alt="image" src="https://github.com/user-attachments/assets/d435442c-2506-4f06-a785-9f7a9bd894a7">


- 下記の画面のようになればOK！　　<br>
![image](https://github.com/user-attachments/assets/136faaa8-03f3-4189-bbc2-01b047f54dae)


### STEP3:CSSファイルを触ってみよう！
- HTMLとCSSのファイルを繋げるためにindex.htmlのファイルに下記を書きましょう！<br>
```
<link rel="stylesheet" href="style.css">  
```
<img width="498" alt="image" src="https://github.com/user-attachments/assets/243016d9-18e3-4881-91a2-b4d57b9b1aa7">


- practiceフォルダのstyle.cssを開く　　<br>
![image](https://github.com/user-attachments/assets/2e327956-4c23-4a91-bccb-d27877d27b88)


- 下記を書いてみよう！<br>
```
h1{
    color: red;
}
```

- 下記の画面のようになればOK！　　<br>
![image](https://github.com/user-attachments/assets/539ac231-717f-41de-ac60-e25ca0e7bfd4)



### STEP4：画像を表示させてみよう！
- imgタグをindex.htmlに書く（ img -> tabキー で表示されます！）　　<br>
![image](https://github.com/user-attachments/assets/4e4df6d9-3b26-4b5d-be1b-7d23436369c8)
```
<img src="" alt="">
```
- imgタグに必要な情報を入力する<br>
```
<img src="img/ADA_img.png" alt="ADAの画像">
```
【補足】imgタグに必要な情報とは<br>
![image](https://github.com/user-attachments/assets/672c0599-3771-4b70-a71a-22961ab1f095)


- 下記の画面のようになればOK!<br>
![image](https://github.com/user-attachments/assets/77f4ff12-de11-4fd9-ae0d-589513908d18)


- 画像にもCSSをあてることができます！画像を適切な大きさにしてあげましょう<br>
![image](https://github.com/user-attachments/assets/3dd2eb6e-32a6-49c7-a2df-f294450c3416)

- 下記の画面のようになればOK!<br>
![image](https://github.com/user-attachments/assets/55d882f9-8a73-4fd5-a652-0edc2e8bcb9d)



# さいごに　

## ”自走”に向けて！
- 最初から答えを聞くのではなく、まず自分で手を動かたり、調べてみましょう！
- 15分悩んで進展がなかったら誰かに相談・質問しましょう！（15分ルール）

  
## 検索のコツ
- キーワードを工夫する
問題に関連する具体的なキーワードを使いましょう！　　例: 「HTML 画像 表示されない」「CSS ボタン 中央揃え」<br>
- エラーメッセージを利用する
エラーを頼っていきましょう！ エラーメッセージをそのままコピーして検索窓に貼り付けると良いです。（エラーは友達！）

## 相談・質問のコツ
- 相談・質問をする時は15分で試したことをもとに質問を工夫してみましょう！
- 質問する時は以下のポイントを意識してみましょう！
```
・具体的に何がわからないのか
・どんなことを試したのか
・その結果どうなったのか
・何を教えて欲しいのか
```

- 初めはみんなが初心者！
- わからないことや同期やチューターと一緒に学んでいきましょう！まずはトレーニングルームでレッツもくもく！
<img width="661" alt="image" src="https://github.com/user-attachments/assets/4e3764bc-cd37-4114-bb07-25f000e1a03f">



## サンプルサイト
- [G'sACADEMY ADAコース ホームページ](https://gsacademy.jp/adacourse/)
- [Google](https://www.google.co.jp/)

## おすすめサイト
- [基本のタグを知れるサイト](https://makusan.ne.jp/html-tag/)
- [CSSセレクタのチートシート](https://webliker.info/css-selector-cheat-sheet/)
- [質問は恥ではないし、役にたつ](https://qiita.com/seki_uk/items/4001423b3cd3db0dada7)
- [質問テンプレート](https://qiita.com/KNR109/items/550b52ff980c0c32bf2a)
- [15分ルールとは](https://rookie-programmer.jp/?p=132)


