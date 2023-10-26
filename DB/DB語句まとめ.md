# DB語句まとめ

## フィールド

行と列が交差する点のこと(行が横、列が縦)

## リレーショナルモデルの構成要素

1. オブジェクト or リレーションの集合
1. リレーションを操作するための演算子のセット
1. 整合性および一貫性のためのデータ整合性

**構成要素ではないもの**

トランザクション管理機能(DBMSの機能)

## SQLの分類

SQL(**S**tructured **Q**uery **L**anguage)大きく分けて四つ存在する。

1. データ操作言語(**D**ata **M**anipulation **L**anguage) : SELECT,INSERT,UPDATE,DELETE
1. データ定義言語(**D**ata **D**efinition **L**anguage) : CREATE TABLE,DROP,RENAME
1. データ制御言語(**D**ata **C**ontrol **L**anguage) : GRANT,REVOKE,COMMIT
1. トランザクション制御 : ROLLBACK,SAVEPOINT

## SQLの標準化について

米国規格協会(ANSI)、世界標準化機構(ISO)等によって標準化
