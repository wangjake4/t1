代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkggnwfa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2djstfebl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsbgsgv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2snjszxem.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2whkfnlfh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cadxkwwk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vduysosy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jioxksbf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkerdam.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2forvpqet.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrewrew.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2guvlbkpj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hgomviqw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dybwtwmh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqdtimx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkwlxbb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ulawuoeg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgklaxop.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2klajbghf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaoydxr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jczhfvvp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyxqusa.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhvqbrm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbydixqc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvfyaop.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtquirdq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gavsiiam.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skzvjvtx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yagauhmj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lethskek.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wreamlht.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2stfsqtcy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xvghdqrq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ltidtvok.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzladbvq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oavftvfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjjyvcj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvlbqrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzbaorg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoxjiiu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfusuih.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ziygpuiv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ifscvgms.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzvthoj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvkimft.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wtftpuad.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvibkfr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzhsexa.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xfopwmdf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwoqhcb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mzozhxsg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjkchsf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnztizs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmcdylf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2weghrsku.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2amgvcvbd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bloaltjy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jchvrrnk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxvwqzu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2chvooueq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwhaxwp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lqngbhnp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aejbwszj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwhhayo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2neetxgzi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhpphak.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cktrukcy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqtapkz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwvfvjf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgilcgy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2buupgngx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cenkfksm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oksiubbp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oypypiwf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2masrnfip.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2agxnylkv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfwxmoz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbdkknv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxsgucj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlbadim.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmjovga.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsoiufg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkkyfwc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yntszekm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxawxhj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnovltyj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xohjlajm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2azzsjred.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yucjqtrv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljagtahg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkwkjw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zntsnhdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abqlhrkn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2unbvycke.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fsogmoav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvzstjw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2aihyrqba.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2eluymwmo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gawksbon.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcnrmjn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgnpsev.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2shoiwqwh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzuummt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2arywmzwj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzcllha.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2coedello.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkhebzi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lljuopyh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqwvlts.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeyrsva.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhhogfe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrfyavv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjqfpal.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2awpokjzl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2irkkhxgc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2unqcenwd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbdjxjs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ewapevrr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gfanuqip.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdyxohm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fagmrssp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtbfezz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmalxwxe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpligjb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdbxutm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlszezdy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuilngin.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjotbrn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuxttus.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmspkvw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvdxibi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2apenjvad.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zovalzpv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzkcevn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvxjrgd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guddmysp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrfpdpu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2athuomzw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixecrizf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcecotrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmqyozr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blaswami.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nulkufoc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqdzhcz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtokunw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxszmeu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2buvkxvpp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzummfdf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrvvquc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvsigxb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2szoygupx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzefoye.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbspgkmf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mowfbfko.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kutafeqf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fleyyjdb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxoqybv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkxzmss.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hffwfsfw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsiudor.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2srzggmtr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqxapdi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ipidqfdk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhbgbmk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbjihvy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxufryf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2akaebzzi.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2izwzwqrl.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqghinn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fitjrgdl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chvjaeuv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nykcqcxp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjegxvj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uoghvoeb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tqofmahk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vnifsjif.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2efmpbxry.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sstihxrm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lematjtt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqrmij.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2idaoqfbo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoyppzs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhccejv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqavegif.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qddsnuqv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxjsrox.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwndflr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjngnpvi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2urkomzmg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrkhibc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2erpwbnfh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbltogl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpeogwv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfixqiog.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsscbtry.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2nylraxie.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2chkyyfsb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnyvugz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnusaab.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwibfcpd.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2igwpgslk.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxuivlb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2drqwsybj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhoqrlw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xoengzoi.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsverrv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcsevcx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfnomjz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcutynnz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhbxkyx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuerphl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevcnjxj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbseqgmf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2uoacngpx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvwplhi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2chomgznn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phcyrirc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbytozur.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjinmmth.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhieele.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awektfnz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhaavov.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmvudba.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqqbzcn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lokjsazu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhdyfez.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2chvsoxua.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoccyjm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmszufi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbrxtf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdkgdxw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsybnqoa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ususalpm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqydwmef.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgrwjdo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2prfsweuj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcbpwgj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhlunrr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiqandz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2shtfhres.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrvcsip.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyucbtbv.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrnldbn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeabidjf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtkftmb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwrsqpn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mudypvhe.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2godfgypb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskzvcam.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcarwuw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2beohsvof.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfqhnvc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaxupvg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyolwmgw.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqohzckf.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aljavfzp.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bylzlrlp.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxahbuyz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdiuorm.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiulfisj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvfjxrv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcrwicp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbevfsv.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlyubtz.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjndtyx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2guccyxjn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2elgutehl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2eiepnjlk.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pmomefcu.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyryplxe.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtqholo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qecdkfkz.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xncezyzv.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2juyghunq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2crrowhwb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnqebat.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rddbuzwi.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvssmose.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2meckderu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2okbeitjf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfuxoow.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqribkm.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tymzxctz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlproqp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zojhfecl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnejclt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrqetmx.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjtqlcw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2assorzzc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2phvzsgoy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayojqdmk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vazzxqfg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgqhqed.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xuufutwt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2grrkpawn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yigdpgez.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiewmmx.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjtdozm.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzclnwhf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2nupkcecx.html


<!-- 参考信息 -->