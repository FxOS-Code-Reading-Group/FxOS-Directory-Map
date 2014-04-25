# [gecko/dom/webidl/](http://mxr.mozilla.org/mozilla-b2g28_v1_3/source/dom/webidl/)

# 概要

*   DOMのインターフェイス定義置き場


# 主な言語

*   webidl
    *   http://www.hcn.zaq.ne.jp/\_\_\_/WEB/WebIDL-ja.html
    *   http://www.w3.org/TR/WebIDL/


# 読み方のヒント

*   メソッドの宣言は属性に注目しましょう。
*   gecko/dom/bindingsにwebidlのパーサがあって結果がobjdir-gecko/dom/bindingsに出力されるので<目的のオブジェクト>Bindings.cpp/.hを読みましょう。
*   実装コードはいろいろ散らばっているので頑張って探しましょう。大体以下の感じ。
    *   gecko/dom/base
        *   global.window
        *   global.window.navigator

