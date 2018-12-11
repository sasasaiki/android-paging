# android-paging
Code for the Paging Codelab: https://codelabs.developers.google.com/codelabs/android-paging/

フォークして実際にAndroidPagingCodelabを進めていきます。（codelabブランチ）

下記二つの問題点がPagingを使うことで解決できます

* The entire repo table of the database is loaded at once.

  データベースから全てのデータが一度にロードされてしまう（表示する分だけロードしたい）
  
* The entire list of results from the database is kept in memory.

  データベースから読み込んだ全てのデータのリストがメモリにのってしまう。
