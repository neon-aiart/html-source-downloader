# 💾 HTML Source Downloader v3.9 ✨

このスクリプトは、現在のWebページのHTMLソースコードを、**文字化けしないUTF-8**で簡単に保存できるUserScriptです。

JavaScriptで直接HTMLソースを取得するのが難しいGmailなどのページ以外は、ほとんどのサイトで大丈夫です。

---

## 🚀 インストール方法

インストールは、**GreasyFork**から行うのが**最も簡単**です。

**下のリンクからインストールしてくださいね！**

**[✨ GreasyForkでインストールする ✨](https://greasyfork.org/ja/scripts/545876)**

1.  **Tampermonkey** または **Violentmonkey** の拡張機能がインストールされているか確認してください。
2.  GreasyForkのページで「インストール」ボタンを押してください。

* **Tampermonkey**: 
    * [Chrome ウェブストア](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    * [Firefox Add-ons](https://addons.mozilla.org/ja/firefox/addon/tampermonkey/)
* **Violentmonkey**: 
    * [Chrome ウェブストア](https://chrome.google.com/webstore/detail/violent-monkey/jinjaccalgkegednnccohejagnlnfdag)
    * [Firefox Add-ons](https://addons.mozilla.org/ja/firefox/addon/violentmonkey/)
---

## 🎀 機能紹介

* キーボードショートカットで、すぐに保存できます！
* 右クリックメニュー（Tampermonkeyのメニュー）からも保存できます。
* ショートカットキーは、設定画面から好きなキーに変更できます。
    * 設定はTampermonkeyのアイコンか右クリックメニューにあります

---

## 💻 技術的な特徴 (UserScript APIの活用)

このスクリプトは、HTMLソースをダウンロードするためのシンプルなブックマークレットをベースにして、以下のUserScript独自のAPIを活用することで、**高い利便性と安定性**を実現しています。

* **カスタムショートカット**: `GM_getValue`/`GM_setValue`を使用して、**ショートカットキーの設定を永続的に保存**できます。フォーム入力中は、キー操作を**自動でスキップ**し、誤作動を防いでいます。
* **動的なUI統合**: `GM_registerMenuCommand`により、右クリックメニューから直接スクリプトを実行でき、**設定したショートカットキー**を動的に表示します。
* **安定性の確保**: サブフレーム（iframeなど）での**二重起動を抑制**し、スクリプトの安定動作を図っています。

---

## 🛡️ ライセンスについて

このスクリプトは、ねおんが著作権を保有しています。

* **ライセンス**: **CC BY-NC 4.0** です。（**LICENSEファイル**をご参照ください。）
* **お願い**: 個人での利用や改変、非営利の範囲内での再配布はOKです。でも、**商用目的での利用はご遠慮ください**。

※ ご利用は自己責任でお願いします。（悪用できるようなものではないですが、念のため！）
