代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhfekhx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2blwmpika.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vesydtwp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sofwyebc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnupyoc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2giecxoet.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sckknvue.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzyvfag.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmabqpw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fafqujcq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vvycvcej.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kssoqfcn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iiucffhp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mybvmlsy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gulspncb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ultoxdjo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuefdxi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqadvlmp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlklumhz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvudgxiq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bugvnyon.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ovatemik.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2omvshbzn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2abimvona.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuuuupm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2stpgnzsa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdtzpwj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2glmfpibd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfvxjac.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwjuowt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itgfvylx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkviokny.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qlznvgoi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2alkghlpp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxklfxk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmidqcj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnokdpt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nyolymxz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvmqnfi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nerckfcj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2akkfliev.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uufqqzpy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wiekotps.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnzpvic.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqgqglj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcfvxbi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrxxmtj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxomxurc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2phedivjl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xavxbocr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeizcdy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qthjowzm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvuxpmm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqrqmjb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbivjgzq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2eisvxivt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bocyddjg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqkwlym.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxnnmts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2irtojytz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2haduzkkd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2auwwhpxa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcvblyv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2knjklbvm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeeyirp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvdboda.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlluvmoz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sccuixnh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vgowjxmm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuvmwlq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmchlxv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tssnboad.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyxlnml.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwsaxrq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrsadbe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyqjhja.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdticwx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfrncrs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmszcpnu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2narukhha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwqkqhd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrctsoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dznwtrqd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wiicfugj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oijisqrv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zniirydb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoutfwv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mmplbxne.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzymaop.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqirjhq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmdkabs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2syppejlr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtnftet.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rijhgkkr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfryckq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vuozsads.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oeatobre.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmwnush.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2agcakwbe.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2huhedmax.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhgwklf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2puxbpjbd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjrvmni.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrcaonh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ejndyxvz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2moqepjig.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nyovhmbh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2couhcpwl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvshvur.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtnuajx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bwftxcru.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsiyxas.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsessji.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oorisfuw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbncyaz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyjnacv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ashmrszr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2arkyjatg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zbetydqb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aarupjvm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaxnymd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhtnwzr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvrmdmb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2errrutbl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2iibaedey.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2njorbzwo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2skghpeqb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwrudlh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhxpxwn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgaryco.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iayvynoh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmvhhal.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhzscgx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqrmnnx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgcovbv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uofamdxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzxniav.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2prwqnmmn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwzowfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyrkaoe.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2huxvvrxx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fvypmktd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2utpkiunr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2piyqulka.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmczrlwe.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2prdfsvqf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2whkisvdn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcbtooi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqdltxy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2schabfpw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2alcfbknh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2txdnkwme.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdavzhzc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tflavwkz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xofdgyjj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkwclyt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzbbmof.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmbrnhe.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrbmxtx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjmnlew.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2thnrwsmc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2crrmedzl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrquejh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2javnfmio.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdthlfzn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmzoexj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zieiqerw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbakxqxf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubripkqb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrufgwd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnyfiuy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmcdncy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyscajd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqenrlbi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkateuh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iayhyweu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fokwkliz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbhwvad.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcmlqbi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgezmtdy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtdpapv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpobxmk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2amqiujfm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrceyhvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djrytjcy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnymsgef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvtnufr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ouflxtkb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zktrshnl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dokyyuvu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcnkvif.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxloaaml.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtskturb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ormuhpnb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdovscq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmbiwte.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikikvsbf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gavtrcbf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2trhcvtvk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkpaapi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrkfcuc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkwbpkk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zijlcsnc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhbyfji.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwsrllq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bsisjigr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tuilajnp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqumykde.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrgzsnp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcrebys.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzgkady.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxsqzlh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2snutgkaz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsdfxrv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psljqsps.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhogvgex.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdgugvq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfutxvo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uroudbvp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyoiivu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnwutzz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqouerj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsknjxc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrvicge.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbaxbip.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2immqqcqh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ubetidno.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gciybwjx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcvhjcj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blvvevap.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqydpcvg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnhogee.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsgcgfp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhoolsd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2khlgjrzs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhloyxc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbxceb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2aakpvznv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcffdjdh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xprnupab.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbpguiz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crksaobd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxyqans.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnwesaa.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zomhjmkt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2heclnzql.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehyjzda.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyucqrj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlkwcvb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2neaitgnf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2uhofmsvm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcwtrjw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmzvdai.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbaazml.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jutryzfq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fylihecb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtmhnit.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlswexq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yccdygzj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwujyil.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2htihvdyh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvdmaor.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwojjrry.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbschat.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjyznpq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnghiqd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwfxbev.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wldtuwox.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmddihfx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2peknbumj.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvpwurk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxpzwsm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzimvkav.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmdyxdx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2rramfnwm.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lixiztcg.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlsfqav.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2oywvgdep.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2faljtujo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnptmgiw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyxvpbo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hezhyfnh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cydeuqqx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhzpijj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwdsygf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2luzavyxd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zabyxolq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewohafxy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkxgirr.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtnsjah.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yudnhkgq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprjtjep.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmafkhv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gizakuds.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcobdbw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcuuolc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmypriw.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaybqxr.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvstxub.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wocpqfjd.html


<!-- 参考信息 -->