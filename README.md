# WoTデモンストレーション （第4回 WoT-JP CG イベント (3/25)）

### 「スマートホーム+ スマート農業をイメージしたダッシュボード/ GitHub or twitter 連携」

3月25日開催の[第4回 WoT-JP CG イベント](https://wot-jp-cg.connpass.com/event/242456/)における
WoTデモンストレーション「スマートホーム+ スマート農業をイメージしたダッシュボード/ GitHub, twitter 連携」の説明ページです。

## 概要

コメントをボットが読み取ってデモ環境の Node-Red を介して様々なメーカーの各 IoT デバイスを操作します。皆さん自由にコメントを書き込んでいってください。

## 操作方法

Twitter, GitHub, (Slack)のいずれかで、デバイス一覧より場所とデバイス名、語彙を選択し、  
「`場所`＋`デバイス名`＋`語彙`」を含めた文章を投稿すると、デバイスの操作・状態の取得を行うことができます。

### ・Twitter
`#wotbotdemo`のハッシュタグを付けて投稿することで、デバイスの状態を取得・操作することができます。  
返答は、[@WoTbotdemo](https://twitter.com/WoTbotdemo) アカウントにてメンション付きで返答が行われます。

### ・GitHub

<https://github.com/webdino/wot-bot-demo/issues>  
こちらのissueにコメントすることでデバイスの操作をすることができます。  
**なお、GitHubからの投稿に対する、デバイスの状態や操作完了の返答はありません。**  
そのため、デバイスの操作を主に体験することができます。

### (・Slack)
**既にWoT検討会のSlackに参加している方のみとなります。**  
`#wot-bot-demo` チャンネルで文章を投稿をするとデバイスの状態を取得・操作することができます。


## デバイス一覧

### 部屋

例1) 部屋の電気をオンにして！  
例2) 部屋のカーテンの状態を教えてほしい。

<table>
  <tr>
    <th>デバイス名</th> <th>語彙</th> <th>説明</th>
  </tr>
  <tr>
    <td rowspan="2">電気・ライト・照明</td> <td>オン・付ける / オフ・消す</td> <td>電球のオン・オフを操作</td>
  </tr>
  <tr>
    <td>状態</td> <td>電球の状態を返答</td>
  </tr>
  <tr>
    <td rowspan="2">カーテン</td> <td>開ける / 閉める</td> <td>カーテンの開閉を操作</td>
  </tr>
  <tr>
    <td>状態</td> <td>カーテンの開閉状態を返答</td>
  </tr>
  <tr>
    <td rowspan="3">加湿器</td> <td>オン / オフ</td> <td>加湿器のオン・オフを操作</td>
  </tr>
  <tr>
    <td>赤 / 青 / 緑</td> <td>加湿器の色を操作</td>
  </tr>
  <tr>
    <td>状態</td> <td>加湿器の状態を返答</td>
  </tr>
  <tr>
    <td>コーヒーメーカー</td><td>オン</td> <td>コーヒーメーカーをオンに操作</td>
  </tr>
  <tr>
    <td colspan="2">温度</td> <td>温度を返答</td>
  </tr>
  <tr>
    <td colspan="2">湿度</td> <td>湿度を返答</td>
  </tr>
</table>

### ビニールハウス１

例) ビニールハウス１のドア閉めたっけ？

<table>
  <tr>
    <th>デバイス名</th> <th>語彙</th> <th>説明</th>
  </tr>
  <tr>
    <td rowspan="2">電気・ライト・照明</td> <td>オン・付ける / オフ・消す</td> <td>電球のオン・オフを操作</td>
  </tr>
  <tr>
    <td>状態</td> <td>電球の状態を返答</td>
  </tr>
  <tr>
    <td colspan="2">温度</td> <td>温度を返答</td>
  </tr>
  <tr>
    <td colspan="2">湿度</td> <td>湿度を返答</td>
  </tr>
  <tr>
    <td colspan="2">気圧</td> <td>気圧を返答</td>
  </tr>
  <tr>
    <td colspan="2">人感・動(き)・動体</td> <td>人感センサーの状態を返答</td>
  </tr>
  <tr>
    <td colspan="2">ドア・開閉</td> <td>開閉センサーの状態を返答</td>
  </tr>
  <tr>
    <td colspan="2">ロボット</td> <td>ロボットをビニールハウス１の方向に操作</td>
  </tr>
</table>

### ビニールハウス２

例) ビニールハウス２で何か動いてる？

<table>
  <tr>
    <th>デバイス名</th> <th>語彙</th> <th>説明</th>
  </tr>
  <tr>
    <td rowspan="2">電気・ライト・照明</td> <td>オン・付ける / オフ・消す</td> <td>電球のオン・オフを操作</td>
  </tr>
  <tr>
    <td>状態</td> <td>電球の状態を返答</td>
  </tr>
  <tr>
    <td colspan="2">温度</td> <td>温度を返答</td>
  </tr>
  <tr>
    <td colspan="2">湿度</td> <td>湿度を返答</td>
  </tr>
  <tr>
    <td colspan="2">気圧</td> <td>気圧を返答</td>
  </tr>
  <tr>
    <td colspan="2">人感・動(き)・動体</td> <td>人感センサーの状態を返答</td>
  </tr>
  <tr>
    <td colspan="2">ドア・開閉</td> <td>開閉センサーの状態を返答</td>
  </tr>
  <tr>
    <td colspan="2">ロボット</td> <td>ロボットをビニールハウス２の方向に操作</td>
  </tr>
</table>
