# 概要
画像投稿ができるタイプのSNSを自作しようとしているので、そのためのサイトのサンプルを作成して置いておくためのレポジトリーです。  
サービスのメインはiOSとAndroidのアプリで作成し、一部の投稿詳細画面やログイン周りの仕組みはちゃんとサイトの画面を用意する予定です。  
DBなどの細かいところはLaravel編で参加している最中に勉強しながら作れたらと思っているので、今のところはhtmlとcssなどの事前学習の延長の部分にだけフォーカスして進める。

# HTML&CSSを勉強するにあたって使っている環境
MacにVSCodeを入れてHTMLとCSSを書いている

## 拡張プラグイン
- `HTML CSS Support`
- `HTML Preview`
- `HTML Format`
- `CSS Format`

# 実際にやった学習サイト

----- Laravel編 -----
- HTML & CSS 初級編
  https://prog-8.com/lessons/html/study/1
- PHP I
  https://prog-8.com/lessons/php/study/1
- Git Ⅰ
  https://prog-8.com/lessons/git/study/1
- Command Line 基礎編
  https://prog-8.com/lessons/commandline/study/1
  
*追加で行った場合はここを更新

# 参考にしたサイト

- HTMLの雛形をコピペしてきた  
https://web-camp.io/magazine/archives/27870

- 上のサイトでヘッダータグとフッタータグの存在を知ったので調べた  
https://web-camp.io/magazine/archives/27870

- headerとnaviの差がよく分からなかったので調べた  
https://shu-naka-blog.com/html/tag01/#nav
headerの中にnaviを入れている、自分の解釈的にはこれに近いためこの方針で進める？  
-> `<ul>`と`<li>`で事足りる気がしたのでやっぱり使わない
  
- 均等に横一列に要素を並べるにはどうしたらいいのか -> display:flex, display:tableを見つけた  
https://hsmt-web.com/blog/css-side-by-side/#p1-1  
https://gray-code.com/html_css/making-side-by-side-menu/  
`px`の指定だけではなく`%`で指定する方法がある  
ヘッダーのメニューを右半分に50%の幅で表示したいのでdisplay:flex, display:tableを併用して実現させてみる
  
- なぜかbodyに隙間ができると思ったら、デフォルトCSSなるものでbodyに対してmarginがついていたらしい
http://ideahacker.net/2015/08/21/10357/

- ヘッダーとかフッダーは使いまわせないのか？  
https://www.itra.co.jp/webmedia/include.html  
https://webukatu.com/wordpress/blog/9075/  
HTML単体でどうこうするというよりかはJSとかPHPとかで共通化するっぽく見える  
今はまだ問題になっていないので後回しにする。

- オリジナルでごにょごにょいじる前にFlexboxのレイアウトを勉強した方が良さそう
https://qiita.com/takanorip/items/a51989312160530d89a1

- aタグの下線を消す方法  
https://web-camp.io/magazine/archives/82438  

- imgに丸いマスクをかけてTwitterのユーザーアイコンっぽくしたい  
https://www.nishishi.com/css/trim-image-to-circle.html  