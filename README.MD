
# HELLO.COM -- Greetings to the world

> [!NOTE]
> This file is encoded in CP932 a.k.a. Shift_JIS.  
> このファイルはシフトＪＩＳでエンコードされています。

## 開発環境の用意

まずはなんとかして MS-DOS を得てください。
古い Windows（Windows 10 未満）を利用して「起動ディスク」を作成することで
MS-DOS 8.0 を得ることもできます。

開発に必要なプログラムは以下の通りです。

- 適当なエディタ（マゾヒストは `COPY CON ` でも OK）
- アセンブラ（MASM）
- リンカ（LINK）
- EXE2BIN
- 手に入れば MAKE

これらのソフトウェアは [microsoft/MS-DOS][MS-DOS] から入手できます。
マイクロソフトに感謝しましょう。
必要なファイルは `MS-DOS/v2.0/bin/` にあります。

[MS-DOS]: https://github.com/microsoft/MS-DOS

### MAKE が手に入らない場合

**HELLO.MAK** のレシピ行を実行してください。
怠惰な人間はバッチファイルを作ると快適に過ごせます。

## ライセンス

BSD-2-CLAUSE
