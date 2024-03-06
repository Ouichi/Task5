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

**<details><summary>クエリ文字列</summary>**

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


