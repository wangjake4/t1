代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kykxoojl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2axzceacr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwdmiop.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkyqbcu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxvctfs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtuwrfb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jexufypp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mozoqqul.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2awucwhwi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zispayjf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bebwknqe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxviznd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2srfilkni.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgnveul.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2enploklk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sbltrdcf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrsmruv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpccbltz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsrdjhl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vascxwui.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nekhtuxs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wecrchfs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yioxfcey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqphwzzp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfqmltq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbixcnok.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocndsnuw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbirzrra.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2trhpfbhv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pejldvuv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2efmuktmz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pkloywrz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwgvuzt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaryrxj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhharkqd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zedyrmcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndidehap.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2exvwwdfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bepdfbfq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrsxrmi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dugrxacy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tiphczip.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2roognyde.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlahnyh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lclbclqb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2leopusqy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xxifvutc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dabexsvh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uavoxplr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bldliltj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpqdaak.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2joxvcktl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2obfuqdcv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2drzsikle.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsehfkm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qegznejh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2miezvahc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2idkueugi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2knzkidcb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2szxlvhst.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sizhrrbu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sirnemyh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gahjjytd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tldsenif.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfucxrs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2prlebbfd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybpfsl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpzxfzt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2saywsgxs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zhisqntt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uszqgyhg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhhtijj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnuhvbt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oljnjlsc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yjndegie.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwlshqp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmmulyb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlnqfth.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xxanfase.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uubsdilm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2etvuogrc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfufgsn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaxktjx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qslrwwzf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkdojzp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aamjkafk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxgubn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjccojh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzonerx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2szxeiffm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rudlaewu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkdoxuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkwgaeb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2movdpfjk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kphshrqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioftotvq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhsxcde.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mepgnehq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfnddtf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dshgvmca.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxclgqxs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gqszurzv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkztmow.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sptnzngg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xjebrcjl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2oarnfbjx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxdysqh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrddzqk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2widvdych.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uzryyxhb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ksarkrck.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2axncglrg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxamybp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgmuhxt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjrrklj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlufmfre.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2irupgyfl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyoupfd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhwgugy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2poxicxgb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hragttpz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvmuizv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drfzyjle.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2favmxkgr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcfxoiy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fekkldmh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tofeghbc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtxhohw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dexrbtyg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owniklio.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zndbuntt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qanjihlh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwlyxhn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsrxrqu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2famxvhvt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrotasr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxwkdnt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aygdvvun.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqrgjsi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvyosfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqesmdmd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egxcgsal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkumrpk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2grnfchtp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdpypid.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2junlyvmu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyaiotc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzibpofk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtozsbj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvhucqn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpolxhxu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2brzumwvl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrldpth.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fkngizhw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsakykg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqphbbu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiyinki.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfatkhr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uapwpxsi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fritzqnz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2akdsfwii.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cmflzqqu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2sfydtwnr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpkgpck.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmlmenz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgkzjnl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqatpsn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgviqcv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvrdcxk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2urxsabyv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccswkpqm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwijtlft.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsgzsno.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2aabzdwnj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cngcnuni.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2extliduh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxqwrdd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zukvoeks.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2iciqzhyg.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2moqsigma.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxrfsqo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vcspozjs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoyfssg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyouepl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhoyxys.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2voangcdg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdykgtgo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgqmkre.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zurbdcqb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsbwqep.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2imjcmjmz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxlihhd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2moidvcfw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsfuugn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmvemta.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhctkrz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziffsaeq.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dncmrjae.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrgsybk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpzoqqy.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwxyekd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kchosvrf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuutaoj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlssbys.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtinyky.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2famxzbsm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgjdoeu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2upafwbqi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2caadcqbs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeccxcl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2stuoyqro.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzipnsss.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmgpubg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cnswtild.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvkahft.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnctdkx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwnnkwo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiynbtz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuhiejd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjkfrmp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jclqwpzp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlfpvks.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdmzojy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdzueuq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxicuum.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojscxqpu.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dynzuscq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xktikgiw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjcuwdg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrdkwli.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtdhprf.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjzpzgj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwulbbfe.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2neeodwcg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaykrmf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2njteopfi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaqxtcd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuthnkss.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpegarzx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbomapm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqottcy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiuncpw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2erwdbmii.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoppgzy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjmnrbw.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqujqzj.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvhttci.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkneqlva.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhvpwas.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yngefnkd.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2giumpmlg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwoojov.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2clhkkznz.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2faiwgmnk.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqittpxb.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2buzlolki.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvbflid.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdpsiuf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjwcvyy.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdjqsio.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2matdhnpk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2vfetmzjc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtmedfl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ieobwdvs.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bgedymfk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vyberqjx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbdtlrs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2kouamwav.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nptbtosq.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2edstihum.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2tikpvmds.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzjlmhz.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kprmklgn.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2apwdgvlj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuuswuz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkccapff.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2bteoytgf.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2izucegpc.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjdpjri.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxlzfti.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqhnanq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjomkxi.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arhgszdp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrqvkuo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2atwhbsgo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sdadpqhu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxzyjaa.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdzsnhw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbximlba.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lomskalh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtyvcxp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zscmgkjo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjuomot.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcajzcjh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivudpnnb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2arcukjgi.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gwogpysv.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwksvee.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiveztt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmiqwh.html


<!-- 参考信息 -->