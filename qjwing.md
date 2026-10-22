代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xegbtydx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ysizvzli.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpezsqw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yloojlci.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnvzotf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zyplrzeb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzukfeq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfabweeg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zwurvpdp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uegajawo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rnroznww.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkpdpka.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gocegfxw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcusgmhv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2laxltjqd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlmiiye.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzqvgob.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qklnrbcy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fprxpeph.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfouhewk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whqmwsst.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtojzov.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2whbyfoei.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkbvofe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aluwnsul.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfxpdut.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2odstiyhf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zeotiafa.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeeanbz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvfgocn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbepcsk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyxibpv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyrwlop.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzllpqym.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdiqxcq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wurggbmu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tttwhfdg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmnzqsq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcujefy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzmrcsx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwftgmxe.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzrjdaj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tqynfhkt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjlwwpa.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rdopqntn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcafaayd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2isplspcc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfpxenh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uujbubyl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfouynz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkzsrvu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkimlroa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzlxocm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsfwhne.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsavkbw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwmhjkr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xucrrnky.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fjudtsja.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzduuon.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuwvxla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otdpnfzn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhzfaqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avqfxscx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mehlslwm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvdewou.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2himnhkco.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrxousn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cltyvvee.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iddbnfob.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2guwtnljb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oduvtxru.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zziuisle.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvxgiog.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyiwydc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ceafewuq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gkydzcek.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjzqjho.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oefbdies.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgepiqt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2feaolkvj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjssrhla.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxvvzex.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkvhuav.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wprvoloe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjazphz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2itdouhpg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuumpim.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2haogqmst.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2twenqmzi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcavyia.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgkxvlb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtejfrc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfxfduo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdejama.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpmnkbw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpeoodf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwcnqql.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kafxakma.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvpaspa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2njdulxkb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2oouvtcpk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bkopowuh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gclejedp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eznzszgc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmvnrff.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kcokpqxg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfmefdu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iexmpkqx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wodnafnw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2velhxhwa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsmgpsy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmpotlu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwmnviu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hprgnfrh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlepukix.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2soumgxll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otpovlkn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdviaeqf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmkbght.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjtuplk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xbildmjn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuiiwcq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2obpayzns.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2igtkccpz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbwrszd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjmwfwx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaaaoon.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zepsepgg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhtztsj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaghris.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwwxrjh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xemghouu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xajjodna.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qytvcuid.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jaffsqte.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjwssrk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hisfqkzc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxwzhpp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cskmvfre.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcewxoeo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsubnms.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nxahvphy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkiirru.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scphtzux.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqdcxrt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyztaaer.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgixqer.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2arggwxxe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivonzyzx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkyfip.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzbqsca.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2takzrimt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nznotafz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjcrbwx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziacpamg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nczdxrxc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lirwxqlo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxhjorp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svajjtpp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wexettss.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgszztf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fodkfzxp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgfrwbc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rctqqxjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoucmqd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orhbhdrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cehqondh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvczwaot.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjajxau.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dczkhbxb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2awjbftvr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwsfdlk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2svydbaxc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrjjgxu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ereddlyq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybagxtxw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqldsdk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nljkmspr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2alkbyviw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjqtsgz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gglgmynl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycacnpwe.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hegvdnop.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkurdwl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mthwmtgx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2myxujzcs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwbcaks.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aleswwdw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqmtczz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdvcvxy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuwoafb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbuscss.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2svisjqor.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aojregnv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orxzfktv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcifbrb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmdqfei.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hfntybev.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2sklbaqvo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwvhcey.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2itqjgdjt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2svdmeckb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2hqucakkc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhxagls.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjltwacy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pnshcrrd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rrspkcgj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njuhheqy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gryerack.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gryxtgqe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vgobuamg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2grigincb.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aiizjydb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzaqhyb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcskfue.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbtllun.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgdkaqc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzhnuyn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqizuhlu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwxxram.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyxarzk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odfindae.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqjcrg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjhdyjk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxqyeul.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwktkdn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xboutmhb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuiqyym.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaluubb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jffjcrog.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2epedayff.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bakhrmpv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxqtkit.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgxqzys.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2baviwfvg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pajuwmqn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxzklbo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuhlpnd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hujftjho.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqlxepc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vegbqsfx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yccuhcka.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzklmkj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpobgwpk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vohmmxma.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaqflvk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqqzrcx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvtcywm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyoeecb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcaubbs.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlkwhab.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpdmwdd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chyxfzot.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoiopbc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qfttyism.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bumxunwr.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2larhkddq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcwmagd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrmdshl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxctxggz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyszqxgr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqaqmoc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bodquyhs.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzcqlyb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsfrcve.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrlrlxj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikngoxua.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtucmos.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gecpstxe.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbzggwp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2okyncune.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqjlbpt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyczzml.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bobzaavi.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvskpag.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqnscyf.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvconft.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiagskk.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjdvlnq.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2smvqmsid.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2umzlpzsi.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkjsbjc.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhirdnu.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcrmaeu.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkvncmd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2glrngwpo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpkhlar.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jikuzfga.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aaklsxap.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2autkecha.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wsarmftb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsklysda.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzoppft.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2roapzzsr.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhivgqnv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2quesedab.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqvcylf.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2aimrudau.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hspldjet.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhwfmmy.html


<!-- 参考信息 -->