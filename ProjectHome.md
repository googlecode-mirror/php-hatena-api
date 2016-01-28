はてなウェブサービス(はてなAPI）を簡単に使うためのPHPクラスの開発。
## 【使い方のサンプル】 ##
```
<?php
require_once('HTTP/Request.php');
require_once('cHatenaApi.inc');

$sUsername = "YourUserName";
$sPassowrd = "YourPa$$Word";

$oHatena = new cHatenaApi($sUsername,$sPassword);

//はてなブックマークを取得
$aMyBookmark = $oHatena->getBookmark();

?>
```
※簡易ドキュメントやスクリプトのダウンロードは、上記の[Wikiタブ](Docs.md)から。