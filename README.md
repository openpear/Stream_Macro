Stream_Macro
============

PHPにマクロ機能を付加します。
  マクロ未使用時
  include \"hoge.php\";

  マクロ使用時
  $opts = array();
  $opts['debug'] = true;
  Stream_Macro::registByArray('macro', $opts);
  include \"macro://..

## License
BSD License