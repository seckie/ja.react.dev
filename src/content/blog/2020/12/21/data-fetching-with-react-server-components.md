---
title: "バンドルサイズゼロの React Server Components の紹介"
---

December 21, 2020 by [Dan Abramov](https://twitter.com/dan_abramov), [Lauren Tan](https://twitter.com/potetotes), [Joseph Savona](https://twitter.com/en_JS), and [Sebastian Markbåge](https://twitter.com/sebmarkbage)

---

<Intro>

2020 年は長い 1 年でした。本年の最後に、我々の研究における特別なホリデーアップデートとして、バンドルサイズゼロで動作する **React サーバコンポーネント**の紹介をしたいと思います。

</Intro>

---

サーバコンポーネントの紹介のためのトークとデモを用意しました。休暇期間中にチェックするもよし、来年仕事に戻ってきた時に見てみるのでもよいでしょう。

<YouTubeIframe src="https://www.youtube.com/embed/TQQPAU21ZUw" />

**React サーバコンポーネントは現在も研究開発中です。**開発の透明性を高め、React コミュニティから初期のフィードバックを頂くために共有しています。そのための時間はまだまだありますので、**今すぐ追いつく必要はありません**！

もし気になったなら以下の順番で見ていくのをお勧めします。

1. **トークを見て** React サーバコンポーネントについて学び、デモを見る

2. **[デモをクローン](http://github.com/reactjs/server-components-demo)**して自分のコンピュータ上で React サーバコンポーネントで遊んでみる

3. 技術的に深い部分について **[RFC を読み（FAQ も最後にあります）](https://github.com/reactjs/rfcs/pull/188)**、フィードバックを送る

RFC や Twitter の [@reactjs](https://twitter.com/reactjs) へのリプライで、皆さんの意見を聞けるのを楽しみにしています。それでは良い休暇を！ また来年お元気でお会いしましょう！
