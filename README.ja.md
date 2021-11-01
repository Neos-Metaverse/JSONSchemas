# JSONSchemas

生成されたNeos JSONスキーマの公開リポジトリです。

## JSONスキーマとは？

JSONスキーマは、JSONファイルのレイアウトやスキーマを記述したファイルです。コードの生成やJSONの検証などに利用できます。

## なぜこれがここにあるのか？

ヘッドレスの設定ファイルやNeosクライアントのジェネレータファイルを作成する際に、何ができるのかわからないことがあります。これらのファイルはこの問題を解決するために設計されています :)

## どうやって使うの？

VS Codeを使ってJSONファイルを編集することをお勧めします、そうすれば自動的に編集されます。 詳しくは[VSCodeで公開されている説明](https://code.visualstudio.com/Docs/languages/json#_json-schemas-and-settings)をご覧ください。日本語向けの説明は[こちら](https://qiita.com/uzuna/items/3f8ae7775b2136fffc7f)。他にも使用できるツールはありますが、私たちはこれらで様々な成功を収めています。JSON Schemaのウェブサイトには[ツールの一覧](https://json-schema.org/implementations.html)があります。

ひとまずサンプルを sample 以下に保存しました。簡易的に使用するのであればそれらを.vscodeフォルダ(なければ作成)内にコピーしていただければ使用できます。

## どのようなスキーマがあるのでしょうか？

- NeosConfig.schema.json -　[Headlessの設定向けのものです](https://wiki.neos.com/Headless_Client/Configuration_File/ja)。 英語版は[こちら](https://wiki.neos.com/Headless_Client/Configuration_File)
- Config.schema.json - [Neosクライアントの設定向けのものです](https://wiki.neos.com/Startup_Config_File/ja)。英語版は[こちら](https://wiki.neos.com/Startup_Config_File)

## どこで記法など、詳細を知ることができますか？

公式[JSON Schemaウェブサイト](https://json-schema.org/)に向かうことで詳細を確認できます!

## なぜDraft-04スキーマを使っているのですか？

私たちの[JSON Schema generator](https://github.com/RicoSuter/NJsonSchema)は、現在[draft-04](https://github.com/RicoSuter/NJsonSchema/issues/574)しかサポートしていません。06/07のサポートに向けてご協力をお願いします :)

## なぜ日本語版を公開しているの？

日本語で確認したいじゃん(･ω･
