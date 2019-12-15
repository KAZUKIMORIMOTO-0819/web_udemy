# HTML 
## フォーム
- ユーザがWebページからデータサーバに送信するためのもの
- Twitter のログインフォームなど

### フォームタグ
＜form action="#" method="post"＞＜/form＞
- action どこにデータを送信するか。送信された情報を処理するプログランのURL(サーバサイド、Rubyなどで記述)
- method フォームを送信する際にブラウザーが使用するHTTPリクエストメソッド（get, post）   
\'''   
＜form action="#" method="post"＞     
    ＜input type="text" name="username" placeholder="ユーザーネーム"＞    
    ＜input type="password name="password" plaeholder="パスワード＞      
    ＜input type="submit" value="ログイン"＞     
＜/form＞    
\'''


### いろいろなフォーム部品
- ＜input type="text" name="usename"＞
- ＜input type="email" name="email"＞
- プルダウン    
\"""     
＜select name=""＞      
＜option value="" selected＞選択してください＜\option＞     
＜option value="hokkaido"＞北海道＜\option＞     
＜option value="touhoku"＞東北＜\option＞      
＜\select＞
\"""    

- ラジオボタン    
\"""
＜input type="radio" name"gender" value="male" checked＞男性          
＜input type="radio" name"gender" value="male"＞女性       
\"""     

- テキストエリア     
\"""     
＜textarea name="contents"＞＜\textarea＞     
\"""    

- チェックボックス     
\"""
＜input type="checkbox" name="privacy", value="1"＞同意する＜\input＞


### フォームバリデーション
- 入力された内容が要件を満たしているか、妥当性を確認すること    
\"""     
＜form action="#" method="post"＞     
＜label for="username"＞名前を入力してください＜\label＞      
＜input id="username" name="username" required＞    
＜input type="submit" value="送信"＞　　　　
＜\form＞
\"""    








