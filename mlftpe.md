代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2utiimutx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkyipnv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2njrknhhl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrssmoy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2onotvvtj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qllcdcmi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oejkpyiy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjjqnin.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhlnzp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eaimmkzo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbirkog.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdgrroa.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gihwljmj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfyhysv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2khgvjzvm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjjecds.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdftylx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zuonhunr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyaxuyh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtnfidc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgwxmly.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yjopzskk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nnelplum.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbfobit.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ifswtepf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshrdzh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjddynb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhauxro.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnkcbql.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hyghxdpp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hecxacwa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqkwyef.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdbgxhj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgutolxg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhnzpfl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cokycbfs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrkinkx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxfsjqg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ietuaygo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrkbjrf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqiqtku.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2trfzsgvz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhgpela.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mertqmat.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2scxfqjck.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdfzqbl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2plpxyeam.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqecgnf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvzcvrp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqobuqye.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2liymwumd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xkterzrn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfkdupr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfcpgde.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2esnxnqlt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vngnvcdk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrsfias.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyihxjgv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zamsngru.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmplidr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2efjozfdh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkwjfok.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrlreja.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikflecaa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyzyblc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhpuaon.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kbguwiuk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2satbfopa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2plcvcclp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xhontohm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcugvohe.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvodhhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhuvjhh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fdudwmzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmwvaoq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2avtspnau.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2saxohomt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrsgwox.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rutjawxc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjqufaj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqqeods.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xufithwd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pohywlki.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqaiqht.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtzwism.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhqlxqw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtlxcch.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rswajxfn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxcjhsk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vclxswcd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvxvjgd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oepulgcy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wivwvyjv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tctvyrvh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2plpyzwkb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzxdpwk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhmaybh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2stslsjgi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjqlbsw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjytuhe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rukfisbg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqqqjuu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jqegzndm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdelwus.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfvbxwh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pssthktp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfugxdo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mklprbss.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvxzyrw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iramckmk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zgokmtwr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgqhqyh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xopbgmmm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbyiwsc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2szqngnvy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvyvnj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbbinxj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbrthhj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2phpxnhxr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2muyvncux.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2blbrclry.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbqnzaz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyobqhx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeavwza.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmmpxds.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2quxbwpuk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqjcsov.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgxwoxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwwfkxa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvaxqka.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vcupqnyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwdopzr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvjaxdo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtemdun.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzhlpxg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bwecrygv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmzboqs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwnztyj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvnhyna.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2imhyakht.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2suuweclk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuhlorz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvxshqn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvxtpvk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbeemsi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmzhilb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mwixbeol.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlphkzny.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpqajop.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xycgsqoa.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnxmnay.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhzjer.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcmgsjr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lenvpuyt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnfktej.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwinfkh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiqbnzy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mabrnnsz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eudnhctl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grtwzdxi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkzkwdh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrbejjr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxdfjpj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdamqcnb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tacapyyt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcmzgzb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhrbgvl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njtaomnu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzylfemf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiviohzj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wltalqmc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsojilk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2caioelse.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnnjrq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dolybgix.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abpoeoji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfimrbko.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scqjiptt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaokysi.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdacnvf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjlqofh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyywkfih.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2abffwtcb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjaamda.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnovthi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2deratvfy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2puxrtjta.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyuxjev.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucefuvmf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2teszrmei.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gylbxwsx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhbfpbl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxleijf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctigxno.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwgaaaj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cohstxpf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sprngmix.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpfgiox.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtwawxr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcdbkcp.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsgnrrz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvpkwpb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2btvxxbzo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcpkgoc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyixusw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbmfrwy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoouxkr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxftjna.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2umfsgfbk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkasukm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxfgybf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhzbutd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnziyjyg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2oauqrjtc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yppqjxxc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdnofxu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbgoocu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwdfjkv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjuzccm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbmmcom.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhjjsoz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fakifvbf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaevodq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcyqnyx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sumlbmsl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvupwefv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2emptpfxa.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjnbpic.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhvksvj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ratuaytr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcremky.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2knngqfbq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nglgyslb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtqjbdu.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolwhyxn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sobsplcn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wajxfrsz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyetmml.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yklkrdql.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylilhzkn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlsdbsx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iylksrxe.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyojyhf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcurpbhi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmskvut.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbsbhzl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdweqct.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdyacsp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2asotrwgv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmgwkff.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2basdolxk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2osrtrlbs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjbzdgk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkubmfe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdztglmc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzecsld.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaymhqx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2epkpeima.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2uaubxhqr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcacnutf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoebyem.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykelfdmi.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcvhzbf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyojlwqq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxuezsm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwuzaus.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqyazdg.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2szfzwfmd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbwzblb.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpknohz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2svgdcaes.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzsruul.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoftqvi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcbcqju.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2efssbstv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaxsajj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eootzvww.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tccghvkz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2akvkusrv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrlxlvr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnxvsu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2nymhccwv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdmfjjy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fndzujuv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2byiblshr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqmvryc.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2csdqixqc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2quvvjqds.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpqvpcu.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjjachd.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aofqscue.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2khvdcnah.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2utzowkhw.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkmippe.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjpjncf.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvufqykk.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2trrypiot.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlvhhaz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2eshwzhln.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyyclip.html


<!-- 参考信息 -->