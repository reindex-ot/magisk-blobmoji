# Magisk BlobmojiってどういうMagiskモジュールなのよ!?

[Magisk](https://github.com/topjohnwu/Magisk)で[Noto Emoji フォント(Blobmoji)](https://github.com/C1710/blobmoji) (スライムくんな絵文字のアレ)に変更するMagiskモジュールです。
本家側が「フォントの更新をやってないっぽい」ので勝手なのですが作った...というか差し替えました。

このモジュールは単純に`/system/fonts/NotoColorEmoji.ttf`を変更する事で絵文字フォントを変更しています。
もしかしたら他のモジュールと競合をしたり、うまく有効にならない可能性があります。

##既知の問題
MIUI13、OxygenOS12(多分ColorOSも)で絵文字が上手く反映しない。

## ダウンロード

[GitHub releases](https://github.com/reindex-ot/magisk-blobmoji/releases) からどうぞ。
