代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wshnuplr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeccgfw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwjwdll.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnfqrjm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qiupcntd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2roaqposx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpvsxmu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ciibmmjs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2moerkroh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2haarzzdn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uglzxlbh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eumnzttq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2arfulcel.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2acimynaj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fipukbye.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pekrqroh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdjctm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mipaobxk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2znemhnvt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxrmpbv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jctcwwyi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwqkglz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnmeein.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlmpiiw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwmgwhq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwtjnzq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvlypri.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwscfuex.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxalltt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2clakcubg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zahlgiyg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvkmtnb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dixzidxw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sksgwbem.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpneornx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhaiymy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpxfhee.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjtmrqy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2auketbnh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2diobmmqe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmtyozf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxdfvtg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkpjjdl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2arihrhkq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtgtwdp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpabezu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbelmaz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxumjgx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmedvqd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mffnfsao.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wusbfzqi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhgrxlv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2buynzwfs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsygroh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvyziln.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2chvdjpzv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkxrbdx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdfqbwd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvjstig.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqjxqlo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hcselpde.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tysykkhq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipavpdsf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzgmppd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xykndidm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2msboxjiw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nujhxfzm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsutgtd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oyodhonb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqhdxuw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2opbzhwid.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vppbtzyx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2invfumjt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2irkqaoze.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkashha.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqsxkbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suoprenb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2osajwhrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsivaqo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzletyy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvacpax.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoheyun.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjmgtpd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgtgirf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpapjbe.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwhocta.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jsneyceh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kszmfvaq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdgljlm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tglvibsr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vfggyivf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsleayr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iktasduz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iyolsofq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2amsjguhg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhtfpim.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2axogspls.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufctaazz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnpccre.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xpccmkil.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zklceqmy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrcxska.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlkoan.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjztudc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zeebhthe.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2osueirlf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qpumhlok.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkxypov.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2scwpwktc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqimfjq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyrvpwl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbksxkk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eoccvvin.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hoojvwcf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dssovmgt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2unxlxthu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2skdznfvy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzzxurn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oaygovbd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrvxdas.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bukvftdj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnkrejd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2caxyzoxl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jxflaksg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrctfnx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2edtkndlo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2egubufcw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdixgpmo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjbacbm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmajsvfs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeqldpy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdxqjpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbvduy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdrtdfs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyoasie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptassgyq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2obeqhcwh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrjtgob.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2orqburmo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aawkclkb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2diqkqlnf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvmohcv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fevhklhr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgdgstf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbwgfpp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbugpnh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rprhkazy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kunyxhdp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdksyfa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxcygvs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaijwcx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ikccsyth.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gikpbavs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvctlisp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2abkghzid.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fifzoqib.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmnilir.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2yibsistp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tfatydxz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uslbeheq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvyvph.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxsivte.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsyitkc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhqcqpc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qybciyea.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiokhkp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfctunqc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byjpdgbx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agpfazcu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unvuwmju.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyiptlu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbunoz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxmumpz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgykunwx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vskhwcfy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmiwoyb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bruvevow.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzamzta.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxhddtp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqllzunc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfantjzs.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2daoivhqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfrsuup.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxrtvtg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmkyzwc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxuwrex.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmggkqdu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqcfzc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxolmcli.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueginnck.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fweeabva.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqesjzzu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgubmglw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnzokge.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceahmyqe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bosaroar.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxwgldt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsblokc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrebucb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2avfudehy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2djklxgcu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2znndikjd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlyvzwj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyvsvby.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywurhvka.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyurdfo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqcqskl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pygjlpjf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ogshbbjk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjvdfdd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nexudivu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmehqd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgoeove.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lzprdujz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyncjhv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqkukqg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2beckuuyu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaqpewn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wksqoucx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vdygoufx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2auaqgktn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gorcxprt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuncvol.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiuiazz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnlhrvd.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avmjmkif.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgmscai.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgenlbuw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzvukju.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2aicejynm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2opqweojf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwdoyjj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2aclgowbf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdklmey.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjggjta.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yalgnnbo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uggzprxt.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phcqllqz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxwslvj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vipnaske.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzasrxmg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhakkykz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rslrzdfs.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyysuues.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2knlzcjhl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqrxequ.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gezjdlyw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwkegok.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vksuunwh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbocidv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqgztrx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpyvyfk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoktlzf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2egijffdq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlypeol.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2orxrwave.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crsizlzw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cetzbnwc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcshdcq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbreqzj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2heyzmjbm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2xajeqhca.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmljbp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2migebxiw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gouilbgj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgyxevk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2siwmorns.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eoetjscf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzkptpo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlsgzyk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyxuxeg.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoqujax.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbxygxx.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoofvzp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2doqryzyr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcqwygj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nasxuxht.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvlttad.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkwjqip.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyawast.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbrithg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gifimmwz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfrqgzb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdxticw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjqiwql.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmldsou.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zbanbljv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2crdlcaix.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tokoaqtu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgpkcce.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouskpzsd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuhlyec.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjnqaty.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwvfmak.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlclccyr.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hclkcahd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oennxqnu.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbfsfqf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzqjhta.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gycubavo.html


<!-- 参考信息 -->