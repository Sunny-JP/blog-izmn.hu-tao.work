---
title: 'サンプル'
date: 2024-09-13T18:26:35+09:00
tags:
- sample1
- sample2
description: ""
weight: # 1 means pin the article, sort articles according to this number
draft: true # draft or not
showToc: true # show contents
TocOpen: false # open contents automantically
hidemeta: false # hide information (author, create date, etc.)
disableShare: true	# do not show share button
showbreadcrumbs: true # show current path
cover:
    image: ""
    caption: ""
    alt: ""
    relative: false
---

    hugo server --cleanDestinationDir

# Sample Page
## 1. はじめに
　windowsでコンピューターの世界が広がります。1234567890  
　あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市、郊外のぎらぎらひかる草の波。  
―――宮沢賢治『ポラーノの広場』より―――

## 2. Markdown CheetSheet

### Text Format

後ろにスペース2つで  
改行

*Italic（斜体）*  
**Emphasis（強調）**  
~~Strikethrough（取り消し線）~~  
This is `inline`.

    ←タブを空けてコードブロック
    [hoge](https://hoge.com)

### List
- text
    - test
    - test
1. 1番目
    1. 3番目
1. 2番目
    1. 1つ目
    1. 2つ目
        1. 3番目
    1. 3番目

### Horizontal rules
***

### 引用
> This is Blockquotes
>> This is Blockquotes
>>> This is Blockquotes

### 参照
:link:[リンク](https://www.sunsun.earth/ "リンクだよ")です

### ショートコード
#### ダウンロードリンク
こちらから{{< download url="./01.png" filename="サンプルファイル"/>}}をDL :link:[参考](https://isqua.github.io/hugo-shortcodes/links/dowload/)
#### Instagram
{{< instagram C988Njpq-7g >}}
#### Twitter
{{< twitter user="Genshin_7" id="1812698888756928931" >}}
#### YouTube
{{< youtube jtpX8a8G3q0 >}}

### 絵文字
:smile::smiley_cat:  
:link:[参考](https://github.com/ikatyang/emoji-cheat-sheet?tab=readme-ov-file)

### 画像
![画像1](01.png)

### 表
| id     | name    | date       |
| ------ | ------- | ---------- |
| 1      | test    | 2019-01-01 |
| 2      | test    | 2019-01-02 |
| 3      | test    | 2019-01-03 |
