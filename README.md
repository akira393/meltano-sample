
## setup
基本的には、以下のサイト通りいけた
> https://dev.classmethod.jp/articles/meltano-slack-to-bq/#toc-13
補足として、
- meltano uiで設定が可能らしい

## result

<div align="center">
<img src="img/スクリーンショット 2021-10-15 11.30.32.png" alt="属性" title="タイトル">
</div>


## tips

トークンは、
- アプリを作成し
- User OAuth Tokenにたいして適切なスコープを付与
- tokenを作成する

<br>
botの方のトークンだとメッセージ一覧が取得（0件）できなかった？userの方に変えたら行けた
botのトークンだと自分の発言をとる仕様なのかな？