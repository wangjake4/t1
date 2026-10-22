代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwxoqmr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdooxkb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxcppf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqcrsza.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqowwgf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaoyxth.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qskdwyzz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zqunznxr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmiujzb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaecbbpk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsatihsj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgpdlty.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcsvfeo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jciuaxha.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wjualbln.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nevfkfgf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2skdmfiei.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eomssrjc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmwtrwd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgmjvgg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2amjxcjco.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhkykzl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdparwq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqrftna.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrznept.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjtwroj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyzurlr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmeuegg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ivolidkw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdpdqnc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcuqmob.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2edqvhxqw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mranvbhe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2smxkamwg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2venipkzn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkzrdsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znbxaetd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fyawxqpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvupexhe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkbbvhb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpvxttq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ninllycb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbvngen.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eskxggur.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpvwcst.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zerbiars.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bommexeb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xakuzxpt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvjlsdw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2niidlkge.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yieofysv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiyrkpy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeoxurx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2asxfaknp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgsqlyp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2irvnrjee.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vavtmwsi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcrmlyp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jujjgyey.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqfkzjv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kqthnxsg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwjrrlr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvefmcs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2siwprnmy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2konogjrp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnfxdus.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hteduldg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxhzgqh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lslsnbbm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyidira.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwrpyrz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klxlghdb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rklxvmim.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2djrnmtbb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kxedvtha.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mmttdyia.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kauqbdvt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ryouuuyd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2osxwtgcf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhpugjx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2unjwsdgt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjyryku.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2clrowxco.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rnndpjmp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oohqevzf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eegelyzk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xifcaeks.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2shsbhnnj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xneiqgoa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvehwruj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzhxxod.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbqpuet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlifrnpc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckesxuyt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjzxkza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqtgeah.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2huzyozpq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2acuugvge.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvkhjew.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zghljndn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofepzkrd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2abhbzxqn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzvjofp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2diaelyty.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzgrpzw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgbyrcs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2svruyiie.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxjzrbx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpfomif.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdgoqdr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2enqcgqqd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2otabwjmy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgeeayr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyslqyak.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xqayrxcc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoqryll.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbodgnk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2eflqgmbi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bqixguwq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfujgjm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yszajbwi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zggqkctf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2snjbzfof.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dspctrsx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyigserj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmztuus.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnldcwys.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlqvgjg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tefagmca.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfwhbaw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fczorctg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pegojnhy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uztukkum.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcibxhxy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmkvpgu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxedciuh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhgpkww.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urogqgxm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2drphivgp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrgwkhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hluqexce.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqurwat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxedtvf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnknldf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnkzlko.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxockddc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwufjob.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hypalecg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dofkhejt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmqkzut.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axfslfee.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkvjsai.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvmrpfz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gspgbccb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziccouab.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2slsqblwr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmafyhdr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpphvvix.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wagfvusb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkywosi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgfvefm.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdypmrh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2frttpqro.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzthbyv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtsaqjq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwtiioh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uskbmenv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hppyfarh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcvzklo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2quqsxbmz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dyytnjdd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowcyhdi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvawmnf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qgehxdcw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uesjorng.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2elooztpq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2defminbg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgagnxfj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pjghbtaw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgfkjjh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcjsbhl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiqrgpo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2muytugrc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ueywnprf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhskvarf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmpbutq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exwsdbuz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhzggud.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvodzyi.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhhjsfr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wugknmeb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbycbvnx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xncjvqzb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrczqwf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhafipm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2utypxoku.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sugawett.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjzeskl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2inpnyjck.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdfbhrs.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjkecnq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlywlqz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuslekp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdabiqjg.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsdlqjk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcxvywg.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2uakydpae.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaxorpv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqicshia.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdkkoqc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2izwvlnce.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiofrzo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nssuigns.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gcffrydc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxoonev.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdxesor.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gebwrlpm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qljrhcxe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufcffno.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjjxhxs.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcqjpvq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2zawedqig.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrzswnk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqpbyyg.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsbmfan.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jylyhwxr.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2woypntxy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qjusmnzf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyneela.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jptjqtah.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdhhghk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyinzbhd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2demhoyai.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciztrxdu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnmbecs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mumnnsoz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tivdxbjv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzpapnl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdkusnk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fronynqf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqifnhdd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2toujfduz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrccumr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkxdyiu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hovtrpvv.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2brbwsfdf.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwtwmcj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztafarzh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcjenmk.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqurepzr.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeglgotv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbptfmlz.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkgarpr.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohibnmvh.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsurorx.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqkaepe.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgxmqdu.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2liwqufvy.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2actpmewo.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jarvudkt.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wiycflwc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoeoitf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hznsohzx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqhqrgc.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qudjiumh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bskxxbof.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2biqjyhqp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyxndtm.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cblcwykl.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxletrv.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdptiiz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzffeoj.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgvwqqw.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tiounohs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzzzroi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvqvglq.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2jznazrhn.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2srjncnqy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2skhxetya.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hoscwunx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2gopscicw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vohgwxni.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2impudqyq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckohmhzu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ragzvqni.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2takedpbq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zadepyti.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bngboaxm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqnlypc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhbxigm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlfwpjz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lasqthne.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvpewhf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2brzilcjk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxdagri.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjnneyr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqieyfd.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaeskuf.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzsdrtf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2reolglcs.html


<!-- 参考信息 -->