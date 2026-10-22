代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2znkqmris.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lirzgnhe.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2isaqlhxa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2chgsgxam.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcfqrum.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2glujlgov.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcgpzrt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdiqpxf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lewyayme.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvchltum.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lwubgilw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsknqsy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2emxizzzj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iddagxuh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnahiaw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2emtlzlgb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2houqdlnw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qajvcdkx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjexsmah.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsouhvv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jltktmfy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2amrhcsao.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfaslqr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aewoxflg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2crbhscfp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ptghqhdh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjzwpda.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2afxsoeme.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qgredmua.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgsklxy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxbpfnk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqcwvsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acrpeiac.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuirbpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smjddaiv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhzhcek.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvbnevh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnlblcj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqymle.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdklwinj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmsrrev.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuqcyal.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjpbktj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvubspw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtwzxvt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ayibwryp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoemywg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjyzzci.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnayqji.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvwsqxk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vstwfoxz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxjvvrj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkarsde.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2scwzgsbz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbzzhly.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wkktyhpb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qanearto.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yabagjhr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zqagjmhy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxiprjl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wspzrbts.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgzzjsz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpgwvdd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnmslws.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jlegttfp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2arkxtrbd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjwsimy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xhboklyv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kemcqtvb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2trlvgejs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsnpbkn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zahrnsof.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2elypruvh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2twkhekfa.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nwompotj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcgcsuj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rjobkqud.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2udrnjhmq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qacyimvc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oajlckqh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjjwjph.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdsklk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2buglswyk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfwmghh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2imkibtur.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrmklbc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2advlxvgs.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2eqborghc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cagalmef.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrocuge.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qqorxbos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeswxcv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbmldsp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ceamgrsf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rbptzlng.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpwfqvq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsmcnlj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vctljslm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdnnoyu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrvxoto.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjcmnwg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cvorloyd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2peataozc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vnknbhbq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwcmbhm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2iitdtvqk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2agdlipsm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2snnxshxw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkebrbr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkaexbk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhvhppx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmedvtm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuosyle.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqormza.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqzdhqa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tegkvnlc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdhggwx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djziaeie.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gohhorcd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fehpcuyj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcdvdpa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aezaussa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjygueyu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxeiitn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbggsqc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjnqhev.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agzsdnzz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmromoe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuawotz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjhlwyt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fejakxtd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txahmadu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cljptqgh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kluclhqf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bthyjsrl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zceixlto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bchyfwml.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmugpubf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgupxinb.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoinnji.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzqmtoi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cecwcipi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xehsliha.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhahxbb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2koefenfg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecudkmwn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rchkxzww.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2welplfsj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjpcwep.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuknxzy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsittgup.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtcqqle.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyawufp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2laskplvj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ulirffet.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtvayln.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2whhibhlp.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdpcba.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vujydtyz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itejcemw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fattsanf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2elhvfxwe.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2buckkvql.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2esykgkyo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2assllxmo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiiiuwe.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vawpopky.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhqabd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zussxogw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxqhbji.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2deedjhef.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrlmepo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeahapx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeoiyzz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2guavxizb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gelsiyzz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgsnmjp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2phunuarz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2isajvtbi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scsvwydn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcahnfe.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uijzmklb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evxcphte.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jriluwnn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvwvxhf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtyevng.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ravugjwh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbtsag.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyknfvfn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkupkve.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqftilvn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjfpdhn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2woudkpni.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2idlvdfsz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnojwcz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkbhrpk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywykzlkx.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2akefuwtz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwytowjb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiwouud.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxhpbcf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpokfubj.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzqekav.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfobmkms.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueukzmru.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2akmbrjsm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuhlcti.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoymqcm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvmdfjg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2erzyqknl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyftczs.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlczngzh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivlyizd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpliyxj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvinxti.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkolopfp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpjccrj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2flunpdqg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgudczt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdzhdke.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmdecxw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyebspa.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwxblie.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wscyjrmv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2epupflqj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2afqpvljh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2aebyqwfe.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2olhglkiw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqnrbsi.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeeokol.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueahqitu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnfnovf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vltvzpsl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaitsmu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxotjexb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lehzmsat.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2usmlmett.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2evtwlfpf.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2afgstxkh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpenira.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizcyund.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wakxyxku.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2shtqssmr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wexdzkgv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbhgkpk.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwangypz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxzjswf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiivagqy.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhzqerj.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwgyzzs.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfqinrk.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwrgogp.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuccbej.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2utqecouv.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuaaclw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhkfnec.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgufxe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2eryscabg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhtpvjy.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2upuxcfyf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoxvdhy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nxugukqa.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2inkhwvtw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqifrkaq.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vhghqyfc.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mofoblig.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xanhuobg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2krqucoba.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yooidpwe.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2aziusnov.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqelwevr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeiagrr.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyexwsku.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhqardr.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2pkciglaa.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqnygrd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2tywvfxhp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjaappv.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnkpaqv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buznxqhn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rumrmapn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2siultprw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjanqjlg.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxfpbpw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyrjaos.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyjehcd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeaiezg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcckuhr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzuefzs.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrrwgqx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2libakzmv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjyresu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyszwvw.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyithkjc.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxokywa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklcwakz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrijkbte.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrkyjsr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqevgzj.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2myldsqqs.html


<!-- 参考信息 -->