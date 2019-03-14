# Tips
## function
### date
- http://php.net/manual/en/function.date.php
- string型かfalseを返す
- date('Y-m-d H:i:s') → '2019-03-10 08:38:24'

## composer
### if log says class does not exist
- check spells in your composer.json
- write "require 'vendor/autoload.php';" in your php script

## error
### 「Cannot use temporary expression in write context」
- pdoのbindParamメソッドの第二引数が参照渡しで、そこに定数を渡したためエラーになった
