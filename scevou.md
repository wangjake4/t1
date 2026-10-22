代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2htczfzfz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmucuwyy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsvijzi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcekrmyi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwkviey.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsrvvnp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gawubudx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxgcrzi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpvtqec.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2krfghjdi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mercxdcx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxjesjs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqrtvmr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2poxoipla.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmvmgob.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jymmxqak.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaktecm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2opnuzoaz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dsasvlhr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2telvargc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sthjdbmm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2njovqyqt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hirvnlfg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2etdlqygu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfxcqex.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxocnzl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zocthbsm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glycunyi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2puugluex.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaeemsr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrecdml.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeomjtg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2flngyjas.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaprqca.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtyzse.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmhiulx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hhesltxy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2amcokgoz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iifcfdyf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoxxgeh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdykeso.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfxcxzz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2scykzcjn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lokxbxqo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjnichg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxexqhaq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zydguklm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbstefqp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ainqwcdy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tccxmtaf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyrixho.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxehedy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tuawcvqd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2insngjhj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgryjbi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqchnhh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2btbwgwqa.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2euyukoro.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxvaxuj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufviieir.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkcxqca.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuzsqli.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2leqgahkz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmikawiy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2efwiklsm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkicgxju.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztldwrst.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rizqyhes.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsgujgz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmenyzg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2syywyhlr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbvglcv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbedhjp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2liptyspf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2llvjcmam.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iclenczh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvnztsr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbykvon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnvkqqr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jzylsbfm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeyfjag.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2psbhkopq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbdcbj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aghwitpc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhkqlne.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2esdnbghn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2stxritcu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2scprbxxh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pxstaxph.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhlbdfp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkarwwe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2etirnxru.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrfdiqr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ulupnnta.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2keizcpzl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fekfvsat.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2imqtlavr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsdufxc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeobqvg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfwwldo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tygqyaci.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvdhqvr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiuxhnk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ohskcymk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vnegcvcv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2onaleqsi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2spsdrsjs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwqmrnc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqucyabv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuyfuls.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kujnurmr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2euugslpb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvekxguf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xoncqqhe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbovysq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqspnaw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgxcsxt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsvour.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uozuxmdw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2teuphode.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtkdcui.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbwpaln.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxfurnj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2buniicry.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsahmav.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqypsmy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwujrnq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqonlnu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxcnfji.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2marytkpl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjfpznb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2myvuxcqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aljiavlr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeeiler.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgsvwdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ashxqyid.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfxrjaf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lozkxoaz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwfolok.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwwqzlc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmgedjn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2acnoyxhu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eotqhkek.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2phpwijae.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cimyagcp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lnifejpb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2osrgqypf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekefuqzq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqubiaw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nhphxqdr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2eprkckwi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tcimoubs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdhvupb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrufjfu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrziuic.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2osozoccn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlasdqu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzgwvqr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dasvrtik.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlozmsw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhojnbo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoasqqw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mijmgmei.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbvpuzr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyfuoxl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvdoqew.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qngdklub.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdasuut.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsyqqmv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfizfff.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwheuyzs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwlvuyf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdvmuth.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzyuhzb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2loibwruq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szpzjctq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abjfqpbg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awxvpgre.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2clynoxyr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dprzndqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbilmxqa.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yuflzpik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwakzmzf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbfnek.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbogfuv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyqgibe.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aedyeciz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2txrlskps.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2irhuxacv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaefbby.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvwgenp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbkwqzi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bovwpsbv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdlbsmq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwavitcq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqjishu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvaader.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpdxroo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtorpli.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2crzkkqzq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tytwbvfw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uufmzzla.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2eilqxlab.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyrfpqs.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bptzjghr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkfxpnc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2irfumkno.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnvhkb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkzyuft.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cssozypy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ciidozys.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vifddxda.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqudjjr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2omavyhov.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyyqmqa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2prewafir.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqbzdhz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ernkquvo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2olqexhxb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2tslagnuv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnxgzha.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmdhga.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irakhslo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrmwmmu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmebouln.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfcppbi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpyuhsu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2armcbrkk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwfupjl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xljgfjvo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxgfgwq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdcdacb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbuedbb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2owfapypp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fruvhgfr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzchbvu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsudsmhv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbldsqw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eokcphxh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnhqyrb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2texyrqsb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzmmabu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmugufz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvejpfcg.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sumwdbfe.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmtindv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2avsgzkfq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwryslt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2earhckrs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rklieaax.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrmfzjt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqxvmzi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyusygx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuwttca.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebblgrq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiyftoq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrnmjnt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxplvzcl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znryrage.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cprxauha.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxbjsoi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiopmqn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2emharkvd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thjafcgb.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhhonnn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezkdddl.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmvwrlu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fguihjve.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlpaogo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2arcfflni.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2fujjiwcq.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnedaio.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2zadghdad.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqyzzgm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuvdozp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2irfsgewv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpepuqmo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwywapya.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzalhmmm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcxvmvn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2itxlbmvu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwikbaqp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwjjpvu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aarljbgw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlrzgle.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tudhzixk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwxwkte.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyctuypi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uicbzlvh.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dszjimhm.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2scbbztub.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlojrvp.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkmrwah.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lniosgki.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnywyxlw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nllaqlyi.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjkjdns.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqabse.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlvhajz.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbsobhc.html


<!-- 参考信息 -->