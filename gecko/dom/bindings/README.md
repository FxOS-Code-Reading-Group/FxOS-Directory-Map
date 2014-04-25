# [gecko/dom/bindings/](http://mxr.mozilla.org/mozilla-b2g28_v1_3/source/dom/bindings/)

# 概要

*   gecko/dom/webidl配下のwebidlファイルからグルーコードを生成するスクリプト置き場
*   Firefox OSに関していうとobjdir-gecko/dom/bindingsに生成結果が置かれる


# 主な言語

*   python
*   C++


# 読み方のヒント

*   webidlからAPIの実装の流れを追う時に<API名>Bindings.cpp/.hを読む
*   基本的にはAPIへの転送関数になっているので実際につながっている関数を確認するぐらいしか用事がない
    *   それもwebidlをちゃんと読めば基本的にわかる
*   特殊なバインドをするAPIについてはBindings.confに記述があるので設定を読む
    *   https://developer.mozilla.org/en-US/docs/Mozilla/WebIDL_bindings

