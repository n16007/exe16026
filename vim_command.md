## vim comannd(1)

### vim normal mode comannd list

1. h -左へカーソルを移動
1. j -下へカーソルを移動	
1. k -上へカーソルを移動
1. l -右へカーソルを移動
1. :q! -変更を保存せずに終了
1. :wq -ファイルに保存、viを終了
1. x -カーソル上にある文字を削除
1. i -インサートモードになり、カーソルの前に文字列の挿入可能
1. I -カーソルの行頭から入力開始
1. a -インサートモードになり、カーソルの後ろに文字列を挿入可能
1. A -カーソル行末から入力開始
1. d -カーソルのある行を消してレジスタに格納　切り取り
1. w -次の単語の先頭に移動
1. e -次の単語の末尾に移動
1. u -元に戻す
1. Ctrl + r -やり直し
1. p -ペースト
1. r -カーソルのある文字を、次にタイプする文字で置き換える
1. c -カーソル位置から行末までを消してインサートモードに移る
1. Ctrl + g -ファイル名、修正の有無、現在の行数などの情報が表示される
1. gg -ファイルの先頭行に移動
1. G -ファイルの最後の先頭に移動
1. / -続けて文字を打ち, Enterで文字列を確定し, 後方検索をかける
1. % -カーソルのある括弧の対括弧に移動する
1. :s/old/new/g　-oldをnewに置き換える

### vim insert/append mode command list

1. esc -インサートモードからコマンドモードに戻る
