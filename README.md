# wptool

## genslugutf8-japanese-also.php

PHP script generate WordPress article title (slug , page_name ) in UTF-8 to percent-encoding　

WP 特有のスラッグ(page_name)を日本語の記事タイトルから、パーセンテージエンコーディングして、生成する部分をとりだして、独立して動くようにしたPHPスクリプト。

・WPの機能を再現
・日本語をURLにも使えるようにパーセンテージエンコーディング
・適当に文字数を切り詰め
・その他、半角「(」など、URLにそぐわない文字列も自動変換・削除
