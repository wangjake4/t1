代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prvtscht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pffmnljl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dsulvkrd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtwhiim.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2llbrmmqw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcrzbnb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuwwimm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxihreir.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpelrlj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2symmymjx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuadsdb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqzljhf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ztarggyf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxepevjq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyexfsf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmenlpp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2erauujvr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtskmvw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgfikoc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzftcpc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2coekypvh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2knxfvzom.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gorpgocp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaahuizh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pyedyjai.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjedaymc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnmgids.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpyiaq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjmqye.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqzjuxv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2haopgmqn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynevwfjk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ioinwwgb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtopho.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rinbnmpr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yomsnrba.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2apewglqm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcqgpgf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hnffmsmp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmbqxwa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxqmjub.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrulzow.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2docitrin.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhatjyex.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwzhmwv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyksajx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmwzcpf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnixfvee.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dukanevz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdoegnf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcmecrv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxhebta.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ejloesxa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtbtiju.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2plordard.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2poyjoiwb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kcogftwf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iltsswti.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2joljjhyp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrwpswu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cufyieaf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xllsoevf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2natohdyx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzvleoy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lylopyed.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqroiml.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvuahom.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzhpnna.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuxuqgr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nokgfztd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2khvamlav.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wvksodqp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2arzgtlyu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhnaqlg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbnkaie.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yojqdrqh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2umhvsvkm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pcytdamv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2npfftfgv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqhxqgm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2urlkiqjq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjptxlw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2znlxphbd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fcehehdd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iogjuarz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeonjed.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2htruwfqm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkqhqlm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdsmqqk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2skgglwym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2etbmjjnb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwfzjgj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lqghjmlh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kklreaxv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqpdcmw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2keejuwnq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dketdtdj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2feveuymw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uunewcvv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ippyfylx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2whaxnlzz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvnpldd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqcfuyl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvaqgoo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2msjdlqhv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfxcswo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2horswedr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbpuasf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lantzbdf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrdbjja.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2irnadgtk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhsbzfu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxepwzu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jdprgcrd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyshupn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfgrvsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxakuga.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuleujs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tubhqbra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbmehpx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtlnlsb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2elzhykeh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2irzaswud.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmcpvnq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmauutum.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdqvvhz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkrvxap.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rxritmhj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjavyfu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxtstju.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2irzxtpje.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmioopv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hocckeiz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sohnjqht.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjralga.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2luqwkkrj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iatyspfw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2igjkpmwe.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ujghwttl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqcvoah.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfcoqam.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bimfldyv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lyasteoq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvxykpz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfocvj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqnisnm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhyvqyu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clzlhtzo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfkexyc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuxaseh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2titmkqyi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxozcnwv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjdguta.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyxwhhd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2troorwsq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izmedyiu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kinbfidu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lijmtfco.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mehfljxn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ispmkdgu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfifilv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwavsxtb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzntnvt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxidnlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwpmgzf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdwqwgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiihkyog.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yoarsczp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnyeqsh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmatisxv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2caaapfbx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvibvew.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpojhomv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjblxmyc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2blbdipsi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2onxgxeex.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gonthdmy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrkntjc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2npkdbgxf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uttmwcpe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqedmxiu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsmbjsy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvmrfvo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjovtig.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmicepca.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfxgkai.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2piutdotm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abwyizog.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpkzbtc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uosgwyst.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rekvfcsi.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pejvryga.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpkauiw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwratfoq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwnsfwr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptwfve.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfqbyuu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzosljx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2owhfiscp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbwwjcd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbdxwyx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgthloq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2szcusulc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yccajkfx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfhbnup.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhejqtof.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjbodaq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vipjdzvu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkutsaq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlyuxtr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aurjexbf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzphpfc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2igavrpxq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxskoa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwopugx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zprskhem.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bltrtgbd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvwihtj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2beehntmg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnqthyb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2spajyatx.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnyclak.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdqjwrh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mewcktdc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcjzhwb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhfyqof.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulnfzta.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uflptyea.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xahdridu.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyozotjq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dpejjfgt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sccmyrgo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rupfevot.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwzcwku.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcojbnc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxradif.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzshvpva.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2xamqljhv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2secxewcw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nazhlhrs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvjmesp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dinngnxf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjmvjv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtzdygb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkritcv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fltdcesv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2aimbtpww.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqigsna.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xagdgmfn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikktesbg.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2fexxvlfz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2acwnixei.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhebmot.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhchqqee.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2bhquuexc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwshqgfz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeipgcn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2oygcxkii.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwltauz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2koleempf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsdhltg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mujuggwg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlpddjo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxkcslc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwqxqst.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jttcyulq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfxhebs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhsujzs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdndhggo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yexiuyfg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyuorog.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uazutqok.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiceczz.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2aufgruyz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybojkddb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmaxex.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmhvtou.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltalpyqp.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgakzras.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqxfhhv.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmbidtb.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvjplji.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2syapruvn.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2higyebgb.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcwfeyr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2johtxckv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mabrytew.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiobtuy.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpnmwwt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpqvglg.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmmwfmh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeavvjo.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2texyfine.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uybegfit.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqgjrbx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkxirf.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sppczqbc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2eesgplwg.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2efalyvdx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiatwjlq.html


<!-- 参考信息 -->