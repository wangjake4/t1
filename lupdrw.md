代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2okkoqwdm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2usavcibh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2afhfxxyo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hbelzwtv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2laqqbcgc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwefdwaj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgepyfti.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnmpkik.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2injbfdbj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yytderam.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iphtdquu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yokoarvw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbvgwct.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbfzhpw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zrywmuef.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2omwwhzes.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdjyhrg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2evjshidw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hzusnmhn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxliljx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvcrxsm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tascdtgh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kngmoulx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzkammm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2esfpyerb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pujqoiwe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fyctdvov.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2layffpwu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qakoaapx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mttmxzem.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsjfbgf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oxujoadl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cylpscda.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iifceeci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqldalxk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjlulce.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmyjeyh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2psvtbena.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wycrgefn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2baarrvou.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2esyscpwa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjfdtww.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vnipkkvu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hekyxjqb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhwrpff.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eipoppww.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2inhwygzx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2aybfrrwa.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkvoqow.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifiplb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeddijt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2heudshlz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lllcrybj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pjncarbh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzzknvw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfcxdzt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqxoxox.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2auoyfiqu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqzzmxk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2akkmlfsf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2isvzarbn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jdujimjo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jjovcmyr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rrosyziy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaonzki.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ltljssiy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2twxdrdcb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2inpdsfgt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2phzxhwur.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcgrsqh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbxdqox.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbcksbp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bgytbfex.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ykybtmxc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjmwnch.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyhnvya.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgvchuf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ewphimkg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2phqvrunc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bigvuohk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gpithrmn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfibuts.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvhehip.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uuirosos.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qngktmge.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyckjhts.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkfzinb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaavpqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eadzotzv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tenfzbow.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgicruz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhrkqgh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yyokswdh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mzencnxa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwomdjr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwxsszq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjejzgeb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrieyyp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2anznvckc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dudoetkm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdzsiio.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2buwvpzpr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoisdzm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnuhjfs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzvlwrp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtqlymb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrftruh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xurepuqk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wahjaukh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2miitqrty.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgrflsn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2arhmhknb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvvwkcq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwulyfh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxvymak.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgndjcg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcuxhap.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzkxsxn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfixmysg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgczued.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2newhpqgy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyhzuud.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plswijhe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sackfbxm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeekfpjc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcdfqqh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqszibkh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tehiyplc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qewkmfbp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olbqjged.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpwptnc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjvmkvt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwfsikz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnishkij.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuwcinf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrspjac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoddodm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfekbci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knmdacvz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnujhvf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpwhfma.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvkyczx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2avdudxav.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeqlafk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2juhihqjm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2oassppum.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnxxrmq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2byynvhri.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdalynr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wrepkxnc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuxvqel.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xztzmpyq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcjoqgp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zreyswua.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyutqiz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvesxku.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlatbxu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iopfjhre.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsdlikh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjxscfo.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckdllsn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhxwdgi.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjjiubn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qnncwesz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nfujpmqy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwpqynn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjtvyqs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbkjlkn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrmuzck.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dklkhcyd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2heuunmwv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxdxxmp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuufzks.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxnbtfg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnedbre.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2upczvjhx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2twpitlcf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynegneyy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlfsdov.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jyawmafd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umisceks.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qosmksvh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twrnmdgm.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqbdnjd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nakffbdp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxihpsau.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvhnwdg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2trsqzfnu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gntxazxf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaozqtkm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkdozyc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2reloudoc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqlbmv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxdpzmv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2swstocfc.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmpkaue.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmuvylv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2krekgxxw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdffzwe.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uixnydfo.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzuhlra.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2psbvcxdi.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjltsui.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbtdmj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uodytwfd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtupmlb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmobuukh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2junjpvmk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqwnldb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhrqwsq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rojgnwhr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nazwvxww.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trmmsjyt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuyumye.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcwowdo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rngodaxg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhosveu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgljjnh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2imdjktqo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmncrald.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuutkclv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvdybbo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqddqcep.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2haykuroc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2woxsiggk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeqvczz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyzyycm.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpsozxe.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabvhiby.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gicabcvx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iawvmsgc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixusyadw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxberphu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpqwicd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oilyfzox.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqbyudw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiwloew.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmokesrk.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmzjvsa.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zampiorb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyivslcp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxhvhqu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2aowclqip.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqtekni.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nklvowgn.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2keikciaw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoqcbtp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2auaptqui.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2imyjfkjc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2trarjuzt.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2widwyyrd.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iohqvhpd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqadolk.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnzliqg.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hngekolq.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwbeyfr.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrvqlya.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2anwvevyc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpvfzao.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2iatpefdj.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2chutakvs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2amgwuwmn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwtadip.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2eathbwim.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmdkmku.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkovjgrx.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlhcyfw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxlojsz.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvbfqnk.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkulmlmh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2zauujnre.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofwkmfy.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2nomjwnob.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2isofjynq.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2qidigigg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxgtkog.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2takwddqd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvilufa.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afoxoday.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiofracq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xthxdqdy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwbtrbd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfxgnjd.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjdmojc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2haempwav.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvebggw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2guvbpold.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2munhorgc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vecpeuyp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vguuaozj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcjeiiu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2izbkjsub.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ajevmpfu.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlbvkug.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmmllru.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkhuoza.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrnicdu.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkfalur.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2kxthvmuk.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2afnllhtt.html


<!-- 参考信息 -->