# [gecko/dom/](http://mxr.mozilla.org/mozilla-b2g28_v1_3/source/dom/)

# 概要

*   DOM APIの定義がいろいろ入っているディレクトリ
*   base配下にwindowやnavigatorが入っているのでDOM APIの中身を読むときには割と入口としてよく見る
*   各ディレクトリの役割は各ディレクトリの概要参照

# 主な言語

*   idl
*   C/C++
*   python
*   JavaScript
*   XULもあるかも？

# 読み方のヒント

*   とりあえず知りたいAPIのwebidlを見る
    *   webidlに書いてあるAPI名でgrepしてみる
        *   実装側のC++ではAPI名が大文字で始まってることが多いのでgrepするときに頭文字を大文字にしてみるのもいいかも
        *   JSで実装されているときは頭文字小文字なので頭文字小文字も検索いるかも
    *   webidlがなければXPIDLで定義されているので目的のメソッドを含んだidlファイルを探す
        *   たぶん同じディレクトリに実装のcpp/hかjsかjsmがある


