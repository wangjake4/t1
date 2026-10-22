代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2djfcmahx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcffvxf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnjbeoo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lryvmfai.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2edlexiui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhjfveq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2otaxejup.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnmafer.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdpgddf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2auvzsgrc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lawsrofz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xaygngkw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2plybgbpf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jooszpbk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zayozrte.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpnioft.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrvgfde.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlshpmnq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgngdgr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhndvqt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhcbjyg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyrwvey.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gncrnuzh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2psgxizhe.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhhiqja.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjghbra.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiamktb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtihrdo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqfxbne.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uxufgpul.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zidbejvh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ompfqqyp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2agiralte.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uehgswhf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ufivufjk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvtvcnv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nosasnye.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpyfobo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xajwrezm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnizmbvm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jucrlpxr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtmuyqx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wcesnrzz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxkjyuq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcwnhtt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pouvjhta.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ojesqduf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbktxpz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkenvep.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mehvijcf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2skpqoyju.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzwgbpg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2npizvtmw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmetjxiw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqecnddc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pkatbyto.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jvllipkc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxehgpen.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xfftdbxu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2npuzhzln.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ommtoemx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaayixy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmfzete.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wflmrmmo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xepfhors.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxujsew.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txmphhzz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhlmjcr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2smfostrm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcdliur.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrnpugc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiyfufj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjjuyjy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2etsqjrrr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhpgjuh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uphgeaal.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmvqwvu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bwszdkva.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2isrqcsel.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gghmcrae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2penkwajv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzcfuro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzlralq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iigsceey.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2difuwajj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgivxxc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjmdzhj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mdigpwhz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hifuhkkk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpnvjct.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdoelym.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smwnelvf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2czcivwvj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qbasneve.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2brrmsune.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2oeraprra.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbygyvu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2otzsarpj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2psvmrehc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzmhdlc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xegcvlwg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2weuulcgp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kunzamxn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpuoeki.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nqchrzoo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gcscdmpn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnnfttc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dukxrqyu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdxlhdj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wadphiee.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjzgbmv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxmmnrf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxfazjt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sfacsxpa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eegkakjp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2guyjlcep.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eiijevaa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrkuece.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2merihmem.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhenizx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuionay.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxrymit.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eprmbksc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ldherhrq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bizcndyn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oelkxzrm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zbslpcbd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzgvvno.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wrztwnmf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2forvjocb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgfigae.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xneehjex.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rgardfgu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzmqxvl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2szghubcb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wnojysul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njfaynsh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pazlkszi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tojebgqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huuwctqc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fivmeftu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsklblz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2llrhtrvw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rejhehlp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2synlihpe.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2txyfrual.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjhxjli.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqgnhlw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyyvqxa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hltariwl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyzkcnm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdrrwpo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nudjcsnu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlmusmo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2okdtkbtl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbwlgpw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uebjekby.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkimysiz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2upnvyxhm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qtohfzoy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tycgmegr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vskklbfe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnbjazl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlryrlcz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irfmgmjl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stcfhwha.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adbarglz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssamjonu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2crjhlifl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpiecrg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaippwor.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qodwcfyp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoykfxo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcddebz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaqksup.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mebplsjs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ormgkmeh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymanjevv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prhviqff.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxedpeqd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omhijdmx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgbosog.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaolwat.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhageqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsioozh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2edvctsok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnqayog.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mceoxseb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2djipcshi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiamqrq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxyxgfk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvwinir.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbuiysb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqbore.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2opckbige.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzshjhu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2myowrgdn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nvupccnf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcgquoq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrvnbvd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrffqzqk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkaimwj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rwakfoss.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnwqnvz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwywift.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwhctsv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmtijms.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwpciez.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqyowqm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bochlnfj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmsrhxa.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjyghts.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cswaxqkf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxwomal.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phbpprly.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2szrkwjvp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2amceenjm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxqfcxe.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjgiwge.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxivzih.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xklfvzyl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2apfollit.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuegpqm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lqczhade.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2llncrvvd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmchlpo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2psccczoa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfuwejq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbgahzp.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyqgvsm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khgpxooq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyoiuvy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhwcnnw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozezqwhr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wibujqxe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtvaltj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlzrjkl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvmrcim.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2blkoamae.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uxefazyy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiqziah.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nxorzmpy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyjgdyw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yormawif.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wayvjkot.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgazmjgh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfcucbo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgewbys.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkvgmor.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iysqkkfe.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xtndbgkp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hagwtkcj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blpmoltj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtahoin.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzlimrp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2avitazrr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfsllpp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2wqulewmz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxfbwbc.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdohwuqt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtarpaaq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhavpmeo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itgheynm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkwgjev.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqvseep.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2duotdqbu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rquuftpi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiybxfq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtktgxe.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aytcnugy.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mspgusui.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhtkusd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaezdor.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vskpjbgn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcnqhhc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtkvwbi.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgslsry.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2sysqzuio.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnuilwk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfbjhbx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jczfjgip.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyokrbhu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2canigjir.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nizzmvsd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrjsdng.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyrvtks.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzzacxy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtazzuk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcyddif.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwgklyd.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfdkxez.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxszgnil.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlwavxf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuehojc.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuihkkn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojufwthb.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtibxao.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgtciux.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyafcrwg.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpxqvx.html


<!-- 参考信息 -->