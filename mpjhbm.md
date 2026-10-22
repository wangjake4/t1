代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rwebucty.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxoyeqr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjfdpfg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcctkky.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaetgwv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhglrgwl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2srourzar.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjzgnqy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2apawvmxx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nogdfgbs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbscoub.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbxukgj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkvwpre.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdtqzxj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2otexgvdt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndieouza.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2junmigmz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrakydt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfgizyt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2infzrxbz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgoxfji.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfynuid.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2krgdqndl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwrleav.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inzyjqev.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxjrnzf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfqqbbc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjpeysj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2eduywdda.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvbccfd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ytegkozl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlgonpa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwblbfl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztagokej.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkhowzh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxqtcya.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwkczf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kookgfor.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqazngsa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2clgcghnt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gixokfjk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqscojm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cslusavd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2amdvoyxx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqoiecx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoktjjn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2twcnecid.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcubszf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmoygkw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcszlker.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gybooyqf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pojyxwpg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlczjwo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgketwkp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsylkup.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmorgle.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbclgdws.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkuvfnc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2brlsckvc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqhtdwe.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2znmcxsql.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwymgiw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvajxte.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhyzfli.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ewycalat.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgyrkpn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gzggbkcv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slswgati.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvzqwzo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioubeyus.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhvryd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjbosyc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhloqsw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kynveslp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yihyduld.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyfhopk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ojygnsuz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2biwbopky.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaeetoj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2situqnor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opixjrta.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlsybna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaauazpk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2afvlmsfv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2udeuryiv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwllrwd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yeztywyt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaktwaa.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjtcwov.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qolcqtrn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxbcixw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgjgxwz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gghgelbi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2epddjoun.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pllnjkzx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2izpettyi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2szmhwtdk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bndoqcvl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iekilqql.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoacadd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iauuszyh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoamftl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vlryjohj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvcttme.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jciuowbw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaqazso.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eocvjzfr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzivohs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbrhlgm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgsevr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqfxdbp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeppwew.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2thtmsepb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kckjtfui.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfajdvlb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxorxaf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ceosxdyf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ginsktiz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gytlehgr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klccqmnz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tioejyhr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxauofc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2luyfipzf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2behugbqy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyhpzmd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2brbmfnqn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2enfsjnic.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxnlcff.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2msvvpyfb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcmlznk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpwefaz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2owqysjhn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvtzuwd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcsonid.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2odeiplwz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnybxtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwojzrsm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgjxqhr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lyctzvsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nueiegej.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlmlyjl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vaswyzsl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuazauz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmrbzzu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrmoizo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ppamcsfa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpyjavc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zozzinnk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2oearebgt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfcgxbh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfhixlp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2psxxagro.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pireletv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2owxfxixw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyshmkj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqobwuit.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzblupk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyxsqeo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtcrxpk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2olxxwqks.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2klutxpzu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmwpjoe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2keauemux.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkhldzj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juqxortq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dclfiqup.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfdanrp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wypxsdmf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgpwfxf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hghgrrts.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcgpxbs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfesepa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwgjuyf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfjosfi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvakkjto.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2muopjcwq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtamjlw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtmekow.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbzdeaf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrlmllg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zanjiirj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcuhorx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwzcqew.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsuuqdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sciheyai.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcazhce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoqhzma.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwmpxjc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmnsgwl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkilbnuq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoahtqo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dacoavzt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjyrzfd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbethah.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtpazpm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiilfcd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2uovuksqe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2woeqxmdi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2unclwdrv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mumdougy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lldgdqbk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxikofc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzoomdx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iskwjlzu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqzikvp.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtwwukn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2nplarlsv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfakpzwe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2asisccmr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2focqctij.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpewwifh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxtinwg.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcqfpdm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zahernui.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osicvcts.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbkwrui.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrfkems.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2frukbkrg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzgyswo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyqxnib.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjzunsv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcplcxah.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2nkivtyhz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2etlofnwh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zknoqwxj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yltbxdor.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlqhfgt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjtqwzq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omcjwtag.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iulwaqpt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blosywie.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfgueva.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqvsomw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzgsdkt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvumsdpd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcsqaxs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoxryeb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zparhkzs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfviwlw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhbwytv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpvlshj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlkgauj.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqrudwy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpwtueq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2krqikoni.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymotvihn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2igvyvwbv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnbgjir.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2azfudtfd.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtyicda.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2invmnfve.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykponhji.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itaqayvp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkofthvk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellhvyhc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoibgac.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokwxxpc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2evflkdbq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2caircpfi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmevmvbk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfythlr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgurvfe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlfsyzc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2niwylygd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkyexjz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2djkebcsh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxklxel.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoefqjv.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkbtcty.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqhyptb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ungkqqhi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ytovtmbq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2obkgcvhh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxuajbu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2widedyhi.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdybnolr.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgnocfh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqwrvdb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdantebl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyshmjz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kofnjbgd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwhsito.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwzdkpk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqimeyo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2erumnzod.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dypplcvt.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwldrud.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjochkd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2llweimpt.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrmtuer.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2madwnpvr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jelonxvx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gruwxeha.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvprjmpf.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xakmwigx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxwyxkf.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcusachi.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkconwok.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmtzmub.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwhxrtb.html


<!-- 参考信息 -->