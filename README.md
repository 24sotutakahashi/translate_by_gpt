# 書き出した感情を画像で表現するWEBサービス


# プロダクトの概要：

「自分の感情を整理しやすくなるようなサービスを創りたい」という想いから、3年次の12月に書き出した感情を画像で表現するWEBサービスを開発しました。主にDjangoを用いて開発しました。
 
# 処理の流れの概要
 
①書き出してもらった感情を取得する

↓

②それを朝日新聞APIを用いて要約

↓

③DeepL APIを用いて、要約を英訳

↓

④DALL·E API2を用いて、英訳したものを基に画像を生成

↓

⑤英訳したものと画像を、テンプレート上で表示
# 使用した言語：

Python 

HTML

JavaScript

# 始めた理由

私は小学校低学年の子供たちにプログラミングを教えるアルバイトをしています。そこでの研修で、子供たちが癇癪を起こす一つの原因が、まだ自分の感情を言葉で整理することが難しいことであると知りました。
そして、自分の感情を画像に変換するサービスを作ることで、言語化が難しくても、自分の感情を整理して客観的に見る機会を作れると考え、今回のプロダクトを作ろうと思いました。


# どれくらいの期間をかけたのか？

 どの自然言語処理モデルを使えるかなど、方針から1人で考えたので、今の状態に至るまで1ヶ月程かかりました。
