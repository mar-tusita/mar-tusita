がが

- [GitHub Gist](https://gist.github.com/mar-tusita)を使い始めました。
  - [LaTeXコンパイル&出来上がったPDFファイルをGitHub Releasesに置くためのworkflow](https://gist.github.com/mar-tusita/a35deeef90bb7c6f031a7322607ecd21)を試しに書いてみたんですが、TeX Live環境のimageを引っ張ってくるところから始まるので、正直遅くて泣くのがわかってしまいました（最低でも2分程度かかる）。他人の環境でもコンパイルできる、のを確認するテスト環境だと思うと案外優秀かもしれず。
  - それなら[TeX Liveを自力でインストールしてcacheにおいておけばいいんじゃねえの？](https://gist.github.com/mar-tusita/82f9d64da9dab52f9c4723a9db7c0a45)と思ってやってみたら、最初のinstall-tlが遅いのは一旦みなかったことにしても（40～50分かかる）、とっておいたcacheから復元してもやっぱり2分位かかるし、たまたまcacheからの読み込みが遅いと5分くらいかかって意味なし（imageとってくる時間は比較的安定してる）。世の中は概ね正しい、はやはり成立するようで、だったらimageとってきたらいいじゃん、という結論に。
- [scholist](https://github.com/mar-tusita/scholist)は現状alpha release位、最低限変なことが起きずに使えるくらいにはなっている、はず。FeaturesというよりはUXまわりが全然鍛えられてないので、そのへんが現状の課題（JSONファイルを人間が書く、のはなんとかしたいけど、さてどうしましょう）。
- 勢いで、IPSJ/IEICEのLaTeXスタイルファイルを使ったテンプレートリポジトリを作りました（すでにたくさんありそうですが、多分使えるlatexmkrcがおいてあるのがメリットかもしれない）。
  - [IPSJ LaTeXスタイルファイル v4.1 テンプレート latexmkrcつき (Works with TeX Live 2026)](https://github.com/mar-tusita/ipsj-platex)
  - [IEICE 和文論文執筆用スタイルファイル v3.4b テンプレート latexmkrcつき (Works with TeX Live 2026)](https://github.com/mar-tusita/ieicej-platex)
  - [IEICE 英文論文執筆用スタイルファイル v2.3 テンプレート latexmkrcつき (Works with TeX Live 2026)](https://github.com/mar-tusita/ieice-platex)
  - [IPSJ Journal 向け LuaTeX クラスファイルのテンプレート latexmkrcつき](https://github.com/mar-tusita/ipsj-luatex)
    - <https://github.com/attgm/ipsj-luatex>を単にテンプレートにしただけ

<!--
### Hi there 👋

**mar-tusita/mar-tusita** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
