代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvdnene.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyyxquk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwohoof.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyvctbh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oenjbgsq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdjqgyr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmsxral.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwdvyec.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ncabbobs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjjilwe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2aumkysvu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sriblerl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzuhpcj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeefydq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2urajmuun.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtygfxl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2irlhjosp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2knnggrnm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqziggm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeupfmp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sogsrybp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeyuamt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmdutjs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eddmkzfm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkmelxl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oaghnucc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2twyebqpx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hnswexou.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2umotwwzn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmmmstf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkemyegs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2inrqbvfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfenfhbi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcgmvub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wixevdtp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2izyvhplv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfzxpox.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pftsvevo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2apzzrdrq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dnatckgt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2suqmtani.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qgavtgpx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dswzksoi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyryeymh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2edyeocdo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2avhaxmob.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2taavkdzs.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkapbhg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgmiwk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhoamdl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfbeeen.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvpxivv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjwftwr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efcejyse.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qtryzqno.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zrckxlme.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzsucmn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fxouarby.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfwhqoe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyuvtsc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sasygxah.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2orqsnqol.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cezjljqe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yfetyorl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjouwiir.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqswmin.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wahxzhuz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qodiudit.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ikalqrig.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bspzxwyv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nllkkthk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxtpokr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfisfph.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2btwvrzob.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vojztlbn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuadvbv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mlymjegq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2izecswwz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2utzsnghg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2auznpvbj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfwpzjp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kaygkzot.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzeaojg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgqgmqu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mhynlcwm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkawptg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2smldzqik.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2imeakieb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfatayj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjyxmul.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2adfecnrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qallefdw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgmmdxc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkraxrc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwahuip.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qacmkxhu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoaears.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnmpfrq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2npctjrko.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcoizpt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2overmbci.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxjeciq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcjnltp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjgcjcw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvqfgmw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrwdslu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjahhyil.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjftliq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoqhvvo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uphyfoxe.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnmvisi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yccdsvor.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhltild.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2filgeiyn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkcnkir.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuenglnm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqvlrpd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jchwmgmq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2npiwaapd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2timxdnyh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rirhssaz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqjtref.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kspksblr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbrbfcx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prowjzuk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdmowbr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltubnlgo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsppueev.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gelnqlee.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvssrrxj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgagqlx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzzyzkj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ittevwbc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glakqvas.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxcxbg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oifevtst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iudcctye.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvltjhxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiabung.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kiesdyjj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxqksbf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwzipzd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmnvwyd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhpeki.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hywtbuyh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cukckqgy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvnqbdw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2auwnstxz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2azrbaesj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdioupq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnpbxnh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sueqdhrm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rztjyjdn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuevolp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcfeafo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2naunkkwg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdakcze.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tyclxqsq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xavxrtiu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2txbumszr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyjsbrh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fldagjlp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzfmqon.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2djznwgyl.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqycoro.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpswygr.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbkmhzk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvqhxpo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrebnuu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjkldvm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2udipkhhu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vhldcatv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwlmxzd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nerkwexg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gizpvjep.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kakheinc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pcapspad.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbntxlew.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxloikyn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhagurvz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyhmajq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzitjzx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csgixcnq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ryithwet.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpywqpl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2swcbgfdv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdnroql.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqezvcj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dprsqbys.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtajmdnb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfrygfx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qixqizjb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjptdtl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvlgsoz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2decsjcmw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlytblj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nikosauo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdemhjd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtnrklu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkhzewj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpsizhr.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sflhiuoa.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2tuusgwwc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2esoxsptt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xstxdtiz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdexklu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtdpuso.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzhhiao.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yinbuyno.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2savauoia.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcoskvn.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnenzep.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbikjtph.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgohjab.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiorgtw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjlbytv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mekgyyvd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2tebnzsgu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbzuikq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nizceozl.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mivqoeuj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhoxbde.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwfkimt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2idxdtmlj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nepfxdvn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrunccnp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlhravl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2swjekjfs.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2abcgnldq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvnruzl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2riwxravi.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvivhdfc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjqudl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tccjdfhg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpupedv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rqogpijr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2huxzmsqn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mketgklo.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txgtdfjc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbsehmz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2etkpagpo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxtsfmu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqceywt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagqajml.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopdemxd.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfcpwkm.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtvevnx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtyjaem.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdwhgln.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktskesev.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aptzfcbs.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmohkns.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jceppbap.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxaqtkr.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzolrbd.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzncxfrf.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqkcalp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwlpjsw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2azjhqzsv.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwstpmg.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2evzqazmn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcuymhl.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xruzbatd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvlwfzk.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mymrkjpn.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsgsqvv.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcexocwe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2aysgvezy.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qubilddn.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeakjpr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xweffiac.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2evcqyrde.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrnhmyp.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jygcnqto.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwqxoak.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2prlrlgyh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdekjoj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmjclsk.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gborkjpk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kquwlhzs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jccolxyo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yymnzzze.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyqnkvh.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2enluggxr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bilcfrob.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2omjlvlbt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snisqtea.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gahdwzsz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuqxbud.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjjcgaw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzffuyw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfukavgm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjuflpi.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazqzidi.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqgsutx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2otehjfnn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnicdctr.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2ictkriia.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhvxysl.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2nqecqsyx.html


<!-- 参考信息 -->