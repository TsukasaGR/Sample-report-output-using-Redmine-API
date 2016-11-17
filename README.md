# Sample-report-output-using-Redmine-API
Sample report output using Redmine API  - RedmineAPIを使った帳票出力サンプル

## 何をする為？
- RedmineAPIを使って、RedmineだけじゃどうにもならないレポートとかをHTMLでゴリゴリ書く為のサンプル

## どうやって使う？
- 使いたいRedmineは *RESTによるWebサービスを有効にする* と *JSONPを有効にする* のどちらも有効にしておいて下さい
- 92-94行目の変数には対象のRedmine情報に書き換えて下さい
- 148行目にあるcreateDom関数の中をいじってもらえればテーブルの中身とかを変更出来ます
- Redmineのデータの中身を見たい時は166行目あたりでブラウザのデバッグをして、 *issues[i]* の中身を見てもらえれば大丈夫です
- CSSはBootstrapをベースにしてるので、CSSを変更する際はお忘れなく