幸せok改造インスタンス
 <h3>このリポジトリはvercel、render、codesandboxのデプロイに対応しています</h3>
render以外でデプロイした場合は掲示板機能は使えません
<br><br>
とりあえずインビのインスタンス置いとく<br>
https://docs.invidious.io/instances/<br>
https://invidious.namazso.eu/<br>
偽装ページが違うやつ  
ブログをブロックされるとき用  
ASGIで動く  
deployボタンは追加していく予定です  
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  
画像は使えません。  
cookieにyuki=Trueを設定すると認証されます。  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  

Renderを使用する場合の手順  
1~4の作業をやらないと、自動でURLがyuki-tangolevel-[4桁の英数字].onrender.comになります。  
1.githubアカウントを作成する  
2.リポジトリを作る(名前はなんでもいい)(プライベートリポジトリにすることをおすすめします)  
3.import codeを押して https://github.com/mochidukiyukimi/Yuki-Youtube-slim/ と入力  
4.render.yamlを開いて編集(鉛筆のマーク)を押し、nameの横のyuki-youtube-slimをサイトのurlの最初の部分にしたい文字列に変更する。(yuki-yだったらurlはhttps://yuki-y.onrender.comになる)  
5.Deploy to renderボタンを押し、Service Group Nameに適当な文字列を入れてapply(事前にrenderのアカウントを作っておく)<br>
<p>デプロイ</p>
<a href="https://render.com/deploy?repo=https://github.com/siawaseok3/slim-2-by-siawaseok.git&branch=偽造ページなし">
 <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
<br>
  
[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&builder=buildpack&repository=github.com/siawaseok3/slim-2-by-siawaseok&branch=偽造ページなし&name=slim-2-by-siawaseok)
<br>
<a href="https://vercel.com/new/clone?repository-url=https://github.com/siawaseok3/slim-2-by-siawaseok.git&branch=偽造ページなし">
  <img src="https://vercel.com/button" alt="Deploy to Vercel">
</a>
<br>