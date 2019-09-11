# keiya0017.github.io
＜使用言語＞
HTML5, CSS3

＜工夫した点＞
・ページ内ジャンプを行ったとき、固定してあるナビが各セクションの文字を隠してしまわないようにしました。         
・tableタグで自分のスキルをわかりやすくまとめました。


ページ内ジャンプ後の問題を解決
HTML5)
<h1 class="section-title" id="profile">PROFILE</h1>

CSS3)
#profile,#skill,#works,#contact{
  margin-top: -70px;
  padding-top: 70px;
}
