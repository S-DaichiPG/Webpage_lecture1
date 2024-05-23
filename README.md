# Webpage_lecture1

### 学習に使わせていただいたもの
①【HTML/CSS】実践！Webサイト作成から公開までの過程を解説！ <br/>

進捗度合い：19:17/2:25:34
https://youtu.be/Hbxulm8iXSA?si=DR2Vmd8DEat85cNJ

### Memo
※今回は「VisualStudioCode」でのWEBサイト作成

<details>
<summary>Memo</summary>

* html:5と入力するひな形が形成される 3:56～

* index.htmlの階層に他形式のファイルを保存するフォルダ(assets)を作成、中身としては[css] [images] [js] [video] など

* cssは形式的には[style.css]、jsは[app.js]など

* サイトの構成しだいではあるが、jsファイルの読み込みを考慮して、bodyタグの終わりに＜script＞は書いた方が良い。 Headタグから読み込みが始まり、それを踏まえてBodyタグの読み込みという順番
6:05あたり～

* cssファイルはサイトの見た目に直結するので、Headタグで呼び出すことが主流

* Googleアナリティクスなどのユーザーがアクセスした際にすぐにjsを実行したい場合は、Headタグの最後尾に記載することも…

* sanitize.css ブラウザの差異を無くすためのcss、style.cssと別にファイルを作成

* cssのlinkは後に書いたものが優先される！ 7:52～

* WEBフォントの設定(web font) GoogleFontsが便利
8:54～ 今回はNoto Sans Japanese

* よく使うフォントのサイズは Regular400, Bold700 10:00～

* font-familyのおすすめ設定(font family) 11:00～
後ろに後述しているものは代替用のフォント

* html5では<section>の中に入れるとh1は実質レベルが1個下がる仕様

* <details> <summary>セクショニング・コンテンツの例</summary> 
    aside, article, navなどのタグが該当する <br/>
    ※＜section＞と同様でh1が実質レベルが1個下がる仕様
</details>

* ＜figure＞ 画像とそれを説明するためのタグ 15:13～

* ＜figcaption＞ 図・画像の説明のテキストを入れておく部分 15:35～

* セクションワンのコンテンツの理解 15:00～

* ダミー用の画像を置けるようなサービス dummyimage.com

* alt属性 表示されなかった場合、代わりにテキストを表示する

* 動画内の17:18～18:05あたりに出てくるショートカットキーや同時選択は何度も練習してみること！

* marginの記載方法について 19:15~
</details>