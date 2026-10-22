代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbpawib.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcnwyte.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2evzepvux.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiuiucq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcpcwah.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zztkbhjb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgmeff.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2izcjehkj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2orcckizs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pymibqrz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyolegg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkvlfzg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ucremwxk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgaxmhw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfabhiv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dahgttip.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhrqxve.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmatvqe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2topbsocq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetlrttf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaerfji.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkxotge.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjockmys.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlqkcyj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bmafwocp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhasraw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dffbtupd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtthpky.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqtiieb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2txpgdqhh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgrcsuj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ferkukad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ourjfwbc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bipvlsjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnmzkws.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2omydgtvg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ldumetty.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvcaemc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eucvsvra.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2motqjmas.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytirqwol.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxvqbuc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyxikmu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wvocibcx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sauerqct.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kxptmrmx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tzavtlgw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfshvor.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdnnces.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqiqtqm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2znupvvmn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vabetpny.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2unjdwled.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsegsas.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvivydk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2augowdeh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fkptbgsk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnddvad.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqufuya.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajwrop.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2oosufsxb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdssmlt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlvfdjr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kyojwghi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kfekjjad.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxekglc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2srkypuvp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ucltagqd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cstljfjn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpnrvyu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgocfkm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxdxhjb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dujroxed.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xefmhrmt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zblmpexl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2neujibbr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmejrbu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hugqmuwu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbfvkus.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxkbwop.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gguxlbak.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmzdvgp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xucrmbie.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ushhqhli.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdigixy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpukrpv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bhataukh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xktfsqfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcikogk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vagemkgt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2loznrtff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaxdmlf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2elgdamzb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzucylz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkechdf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyuaxnd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkikdng.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2iupchtal.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvnexmy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2yztdftpv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcnrddo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwrqzcp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2msbgkfsg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2evzbjprv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqpvoau.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrhlzth.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2eslkfvnu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjidfej.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfkjmua.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xeflnwsn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2glmbvilk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcawjaom.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nekgyphg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcktfvp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqifhfz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prazhool.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkqcnjj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubihelfn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjompzr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjrjtut.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nexjxull.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxjsaqx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzvucmm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ealarzyp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxygxefk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdahrpyc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmshednr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbvutir.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azlaseky.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkekgoj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zutswynd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnuzhgi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjhtkza.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rghconyb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyojapqj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfecbyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbelxuob.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnfjsae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doebrfrx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiwkzev.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcisggk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaslkzc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzvajit.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaimlrk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pomdrldm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kotafzro.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvcdkhq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyterheq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ughwnwzw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwfvafp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjdatge.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlhchip.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rphsjblz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvamppv.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkpujyw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dddniwdc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mynuwfsd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jpolplnw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhqogvo.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjnydqk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwehvakk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2imzgnzyx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hthqrdwu.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kohchqmm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sqglpzyr.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrfxwer.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfxgpoi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsykkin.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urhgxyyc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrmlxfl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpwkxsw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2etivkham.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdapxtl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbubtvyc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgvksso.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdabouy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2etpagfsa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkvwiqt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aupstmdn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrmhaep.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kliilbml.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blrjtcwk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkjoryg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scyihyte.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2opqqlsnr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdytsvj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjbidzq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrocxpsf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmokbehn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2injtgzwx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjnixdz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2aofdkrvy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtqhxpu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oootsyuo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbkuwna.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpsjcwa.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2belqrave.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfcszzz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiogrdvd.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxkqtvj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvxhlvh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkswqhqo.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwwokwd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vptnplcw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfcsmmz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2diqwiwkn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2viayjojy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lctadsne.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnbsmtm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2pllbxfnk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoaikfx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaxiapg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnjstyn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyeyamy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yibtnpnz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvypswaw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxyihbq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2acqpdlnj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2utkphhqj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrttqjn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zapvqkxq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahricmpf.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpgdiyy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kpidhnqs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhjatul.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtqpwat.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2wgolfask.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwymxgyg.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdhojok.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2vggzcflq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjhjipd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dydzlekd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwjlzjj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhjkjuz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuljdim.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuibnhl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvewyovo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iftyypyc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rotnydgw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2baspsbvt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkdjmjz.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fxggxyvr.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuyqgjj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2biuhteny.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfumqdf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzipdlu.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhttbnso.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2nynewexf.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzbykyq.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2byvfarkv.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmvuflb.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgluhcy.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljamhifp.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2amoisfhk.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbomcsy.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzlpazw.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iwypfqas.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrkyjmm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmcryzn.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fepoutmv.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnwdath.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2noktxywy.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxcoccm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqnebcp.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kogxozcl.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bovlpvmj.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2fohatskb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2loailwat.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2uklcpraf.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2faoiaqfl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2yywspkvn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfhorcp.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyuiora.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqcpepd.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfjlitb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2utubnsnu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2jneybpuh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkjrdiv.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btzslydv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orwzizyp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrxbfqj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlgaysb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyuqzgf.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiunxin.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiafeof.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoihcoc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cuurrlxu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmgzdej.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjemtuz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jypsqime.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpkaqoo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2caoccbdm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbhakwe.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcrhptz.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskasrym.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzldxytb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyopwyee.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgfknku.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfadebf.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzyrpqt.html


<!-- 参考信息 -->