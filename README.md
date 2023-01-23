# 書き出した感情を画像で表現するWEBサービス（GPT-3 APIを使ったバージョン）


# プロダクトの概要：

以前に、感情を画像で表現するWEBサービスを作りました。そのサービスでは、朝日新聞APIを使って感情を要約し、DeePL APIを使って要約結果を英訳していました。今回のプロダクトは、これらのAPIの代わりにGPT-3 APIを使用して制作したプロダクトです
 
# 始めた理由：
以前、感情を画像で表現するWEBサービスを作成しました。そのサービスでは、朝日新聞APIを使用して感情を要約しましたが、朝日新聞の記事を主な学習データとしていたため、感情の要約には不適切だと思ったので、要約の質を向上させるためにGPT-3 APIを使用することを考えました。さらに、GPT-3 APIで英訳もできるので、DeePL APIで行っていた機能もGPT-3 APIで置き換えました。

# 使用した言語：
Python

# 開発人数：
1人

# 開発期間：
3日

# 開発秘話：
寝る前に軽い気持ちで「GPT-3 APIの出力結果に、予期しない改行が挿入されている場合の対処法」という記事を投稿しました。朝起きたら、200人以上の方に見てもらっていて、驚きました。
 
# 頑張った・工夫した所
①朝日新聞APIの代わりにGPT-3 APIを使用した所です。

　朝日新聞APIを使用していた部分を、GPT-3 APIに置き換える必要があったからです。また、GPT-3 APIをPythonに組み込むことにも大変でした。

②GPT-3 APIをPythonで呼び出す方法を、記事としてまとめてQittaに公開したところ。

　以前使用していた朝日新聞APIをGPT-APIに置き換えるときに、日本語での検索ではわかりやすい情報が得られず、英語の動画が一番わかりやすかったです。GPT-3 APIを使って作れるサービスの可能性を感じている事に加え、GPT-3 APIをPythonで呼び出す方法に困っている人が他にもいると思いました。そのため、今回学んだ内容を日本語で解説することを考えました。
　記事のリンクは、以下の通りです。
 
【Django技】formの内容にオリジナルの命令を自動追加して、GPT-3 APIを呼び出す方法！:
　https://qiita.com/komeda_coffee_24_sotu/items/05eabb25b8b937962ca4
 
 またこのサービスを作る中でGPT-3 APIの出力結果について悩んだことがあったので、以下のような記事もQittaに投稿しました。
 
 ①GPT-3 APIの出力結果に、予期しない改行が挿入されている場合の対処法:
 
 https://qiita.com/komeda_coffee_24_sotu/items/824715aba1e3f19c72b7
 
 ②Pythonで文字列から、日本語だけを消す方法:
 
 https://qiita.com/komeda_coffee_24_sotu/items/e1601ca8ccc7e05468a4
