代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nwovnblq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2euyojjka.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wafvufrm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2udqnznyl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzdnyao.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhspkiid.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vopgknzp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kalpreow.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhnhtpn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcwiwdy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhntpgu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvzruxp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkheyit.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bswdfmrw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwvkioi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnricyi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcgmhon.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xipsxcow.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzkwocv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zapbrrnf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkipccb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2euodkekm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsuusvt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzricydv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2njmyyjtz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2arleocdq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpquhxz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrqmfwz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vdifnceb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ureukfsm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzcmjpw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfyqdse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvfwtnb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pztwddux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeqbrmv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2sniktfly.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjbqstc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjkifwy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tefmitef.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjekosk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dztppcpo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mijkdijn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vxabhglr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkvghky.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ricpeqxg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrqrvrc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2owdhvvkh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vguntdgt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qzikekor.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hrztsmxw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ytttfwvj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjjpkbh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lmammxiu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wiehmfvp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hbakhfyu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nfffiiub.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjhfah.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgzoyi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xanxeoat.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cgapuktt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rbllrolq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwdzkvh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2knssecmq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwosmdp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrppwsb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdwezgi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aebclmxf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qasjtdxh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkvktom.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdndbfq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxsmeif.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vasbeoyu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zoscxyaj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfcbumv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbjbtiw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcjvmgh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqdankp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2psrbmigc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zztehtkk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2erulcbyq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qaypmupr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfyhxvd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxietqvn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tktxbcro.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuqmusg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiaesiq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bahtkcex.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtvzzkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgswisq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvefrvn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2oufygmsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zprkpqmb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gagcnfos.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nouxnjjq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxdoxbs.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2itcfyovv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjevzecy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fohoppua.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsnmrpo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2onklzsry.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoixxou.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbbweq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeyaqqh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qrefbfxw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfrgjlk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtuifbs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vadbnjvs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjlkwhj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkckicez.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmieitr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jaezwgnn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2utvsnqmd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxcehoz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fypdsuxs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pibvxwgv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbypjxk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plxkvppr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imbhnhld.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwphfhuk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usjeurpk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oukqcomb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agaegkip.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nprsemfi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvrfzte.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkidorcm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtgakzr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpgfnkm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ditfwuer.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kutdujlq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbeohnw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuohynp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zooswyhs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzznsxof.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2taulnuer.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkkthyh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acbtexvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nijxxtyx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqfsckr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksluddqv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtcalca.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzqfvvc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zktwjjdr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuskofna.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pekomjou.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjzhdmf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfgesgp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsjndad.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wglvudoz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaytcla.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeibhtk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkhyueu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimyqtw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxluamwi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejnwdhu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfmqcro.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzkcmmf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2epebqrku.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nypwzajb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fypjqlos.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2idybhhnd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnncbhy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmslzji.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfjfwae.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnkahku.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2suflcauf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oznflisw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2koigponr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzyscwv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2barkeqgp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcszfrj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2snidevwl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2djwcwcpe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjpahqu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sswlylsu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkemlyh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfmmvaa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bscomepe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekophztb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axdcnsxy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxzxnkl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxziwry.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljchfjyq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2obqxyqoh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axtfapci.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hzznpjta.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikejsjxk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2amvtvkfs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fntzmeuy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qotsohbe.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnjucmk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2krydxlpi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsmbnqi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpglqzy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bajinint.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfqkxij.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjsggrs.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmvyghm.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfonyzjy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2feefupgf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpksiqz.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rqosarro.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfblcdns.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2mzarrjen.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihpewbs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwqcbtc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmrdvmi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2grtiwdll.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpslqmx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nydyxpqz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxzqbyl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rekhvxac.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xontwelh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjjhthx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2esqqgzfp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsosulb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpjguqg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eefezuao.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2zchteknm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2lurjhxwk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmfkkjv.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkbxhs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbexwkga.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2avhqfhgo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2haokthkl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiuoxzq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2unrwdqpd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2guwppsor.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdxeiio.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjphine.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfzxqfg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hchglkqr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lndlzgbo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vatlyvnl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrxnrhh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkbpyzc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnyzvcy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2osdlbrzo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuvrbvq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iukegjpw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgbzfd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwauzzxb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjynjnt.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yldcciyo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifalepae.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqdmvun.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jplxftha.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cttpgwdj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjyefet.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrrtmno.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgetrpzd.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aphxtkcy.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hafbwngi.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgbhgya.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsokzlvs.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuhcimi.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2breltjym.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wtasqrcw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqkpcfm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2khrtrxdl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfcmxfj.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkebrky.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2catbqpbh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2seeuwwmo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2olomvuko.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2brndecxv.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwsavqa.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhhoqvg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrrfekz.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jysjpeha.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2oyklegmd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnwaqw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2psyfikxk.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2eekbiobr.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2wccxhexg.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2abkwzylv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2owibiwxi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdhvcpd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjpktrf.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acpiwbbb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dowmvddz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmrvkew.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgeyfig.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzyzbra.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2imbthxxo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2psayakof.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuwehgy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2evazyouh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwfvauz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dymhiuor.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uydncrcy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgbfzri.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwamqim.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuddjql.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2auevkgql.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2knaifoxj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsosjue.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmwwbf.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2slrvbisr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjzwroy.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdvinrp.html


<!-- 参考信息 -->