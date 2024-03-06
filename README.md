# Task5-HTTPにまわる用語

**<details><summary>URLとは</summary>**

- Uniform Resource Locator
- インターネット上のWEBサイトやファイルの位置や情報を示すもの
  - プロトコル：セキュリティのため、暗号化されたhttpsを利用する
  - ホスト名：wwwの有無はSEOに対して影響がない
  - ドメイン：ある程度自分で選択可能だが、誤解を招くかも
  
  
    例えば、末尾は`[co.jp]`,`[com.us]`の場合、それぞれ日本向けとUSA向けサービスを提供しているサイトであるという認識されているため、なるべく意図に関係しているアルファベットを選ぶ
  - ディレクトリ：サーバーでファイルを格納するためのフォルダ
    ![image](https://github.com/Ouichi/Task5/assets/140411621/6ce47a96-8736-439c-ad0b-ba43b824acf5)

</details>

**<details><summary>クエリ文字列（Query Parameter）</summary>**

- サーバーに情報を送るためにURLの末尾に付足す変数のこと


  https://*OXOX*.jp　➡　https://*OXOX*.jp/**`?A=B×C`**
- 2種類あり、それぞれ用途が異なる
  -  パッシブパラメータ
    - 表示するコンテンツに影響はない
    - WEBサイトのアクセス解析するため（どこからたどり着いた）
  - アクティブパラメータ
    - 表示されるコンテンツに影響する
    - 例えば、Sサイズをフィルタリングした商品一覧ページ
   
    
      https://*OXOX*.jp/tshirt　➡　https://*OXOX*.jp/tshirt/**`?t=shirt_size=s`**

</details>

**<details><summary>パス変数（Path Parameter）</summary>**

- 動的な値をパスを一部として指定することがパスパラメータ
- 例：http://*www*.example.com/user/12345


  ここで12345の部分がユーザーIDなどを表す変数となっている
- 特徴
  - URLパスに埋め込むので、読み取りが簡単
  - GETリクエストで主で利用される
  - データの取得や測定リソースの操作に利用される
  - 変更がまれないので、キャッシュしやすい

</details>

**<details><summary>クエリ文字列とパス変数の違い</summary>**

- クエリ文字列：特定のリソースを操作し取得する際に必要な情報を入れる
- パス変数：測定のリソースを識別するために必要な情報を入れる

  https://*example*.com/pathparameter/`{pathparameter}`?`queryparameter1=hogehoge&queryparameter2=fugafuga`

  
  1. ドメインの後、？の前にくるのがパスパラメータ
  1. ？の後ろに来るのがクエリパラメータ
  

</details>

**<details><summary>HTTPメソッド</summary>**

- GET：

  指定したリソースの表現をリクエストする。GETを使用するリクエストはデータの取り込みに限る
- POST：

  指定したリソースに実体を送信するために使用され、サーバー上の状態を変更したり、副作用が発生する
- PUT:

  対象リソースの現在の表現全体をリクエストのペイロードで置き換える
- PATCH：

  リソースを部分的に変更するために使用する
- DELETE：

  指定したリソースを削除する
  

</details>

**<details><summary>リクエストヘッダー</summary>**

  WEBコンテンツの伝送に用いられるHTTPで、クライアントからサーバへの要求であるHTTPリクエストの前半にある制御情報を記した領域のこと

</details>

**<details><summary>リクエストヘッダー</summary>**



</details>
