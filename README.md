# 廿六三拼方案

配方： ℞ arsenali/rime-triple-lishi26

[Rime](https://rime.im/) 廿六三拼方案，三码输入一个带调音节，第三码声调码可省略

## 安装

[东风破](https://github.com/rime/plum) 安装口令： <code> bash rime-install arsenali/rime-triple-lishi26 </code>

本方案词库依赖于 [地球拼音](https://github.com/rime/rime-terra-pinyin) ℞ rime-terra-pinyin，安装本方案前请先安装 ℞ rime-terra-pinyin。

皮肤（主题）文件依赖于 [同文安卓輸入法平臺](https://github.com/osfans/trime) ℞ trime，安卓平台使用本方案前请先安装 ℞ trime。


## 简介

本方案是26键三拼方案，共有4类上屏码：带调汉语拼音、无调汉语拼音、注音字母、国语罗马字。有注音字母专用主题皮肤。

26键内实现三码输入一个带调音节，且无重复音节，主要适用实体键盘打字，编码方式是“声母+韵母+声调”，第三码是声调码，使用oeway五键输入五声，可省略声调成为普通双拼方案。

声母使用21键，韵母使用26键，声调使用5键，声母、声调编码不重复，故省略声调不会造成重复音节。

### 编码方案

本方案在小鹤双拼基础上结合注音方案改编而成，和原版小鹤双拼的区别在于声母yw和零声母：

1. **声母y**

把声母y分为两类：

 1: y和以aoe开头的韵母(除了ong)相拼时用j输入，共有8个：ya yo ye yai yao yan yang you；
 
 2: y和以i,u开头的韵母以及ong相拼时用f输入，共有8个：yi yin ying yu yuan yue yun yong。
 
2. **声母w**

用q输入声母w。

3. **零声母**

零声母中的er以f引导，其他零声母以x引导。

---

详细介绍请看专用主题皮肤中的教程。

默认只载入地球拼音词库，需要用更多其他词库请到网盘或QQ群下载。

下载地址：http://www.lssp.ys168.com/

或：https://pan.baidu.com/s/1i4X3WFz 密码: 1jpd

QQ群：[150478288](https://jq.qq.com/?_wv=1027&k=5wf1uTQ)
