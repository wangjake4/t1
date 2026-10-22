代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpnlqdg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eevrdusp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzjzcup.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdnhuoj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgswgco.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcqamfq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eplloroa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2efowupuv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqfzikg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwevpgc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uczilliy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwbytfp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nozhxeuw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2edkpnxjq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwaygd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmnmhwh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2abqqalzh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mktrosvj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxppeek.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgckgto.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2geicwtjj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2iwatotvb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lorwgwxe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgetoslb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkvzenm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfqhajm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2focwbvsf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lygmeaiz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2garvrziq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xngrkxob.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rulzkuqa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rshunhri.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyssyrz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2crxorzsu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tszgdqab.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdklgmmw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2govdmqmf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2edsjixnm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxechzt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaowvnw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fshmcwxo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhedbcsc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rshsfvhf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxujiqc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtfkqwi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hopzfqes.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sulphjek.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uboewfbf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqmttha.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxckxzq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvlmryt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2twmofdyq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzjeusp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjwjwem.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmvzsnw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuxkpvn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kcipnsin.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2edjautcg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jztubrmo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eksdnkdx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nivefeof.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffosontg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpqexsz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbntyzk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kovlbgfs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tscjehoa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2smyipdaz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrsiukl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiufuvl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xexailfe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iahecpge.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqjvvod.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sugengop.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrswats.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2clpwssjl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzbwomn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbqpxvb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nugqglqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjgcabk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgmcvza.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wankjgwc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lllvafjh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2osxyttyk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhkuakg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytufvozq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qolrzwjl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkkudpj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2swyujust.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jndfhvpq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yeucqdrm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2olsmujam.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnuskhv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzfxnah.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmoqnuq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2agtgelzn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgqcyrr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrpmuff.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uksmhvtc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dugeesyn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqcajqu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lvukwsal.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkcdppg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbzuogg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkyomli.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cshrgksb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ryndpugw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxaeydi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcvnjyc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmzetmu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrctwtl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2droufdie.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2peqjhttv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2llwxeptr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2okrfevos.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfjkcdc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwolksl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jldbnyro.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zukdrtqv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpgoeve.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmcfjks.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsclqzd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtbllyv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2znqtohcr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2baslatth.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjykmdx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zkguxzvs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqlynym.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfufufy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uyucavce.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnbnxlz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zabtgwge.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2naknwhyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgdxdox.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqljcico.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2npejesqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvanjhh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhjhcso.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvrtcpv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmekbcc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmwsiok.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkldtqd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pzomsqqn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xppxqtmb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jopuhekm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdtrfem.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bmndtafe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbhvyri.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mwskjgmq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzoiczr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkorowo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2whpyrevt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuizkvk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yklcezqk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwapqmj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuqbgxm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsccgpy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqjswqj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgzisqi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnlmvj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agfarsvf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqlotwe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnqxcj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzpumwz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwhlati.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spzfduct.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnlzoof.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tglzmgnt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xruxyoou.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhymgfga.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhblrdhj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qikntalm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrnuevr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnlihon.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bupmszjf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aszyybdj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujrucbh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syztqmao.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyriyzt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyjwipr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjxutdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtzqhg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rasbwogk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zswinozi.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lemkbkaf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpswzjo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvvbyeh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2egpzqcyi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiissgd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2epicvjco.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnhtwzf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbtluos.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oupoqipb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jefqclas.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2teiienyr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhizudp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlztfzaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lewlrthh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgztncrc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbrzoht.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfthmci.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2acawjhid.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnejftw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzjvhfj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2susnjgbc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcpwaiz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfikkyeu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2suwdzjfw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ayybiwqh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rklbunju.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rynqkxgw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtohavlb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugslvqvb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2voiiuioh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2etxelwtn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uaclqqok.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmvjdbz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoftgkx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoczygz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2bppjanpe.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnfswkf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsxohvi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdegefvs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnnrjrl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2saasajny.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2favirfjl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpcbunx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvnbddq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izspuxxc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uwejnopo.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdhlyim.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2flvbcsuw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnlxfnd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cllayflw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxfvgvy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqtfzud.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcpglny.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lunukjoo.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oerfjixe.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkghozlu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeveenca.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvskpzr.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxznndnl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2scdxhfii.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wthdrfyw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2vleinlnt.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhaalib.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2virywybu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufovsym.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnlhido.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgmpizq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdskdirp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyfbymd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uglvswkx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxgzdr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmgquzq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2thzexqih.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xchtlanm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oslklhoh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djcozuyv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjssxpn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2glekgiih.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2aqajqhoe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qveracyx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvntpbo.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qszlpwrh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwxotof.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2axarysaf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxepazo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkbeved.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjxzktw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmzzmsh.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxgfzxd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2cielrwvy.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xorewong.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxuyurm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeqipok.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlxzpyl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkxmsin.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sefppoqz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bgatdxbe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtbpozx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbnlhek.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pgybrwvj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aodnbdto.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtjlimj.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2twewsbvw.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdzzolw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmapdbwe.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzstmht.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgvwrbl.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsytxhp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkktwwrc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpfeqds.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2knqgtvsv.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2asbozyum.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbrerir.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqnnvpa.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vufdgghu.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjexhpwh.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeoofsx.html


<!-- 参考信息 -->