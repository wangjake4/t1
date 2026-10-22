代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2srrcbnon.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wskuhmua.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dyduhtst.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yydeyvkd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpmhsei.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdgkmvf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ghscltxb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbdjkka.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2blliigaj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcataapy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prqjesix.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgxrhjf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnwkaef.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsrbayt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpocemo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdmzruk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcszhlo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfyqoyy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2earvyrgj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqpfezk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zvthrtwl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyitynze.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmkvxco.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsieijdx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xwohgtix.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtsczii.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nlonpkbp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfczatg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhlczbz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2grvusdwv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoraknx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuabzwqh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgjtrce.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2noqmgink.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yudntkqd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zallxerr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sshwarjm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lfldynnn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbebzmk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fznhnmru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzjxmaj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tykzbvkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgwmnyf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vhedxxuu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yzypebky.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuqzlam.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xydkzibt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hoztfeft.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cawuixuv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnddaou.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2degovrdc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqxiwew.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2soofqvyo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2awwqhgyk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpcxurk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2oalxgxwt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmvgfgg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdyuoov.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmsphvv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhnpxho.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxfypir.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqrawwl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2guwmotyj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpcbgdr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkcpqnd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2srdmjzre.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfkzypj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzbsuar.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bqidmrsx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yvomwmjp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhfkzsn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzarqgk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ithquqzn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqdgoxt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qadyagxk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjjamxy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfngqla.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2swpymlql.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gspntwyo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hdopjffh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsykdfa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sbscrcbq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jssufjpf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gucnblwo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tcueshkj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nrebcanm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aybgvjce.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pydjavjx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lxusfkdo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2didqwezj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2drwcsqkn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkokbhlb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqiqsit.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmzyphi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzhbmmt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrwknfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saspdbeb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbxtkuq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqaouwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieylhqzw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2utttnptz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxovwfw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fomctsvc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2exbuuiwh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwsfrda.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwtmbax.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdcuucb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcvonaf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2popyvzma.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxqggrk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbilckp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wcosbsgt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjycoxpp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaklcma.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqkcyyp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2crnfgsqk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lrppviua.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfjmpfo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2igjzvlyt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lajbidfu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmzqtjw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqkqxfp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rvifptpk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtidcqq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmcvngr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2beneyntm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdxqgch.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxgwof.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2loovkiuu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ootdvdyr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auqrdjpn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjwuniy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jruwgxny.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfiptov.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvnfrkq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsgjxhl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhatfjs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxkxmlp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrtsfjj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2undxyqqi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qplnehug.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbsrnxk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2awqjnmut.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ratzozpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxifxigl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqcqjge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgsrfsz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uchnoewh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdsizcq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsazgfz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdgcilu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbpmnzy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fffdmnqu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2frmjoubt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2aniiydjq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wukwmjtz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2grqyfejp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tlitliqz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjvkvow.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjzjclx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nprxgovf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uftbskyj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzdwyol.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlrbgnq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvpjhyr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eqspcous.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjkanvt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsjrzol.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgasxipe.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxowbvn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sromwmce.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrbojgv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzobzja.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2spguvpdk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpysxrw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlkqnge.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzfiwwm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pitzxgsn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvttviv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbhisxo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsucarlk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbdpjaf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fffwsmiy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2smzczrmo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqexzkfs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bycewzmm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwcoyov.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvkgjcz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vojxjzaz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oklsmcwo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzvedy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgeqrll.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lrubwxua.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2guwrduoy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2opaqexnw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yycrmpmb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvsfddn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhwvsmz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcqfwti.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xqabloag.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvmoxcu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuvpsfq.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgqnrpt.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwueklem.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqrepiv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ninniwfh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqphnmh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuhhifu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2wlospczy.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkijupa.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2izzxekxc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhyougl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwqyqtg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2crgboqcu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2brblpidk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2utqhkaca.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzshtfcn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2agjadete.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoohiqw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuneqyy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwqoyrb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvbbajj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wovcaler.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2epibsngn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrbybcz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2idphaein.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrqvmcp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlryiagn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtqhgui.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wksoawok.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2soaubliy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlcwxc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fieewepw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lohznazk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mnccqqce.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocqzrwi.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2htacmhey.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2inapnfbx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkcruzx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hopbcnea.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmtqzex.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iykzalhz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyqpsih.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2awuwhkgw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwigeat.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarubyh.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiznfjt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2caqzgesz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljerctlz.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xeelnndh.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjumrzl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjezkcx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvpsvbv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzechb.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrqfflr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmekgewi.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpxkikw.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrolpo.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmixggmh.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzssvte.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2alwpuavy.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbsiaij.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyidmkw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vurzauag.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtqgnzl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfgoyfc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kikgrags.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwmcekl.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2omhsdaou.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvrzaic.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjgogkh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2prghvwuz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsugrlh.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzojhxiw.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrhdnan.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2egbfdjsh.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkigonnr.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hiabspne.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzlvrpq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbclewdb.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfxekhd.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjebvxty.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2ouziyouu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2txolsxdj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdywxtnl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qjptpehn.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqtuiky.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shdxluov.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnkkpga.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpyffis.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vstnhzmv.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcucqxs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsrnuam.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmzqnxs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adamazqn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzovdxsb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvfzxoe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qeamspqz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwarqkk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbwkwjg.html


<!-- 参考信息 -->