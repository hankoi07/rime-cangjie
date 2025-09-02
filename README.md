# 倉頡輸入法

配方： ℞ **hankoi/rime-cangjie**

[Rime](https://rime.im) 倉頡輸入方案

## 安裝

[東風破](https://github.com/rime/plum) 安裝口令： `bash rime-install hankoi/rime-cangjie`

授權條款：見 [LICENSE](LICENSE)

## 增補內容

*較[℞ **cangjie**](https://github.com/rime/rime-cangjie)的變更*

詳見：[compare/master...hankoi07:rime-cangjie:master](https://github.com/rime/rime-cangjie/compare/master...hankoi07:rime-cangjie:master?diff=unified&w)

1. 可同時利用 `x〔前綴〕` 與 `〔後綴〕z` 取用重碼字。
2. 爲一部分字增添了備用取碼，以期降低重碼，詳見下：

```diff
梯  dcnh
> 梯  dcnlh

順    lllc
> 順  llmc
顺  lllo
> 顺  llmo

临  lloa
> 临  lloia

玩  mgmmu
> 玩  mgmu

慣  pwjc
> 慣  pwjbc
惯  pwjo
> 惯  pwjbo

表  qmv
> 表  qmhv

蓝	tlit
> 蓝  tlot

< 茧  xtlmi
> 茧 tlmi

< 蒋  tlmi
> 蒋  xtlmi
> 蒋  tlmni
> 蒋  tlni

蔣  tvmi
> 蔣  tvmbi
薅  tvmi
> 薅  tvmmi
药  tvmi
> 药  tvmpi
荮  tvmi
> 荮  tvmdi

被  ldhe
> 被  ifde
> 被  ifdhe

盆	csht
> 盆	cshbt
> 盆	csbt

哈	romr
啥	romr
> 啥	romjr
哬	romr
> 哬	romnr
```
