Japanese-Mobile-Emoji
=====================
/*
 * Copyright (C) 2012  adamrocker (http://adamrocker.com)
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *      http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

＊これは何？
日本のフィーチャーフォン(いわゆるガラケー)使われていた絵文字の文字コードを
プログラムから操作しやすいように纏めたファイル。
データ元のサイトはコチラ → http://unicode.org/~scherer/emoji4unicode/snapshot/full.html

＊何に使うの？
- スマートフォンで絵文字を表示させるとき。
- 絵文字の文字コードは各キャリア(docomo,au,softbank)それぞれで異なるため、キャリアに応じて文字コードを出し分ける。

* 注意点
- 正しい絵文字の文字コードを指定しても絵文字が表示されない事があります。
　これは、この文字コードに対応するグリフ(絵)がフォントに含まれていないためです。
　特に海外系のスマートフォンにはグリフ(絵)が含まれていない事が多いようです。
　絵文字フォント対応機種はコチラが詳しいようです → http://www.justsystems.com/jp/products/atok_android/spec.html

