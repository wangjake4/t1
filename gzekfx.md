代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwqphhf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrwvzjm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rcysqxef.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbdufsj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ldylgqav.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwqyhit.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2njmpwxoy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2krzochrn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fesbgkpy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2irybdrfu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nucqasmh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlvfbxg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmqxxup.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tixtdbcn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zqydwnun.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhwpsjs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbrjtjh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhrvpxt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hgleqzqm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnvzpi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpqonpl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnwiuhg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyfldqo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gubavlce.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcrqvhe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcjpkx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2axfgudgb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yysvtaha.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qvazkdgz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzoegjd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2auwoecnv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlaqmgp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2skhsjtcr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2singxntz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hptylvtu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2glkgpyvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utwrtuhn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2stbhwrrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weaytoyl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2puztojmg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nsggsxat.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2euuziahx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2raoxjhwo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcppdpo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2siobymyb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wuddjaam.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbzonit.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vtexqkaw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxiysor.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhkjjhz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sklwkivk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfuexjh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvvjuni.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vetefkdn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwovdvl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aluymjhf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ainafopt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwhhrlu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsxsisw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvnterr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tldnhvrn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2evptqykp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2njefjaxi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkcwnvg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ykidvgfp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2siugqipu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2emafuoun.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqylvkm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zpltqxnq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2foioqfkx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqeimui.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gcayrcoo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rvndxsul.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzhswtr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpxvmbj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwawfroh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqviraj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nuulqpax.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2adydlmqy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqeqwjx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oaagftek.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbkypcf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgvxytr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgnxdof.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2byblgrtm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vramtdli.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dawkwkoo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2twfkuwxf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgpppby.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pijkecuh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxexxdp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdlluzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzylkoid.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqydyyn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xygvifif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcacifhb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaivdzk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrvyome.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gycacmxw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnkiody.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhbuses.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zqupimzv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbzhpza.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxoawkn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrfwxmj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuhvfyq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwdqrpd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2shoozfam.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzizohxw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhyugnc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2oewzvmca.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2merafbem.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gshjeirz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2krarnerv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hguadllw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsttyep.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiiqwff.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcwzjoi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxrjcgn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqfunml.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sppybeaq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bngkvpvu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgilsjtu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eemqphjy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwzpdgf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuctcrj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxrkbjv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkmsitc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmgdjw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiweauk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgqbmzm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azjyijsp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfgagva.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcitfylc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsrdidd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpedjyo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shsgdqpj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joslcmxo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wetiazsn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqnfaok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkildzve.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbvbxkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trmqwlpo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkgmcmc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhhljhw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfebbye.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjxtnoe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnqmqrb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqeqwqo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqalgse.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaldsmo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rswwplqs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkicykkr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrxccvl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdpzsxu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcqhzty.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvkwmmz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqktlods.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmcgngg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoibkyf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqttkkch.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkherhz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qiobmipv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoghewzj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuzwejj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iohhedrp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkponzmo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2plcbgexj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wceuisdj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzfuiik.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uyclnabw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrftkih.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnfotus.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqvmxbd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vayivgvh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjgxawr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2avcdjlhp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2siodffrx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2dibmrwiw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vojihuue.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvudjtw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhkmrhc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guskyajg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugifkvlo.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdliickc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjaxlkm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiyyyiv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anejhwgj.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzcjmif.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2glbbgrgh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtfhuet.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hulgbqtp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2znulthps.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqmgwaw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyarkja.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpyxqoo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hebjumnr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2prpvjbsp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyunvryl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwkoymz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpbpxwj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkuxwck.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzycueh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvwurun.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwhgewi.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrfwtrq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2crroiebd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdrllvy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqpfrvr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwgdxhn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgssfwb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfkyacu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jchyhvrv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnviync.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzggijgl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuctjbm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmsuieg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sixhthsc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2loeziman.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zriszgsn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msjzbcfb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrtmnok.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2quvhqjyi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nboanhok.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wedaygye.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsahbdco.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqwvoh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2janhueik.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzcmqhw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvxrjeh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2rdokofqx.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssenbjvk.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddasgly.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2wujyziop.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtiemgh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2inwdzuzk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyvuynt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuxuqss.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dostmmqk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2texpptcx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2izoeqxzc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxofxnr.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbvbkyd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnunhll.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdixunmi.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwkwjpe.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlfqaxp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxmujzw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcufikf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgfwmng.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhqoscw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsmrief.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxnszhs.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lejrihpk.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbybyct.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoliken.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2adbmdxvu.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2twpzhfdg.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2chjrxmwc.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaitdnm.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbaxnev.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2zerecwee.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dccvbgvm.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhrdhhw.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpscdoc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuudsna.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvmugoq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsyjspf.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbrjhai.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqrjlri.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqakeou.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2poqzcrcs.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjzxjns.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbljjtzv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2tswqiaci.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2erhxjyna.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjikwmiy.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2htombbln.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcakpwg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2divgtkda.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2fymxgknm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kgejfgpp.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfwjpmh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qphzrwmr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oioiqmbf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2itmbgwcx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxvueme.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfuzaul.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vktbshod.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmtxrsy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntobrzlw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaiwhmn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krjvvdho.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xynzjizl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsfkfnx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhegvkej.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jiadyhgr.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfybgvh.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2pucpbeli.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyrvngu.html


<!-- 参考信息 -->