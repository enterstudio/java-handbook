# maven central

maven central というのが事実上の標準となっている、ライブラリ置き場です。
ほとんどのまともなライブラリはここにアップされています。
(ごく一部、巨大なプロジェクトは自前のレポジトリを管理しています）

弊社では、nexus enterprise を運用して、maven central の repository の内容をミラーしています。
(社内用のライブラリもそこにアップされています)

maven central は不安定だったり、誰かが急に古いバージョン消したりするかもしれないので、Java 対応企業は各社それぞれ、社内ミラーを作るのが普通とのことです。

## search.maven.org

http://search.maven.org/

基本的にはここが一番基本となる検索サイトです。得に使いやすくはありませんが、まあ普通です。

API もあります。

## mvnrepository

https://mvnrepository.com/

個人が運用している maven repo 検索サイトです。こっちのほうが使いやすいですが、新しいモジュールの反映は遅いです(数日ぐらい遅れてる気がします）。
