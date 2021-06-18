# Blackjack

コンソール上で動作するブラックジャックです。Javaで作成しました。
<br>ゲームのルールや基本的な流れはこのページを参考にしています。
<br>https://slotsia.com/ja/game-blackjack/basic-guide

## How to play

1. Blackjack.javaをコンパイル後、Blackjackを実行します(日本語でコメントを打っているのでエンコードが必要です)
2. 「choose how many coins you bet」という表示が出るので賭けるコイン数を入力します
3. ディーラーのカード(1枚目のみ公開)、自分のカード、自分の手札の数値、所持コイン、賭けたコインが表示されます
4. 「hit or set?(h/s)」と聞かれるのでどちらかを入力し選択してください 
5. hitを選ぶともう一枚カードを引き3.に戻ります
6. setを選ぶとディーラーがカードを引き始め、ディーラーの手札の数値が17を超えるとsetします
7. 手札が公開され、勝敗とともにコインの増減が表示されます
8. 「Do you continue?(y/n)」と表示されるのでもう一度ゲームをする場合はy、やめる場合はnを入力してください

## 環境
JDK 15