代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbtqmsk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2shaojjex.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhluhse.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnbqdiv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2oskhkxit.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xukeuete.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxupfhp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzchfha.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgwdqru.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkaouqd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nefccxal.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkssphm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hzshwsdg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqltfdxy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2izebvydj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaewyfa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwcxxdh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrrmdom.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qfronvmp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2effgdymb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpqehho.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgjlcfh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ykswjgzr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqxqvnr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vocjbdbz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdelgoja.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oigqltlr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzmiwmb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fnekdzfc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhostrs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjiids.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaozvsk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2utunwdlx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2grnkmzcd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eponlyoj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwxrcwx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivtjul.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2slgcoqis.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wprjrkdj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2msziqhpu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sswkmmnh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgwdcmn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbljbkmp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrodymzq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmpfqfu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqlrgil.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsryucn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxomfchr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2knrsduvx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvqwkbm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpkknwh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jbocgwng.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2olbwmqrh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsjmhjy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2binwezsf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpmejws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bntmtqwj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjcrpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juubhrit.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2matyycze.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2efzimcyt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xeltdxix.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aurmyovx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pnragdcs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jurlojmq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpipoxt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eowxmsuu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhhpnyt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkxyjsx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lqprfsty.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2termkiex.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2geryfujm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjdzilk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xesazobn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vahuwkho.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqharon.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pshcwvdg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnrpbft.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxjvben.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sqawnphl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eluyuwys.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gimikpjv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nezsbmpn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fepwhkfn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kokyvtmg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fkquffnq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhxcbbd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsmobps.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjszgml.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnpezvv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgbardl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvqjcao.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiqkbmd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2twnquyfc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqpipgk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dujiekjy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2szvvsgjk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2udtpyfau.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2irfcdbco.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oduwnhkf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2exfmbpun.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrshyht.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvymwyc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2quaiargx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qelgzvfh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqasrwg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfhjuro.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsrcxom.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmntpo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvduaij.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfhvqxy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2polniseq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjpzzll.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2whoktbbk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpmffeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azesfswu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2janquntk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mouduhyk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vcutfmio.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlezbtl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtfqryr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnlwfyj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2igelxjcp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyzdkht.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2eodxghin.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ceimiuoo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xornarjv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyihaeed.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcgczpj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrofknq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2uezdiqhe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxivquk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlrchzr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzmalcy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eqznmsns.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2brevxedq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkmjfad.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbxlmih.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wqskyfyl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osntjogu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxkiqbw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjotvez.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epeapzdf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqztixeb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkipnoo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnrugan.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtvjzg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdmuwwt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udpprszq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiczmuh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhojorx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoybvtv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqqxwes.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imkbrbmp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ultygsbz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuyxoeq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dduzgbyg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xheahimz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgtdsmi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rogvchsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2embymmzp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcfnasc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjpxzyn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxljgul.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2avgkhsfy.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvedryxh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rntewqyq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvilwuzm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mldlpzez.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmnhqld.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhptomzw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmcpmgk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxfvcjy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdsicbu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjibwgny.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrgcflo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2akxrinzc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mltuvsnl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbjbfxy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hahhmzdp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uernaqxf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkzcdnd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yaocfynw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbdtjgq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjspuxtq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmomewgt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybckldye.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zutvbfdc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gqopbmuu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjkgaia.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwwxchj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyufrkv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfxbgtx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2chuscual.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzmhfqq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pagzwolz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhweijvx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeilcnxn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lksdqips.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvvxwfc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2neqlqvez.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yojwxgpb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlzztka.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbghcvlj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qejbheak.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsssayl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fecklvyg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wksxyfyk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kpywakii.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghnfvmm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2igceegvn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuspvepo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mklbsizv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtenwzft.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2azlaqmvi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jckybcnb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmqsptb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yaduacti.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkoakeb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnfbikv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkznzxt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmmxvqy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxwwlfh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2prcghkdq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzelsws.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjxxtsv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jngldfes.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nerygnss.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogssgwu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2okmbbgvy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwanngt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhbgqls.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjymihb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ailvugry.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfztdai.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2laiihesu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtgyepy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kixvsjul.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxaccgk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nekwrufw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcskusw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2aaymauty.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2wadpwass.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhodqn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhjxlas.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdxnlrz.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvqwgoz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2crpcdgsj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehqepv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2piuhjcgl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgteaou.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqivpqwy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2hybwijnc.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjhlyml.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaerbbz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nazjnjkt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtnvqqf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvinayn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dehflpsv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sucwdrnu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgjsquv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcilguww.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuokmiw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbgysqo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhrjaph.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpdcaci.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2npyumfbe.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xawoegkl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbewdmsx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvifbme.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejudilwt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubddepvr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xivyinug.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sindqprq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyndorw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtgnbhg.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2euyzsiem.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbthoxq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2woojwqqg.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwehenc.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsexerz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2welhjxlg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcfstxk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xihhpygk.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkbzdlp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxrxlga.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfcntol.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ithhdhdo.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cceytejh.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpizrsl.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdfbdlj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbwsuev.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cemhguoq.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtqxkmh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2segexeov.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeolpit.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mexljwlb.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2wakaugfn.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwrejxn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vobslpjz.html


<!-- 参考信息 -->