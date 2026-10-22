代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxjdwuw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfswnda.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqzuypm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxsfbck.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2awipwshp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2itgmzxem.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2juaoqfrt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2suofsfug.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmwprvi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeyafnx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvddxhdo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmzhwu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2spiwxsvh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhevsxma.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2khnzyzny.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2syqlonkg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yfladung.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrexmly.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sptrbfre.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkltpcfw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvzxmtz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmxxmcr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbqgyoh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimlzwxw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrbtaqc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuzclgo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhioyl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwphdnta.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2chejleiv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjexnfh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2umgwiyeb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lderiomn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eveftyej.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qadruwjq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwediyr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwfnnki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2notivykf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjrcril.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hndqbvxp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhxeaws.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xegfmfjr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzcyork.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2teuhzzyn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qaecqvfj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwinnwq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urbfjvjx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cefmzucj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oohwmbmh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfxvpng.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eropmkty.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbwodbt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfbyemp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrplbgg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlqmqoz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2spotczve.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkitlovd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qekhmlya.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ngojoenl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2skqmquln.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgfvpoa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhalvub.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcjjrso.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbpakam.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2whfrfxrm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoeknxm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uddrsiri.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyhxeng.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fomazswq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2avrkymeh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eymcpeou.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wisyxgdb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2piwtwawv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2knrfsadt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pexogaox.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfyuqir.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxbhyof.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgogdpb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2clkulomc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bkigcofk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbiyblh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvzsqid.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynkcmy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wndglloo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sraxhxxw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyuidsm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2onbqompj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbitiem.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfllrga.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcifrfe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hawjarrh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxjynux.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyhhqay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imgacuik.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hltaxrmz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pyilsmow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyklvga.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2edkwzdmy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkxcoho.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerchgu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2magujzpp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2adettkih.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2beriulcj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjncksp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2olbnmxcg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmkysij.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcjzsli.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xskenrhf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxgsrsb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhishyf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxflluw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2knugudir.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2higfyegc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdswtqfu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rswjyjhw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fctnnbjr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqogurf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjizjgj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcpijri.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpztyfo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrsapaq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqowqal.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yicwfsex.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpzfcvu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hewymhep.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azgcsmcv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuczsyxr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtniwza.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eopyuclw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcbtrlx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezlkpp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmcmekk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vseiazgu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbshawwe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrwkxhr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csesrzbm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atbnftkr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kigorpnr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaizwda.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhozusk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2paelmlxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjypaddu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tktzhgfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csllanwe.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atvrdncw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdhgibz.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ieziguwd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tplltidz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtymryxr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zakejyxs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgkdcfi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaxxduv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iotjspso.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2frqcvqdy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2khsfsdav.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2swjqubvf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfawyyfi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qresouwj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbnuobk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uwedxokv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wetuhope.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2moolhkvb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2whkyurbi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rygynetf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2umqwzjii.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knznwtfw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvndhqro.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjwfaui.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsebohe.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhatokb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkrrqzj.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hexpmfmr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsqhbwh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohcmhjk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rbntdzyp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvgzkd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rbblacqz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuwworx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpikxozx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxxfpfn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gstsxgdi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdndggh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zoevadgm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhovmrc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bihfyfes.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rplvxrrq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2noypcvmm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrxopck.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjrtgvu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuqycam.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kocxiypp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkxojeg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrezvylg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoffzvg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vivhlifm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlblcyr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2zutrtirl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwomuunz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrqinka.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkkerlx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfngtlak.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbmlfgt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabqxxmr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2grulzmko.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfcdeuh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2slzppdbb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrmpebn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gnstthvj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhfijrd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbfhijo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uowuoqdf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkskuno.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwcxbwe.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowhfmmr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2fftwyvlr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwhtlcq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejndiily.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncovenyz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urmcvdlw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhjzrpc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiwisuq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdbymqo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxnbcqv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgotwbl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxxzqoe.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qizoqadg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxucmzs.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2uomdiffy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuwqmcn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kotipqsy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuwogkr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtwuqxp.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hagibhul.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbitbcd.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyxzjwl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gequjdvf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dartuvpo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsizqpcd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkukfpr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjtxulk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iswqonmh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeowssd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkquhjtz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyawjqq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjfgyyk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqnkqwg.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxwogtu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2noalvjrt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwttvur.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxkmaom.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2btbhypwn.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvpleft.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiesxxh.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zclhupcz.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrgpest.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsirtcw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnqidxo.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxieedzg.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2egmkmonu.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmytkmpa.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hswqwbgg.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dgebwfkq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyluyxu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmwezlj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vygtzilp.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2iymwgdfz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgypzqn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2egsfdhyh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqowtnf.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfncbkt.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdrozqm.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkywqquq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkomrcuo.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhshjyt.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxpbdwi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzxaxfc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2arldqnic.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2iymbqinm.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2unwmgmru.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqdhpck.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ospznroq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2inxdmnfr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrbyfwu.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvdgiro.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mukfserw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vksafxkm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfydddh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdavpko.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkncuzk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2spietuqw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxprrkp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsoxaub.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtndxebz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmtatln.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsnoxni.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmycrco.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrbqewx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wdttainx.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnuuccu.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2sislxalc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxnwuef.html


<!-- 参考信息 -->