# サードパーティのライセンス表記

このツールは osu! 公式（ppy Pty Ltd）とは関係のない非公式ツールです。
「osu!」は ppy Pty Ltd の商標です。

## ppy/osu（osu!lazer）・ppy/osu-framework — MIT License

判定の再現（`wwwroot/js/osu/`）、スライダー曲線の計算、スタッキング、リプレイの読み込み、
スキン描画の色計算、ヒットサウンドの選び方などは、osu!lazer / osu-framework のソースコードを
JavaScript / C# に移植したものを含みます。

- https://github.com/ppy/osu
- https://github.com/ppy/osu-framework

```
Copyright (c) 2025 ppy Pty Ltd <contact@ppy.sh>.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## osu-resources（classic スキンの画像・効果音）— CC BY-NC 4.0

スキンに無い要素の補完に、利用者の PC にインストールされている osu!lazer の
`osu.Game.Resources.dll` から classic スキンの素材を実行時に読み込みます。
**素材そのものはこのツールに同梱していません（配布物に含めないでください）。**

- https://github.com/ppy/osu-resources

## Realm .NET — Apache License 2.0

lazer のデータベース（client.realm）を読み取り専用で開くために使用しています。

- https://github.com/realm/realm-dotnet
- Copyright Realm Inc. / MongoDB, Inc.
- ライセンス全文：[licenses/Apache-2.0.txt](licenses/Apache-2.0.txt)

## SharpCompress — MIT License

リプレイ（.osr）の LZMA 展開に使用しています。

- https://github.com/adamhathcock/sharpcompress

```
Copyright (c) 2014 Adam Hathcock

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## .NET（自己完結型で配布する場合に同梱されるランタイム）— MIT License

- https://github.com/dotnet/runtime / https://github.com/dotnet/aspnetcore
