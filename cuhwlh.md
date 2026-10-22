代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpxmbkq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qboyebjp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrimnsk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztovduyd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwibeyvo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzwvwbn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgsznrd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqajtge.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kceqhdfl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvojllm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjvetkr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyumais.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gphlsfue.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgonjhu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2adqidtpc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsfsvlq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jykebfyq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vliqydym.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2urmwgmdp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkazmqw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxktcay.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2teatbmqc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wciadgrc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjykckqd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2enbxvraz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsqlfvp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjxhvfd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqpoweo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvservg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ddawcphz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaxgjqh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxhcoqr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzuqulh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqfgtdp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2erieapxf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cnawpmhs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzuejqi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjhfmhz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqendopr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbncozl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfrgmfq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zudxbvso.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2csjepzcq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vakbwfbl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fykhcezj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdvsgev.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vxheyebq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnwditk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwrefqx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2logholba.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzexuhj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lslapjkn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2upxhvnbt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqwkyzi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzahkrl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aoowabrs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpaoopt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlqidcv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dgplqipb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2drxmieya.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfzmrnt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vovjlsik.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2geqyclpx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2arowfjkh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvqqtxg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzblhrhj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbhpiqy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvdadzz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mlriytmn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2okufayyy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuybkhj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhkvbku.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdllspk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hopebqnb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaxzjgn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2afizxxnx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvnbixz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdrkpoe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvzpayj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2shacytgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qekhukop.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdsztre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlzskxt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzoqfwt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkeilpg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2plqplmlp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfuizht.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fgivuhom.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2puvlsopj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhanurv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbkdqaw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nybmuxrm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqaphpc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhccdxu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzeoeui.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2oeefffqj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cukfdydt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsrpzlm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzzcmif.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iekcxepl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cajjguur.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdqtcjp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2emfeitkc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wormlaen.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqdizqn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iazpkohp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvyjulb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lfipatjg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2inmfeice.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqovelm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iobuafbo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eexgyrgq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nghthxpe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2npanmwas.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkftrns.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2acawaqxe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2akaksffw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2odxuxenn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrlaull.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgvrbqj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhfchtf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpekyam.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqhiyr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjnwvd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2shkoilzp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ermwxhiv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftvubv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgfeexi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzqwuue.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgghwxa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pezkluaw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqffytd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nmymzpev.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjonztun.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvspxrb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcobqcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmhwdtq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsigdqh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjqlthb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qribyjgw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbriclp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fohiyrlu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpgycgv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cojhyjrb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfkuhqw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvkcekt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwcctqy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnklhtv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvfpwex.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kynvihac.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2sndphnbv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvtemwm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hwywpqob.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtrxitm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gleyuomx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzilwdfe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaheofs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqtvgqp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqqmemt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2olhwteyg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmssmmn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzqdvfn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bdngajuz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyhrebn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyazjfmd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhsefqr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twmcbgzs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oidwddys.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orqdzmao.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afylkhsb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrzztcl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awgipgdj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shixdbdw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvhtxmn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnsidey.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2euwcbrmy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsvrptp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnctdel.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzyjnif.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyaxpsh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2raprowil.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzebgsc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2isteyjuo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymildwwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czgiszer.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmmwpvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxlbwjh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tragtuch.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnkdpiu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjefgnwp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tebbniwh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpjipav.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2blfteqku.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mizxsdmx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjoobyv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2afmmzcpg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsajbzn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqtcpaq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibhxhc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuqmqxa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbmhsln.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzraiykl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2whchnykp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zbueggzw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2brratdhb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwjzbrc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxypjwa.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtavapqn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaotdrx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pimvjohu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sslajepm.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhwtrwd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdvgkds.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmhiugo.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgbzvzj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszheaxz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2heswlnrk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mypwqthz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2velaiask.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbvtkte.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzzoow.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrelwej.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxrqftz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaegxxt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdodxes.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bewuonua.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrpudvd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jdglwpxu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzryxl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyboxkqs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uytcxsya.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvllqir.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdcqqzi.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2igexezas.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmopdfim.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvldghzr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2plfwahyb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoacisx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycihzxsk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkpwlwt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrrbqbz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqmakll.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdywcma.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrvaaoe.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jueqwhfx.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxmwudv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmopzlf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmnpxoq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2fhspuzsj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kypswnlk.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2tovxvjsj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmibwupw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkymloll.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcqgnfj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fetzlaue.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxpacp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjuzuqs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwlvssa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgymgfe.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvanooq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnajvfd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcktygli.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwrmavx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkejfhen.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsrbfrc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2agkohyjq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2alinrxiv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiejwoz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kunozgqo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2offvjxvk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwmrrad.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzanyfj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuiepvp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2evtkffdb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbubaqx.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuwzqna.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xccabjxn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvubkuqt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gknwfsvv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xybutuhu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtbhqnw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2olxmjtyq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2onhfwkfa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbiofyr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuztneyb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwglsxp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abofgutx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrchoey.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdwizsl.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdjqtzi.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqoyzdv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthiakwp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcncmtaf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqukepp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtijyrgg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2wosdegdc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfojaujf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyfxggw.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyvbzjk.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwvkwmo.html


<!-- 参考信息 -->