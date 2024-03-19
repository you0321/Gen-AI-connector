Japanese:
1. XMLファイルをServiceNowにインポートして追加されるUpdate setをコミットしてください。
2. Gen AI connect profile（u_gen_ai_connect_profile）テーブルが追加されるのでREST API用のプロファイルを作成してください。
3. スクリプトで以下のサンプルコードを実行すると生成系AIと連携できます。

サンプルコード : new GenAIconnector("プロファイル名").chat("プロンプト")

English(By google translate):
1. Import the XML file into ServiceNow and commit the update set that will be added.
2. Gen AI connect profile (u_gen_ai_connect_profile) table will be added, so please create a profile for REST API.
3. You can link with the generation AI by running the sample code below in a script.

sample code : new GenAIconnector("profile name").chat("prompt")
