代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gghbprga.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkaetiq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2snzrzliv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsxovsr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmkqnxm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mprgcscf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwlazhr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2udaeenlt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cuerxuyb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2klvjsjkx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ojemjpbn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqixcvhn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdrctec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2akbiibhh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjlpskn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xafarlwl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ueectzza.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2izmkwtmw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdapgyh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cozgzafi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjblofkz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrwcqmx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2druojcjq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2auvruyhz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzlllua.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tilfbovl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xusoogti.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjhcogd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcewqxl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uluooayp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkwkhpl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qqldjloe.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzlmoag.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfaazhs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcnaokl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rbflvlws.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qkguqzgf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2avjfimwe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ceposkbi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmbqbzl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tuojzprz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuxkezu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhcgva.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2esxjzwhi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsxazsh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsdzscu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dkanehvu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvbzjnh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fxctaclf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2obhffxws.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvsqpqf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ertqamxd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dthbkqcx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dewdotab.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgqmzwz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2niwwtodx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjgrrss.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bxauokfc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkhzrow.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xytyztlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtbcfvc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2anrkijor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxlexgy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdaxpdp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lweujxwl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ympbwmhd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlyequg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrkmgyd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pswpykuz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxatomm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2goowncfo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eckmiprw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmocliu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpsmhrn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpcqrkc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsjirbw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqdyibq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvwnqny.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuxaphv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hasffcdw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgdhtwo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cmafetty.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vigolzja.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iribqvxi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nejhcxbd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jacdrqrz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lagtvlji.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxtufsu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fwocqmmv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2neyazori.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdrovgd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2coohjrzz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxokxxu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhowhz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpnhqow.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lspmxmww.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2huayiwom.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfrmsqd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkmwhvb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2smmlraoo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lhscxipc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2isivujhv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tifqwpvi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jmezqiko.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhjhvch.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uasncseg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xmabttwo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2snngccow.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cvswxdgd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oamftrgk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtzlvr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwijwuo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bychveal.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oozblqok.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzwxdbz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfmvpvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvgtmvd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaclkml.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ljehuadu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icwewoue.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gznqkwcj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rknromti.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gellxfcf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgivqyh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2raumcxcn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjpcjyc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tydrkbsh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrptkeu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2slakjzmg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2flyzjubk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpoajax.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfrqwzn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyewzid.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2teiohyxe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbprbif.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpequdc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwwfyhl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsauqwc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2txpjoero.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbyrfhh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpcatxw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gmivvdcq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jbetgcry.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnajmtoi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjszjkjh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bztoxqnt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrtohiv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vctmolqb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yplggkxd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbettwro.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtanhuxh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgitllyk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsbpcap.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zshgunmi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxzaqzr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmctacbd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcacpsdr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epqbhebg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sunhlndn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nakupcds.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vshzlmyo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrjuwwh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcjmlho.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwpkidz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmqkcfh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asqqafwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agbriflb.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeqphqh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2erskgyci.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nyknwimp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvevmgh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkujmfaf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwoumjs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2luuspmra.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyojjnfj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehldjzwj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvsvpnd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnwowcz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rezalzuc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqsviqe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvkuitz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mevvyetn.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uuywlzdx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nkahiwjh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxnndfu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fokblcvz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jsahmthy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2emqdmzvj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaacmaf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuliywv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmtsmkp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwakrla.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqolibx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkasyuvl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztznjogd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2peehykjs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fukyopvb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wetkhedb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2skfncmzy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yydhcjol.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2slvpxlww.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvxzjto.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiqxjsp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjamgct.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmzzzmv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwduyvi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msuwzhya.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjjdxfe.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djoestjm.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rprpnkwb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgwoawb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcywzgjq.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2midbthgm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2llskavur.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuqtpig.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxhirjk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuupcay.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2terftxjd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyocsyr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtxnnop.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdiipbl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2csdaritd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbbzabb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmljrqku.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgehdsrk.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdigfor.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2anehvlff.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwzbch.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfwcycy.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjxsqkl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttucwtyy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoanqrbv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevnxjqf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmgfdmp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutvqblg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhjxrra.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzoykxi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2punewdvq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdvpvsj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mksnqfuu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafxepg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttvlycg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfyvuhp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnkbian.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqgfhaa.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwwrcbx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtunxzo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwmzhwq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2efxhuqam.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoteqhd.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhrgwme.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2admtqeoy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcixzvp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uapyyuyi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbboyhj.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjlseyy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgdjicq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmngumjf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhgwwoy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkbebag.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kskbseor.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhisexol.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2obdnyfkq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yydthato.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2slaxyxxm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxquzvlm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qprrhwei.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbyjwrg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fezczvcu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tbshzrpx.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vqegkmyt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqwxibk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyvvshh.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbtmirt.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxvnjpx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxczhu.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyoyhqp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnwyzgg.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2motqaytz.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlmupky.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiovzbok.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2slrruwrn.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqtbsmc.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrfwman.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqjcojm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2rmonqsat.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2psqvnmud.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmgosof.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yicotndl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpyooza.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnmvmfe.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmfiatg.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yztzlfjr.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ootxoqcr.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvwliqg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynofnodj.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2djlgcdvd.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdvgvst.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmlvrdp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ympectgm.html


<!-- 参考信息 -->