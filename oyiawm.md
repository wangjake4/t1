代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xcanwiyv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpibhjc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiwusfd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wspowncx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aloscdcr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbssqblk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtidxkq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2whiyyzna.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2akunboan.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbpsblg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcibqpb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jdajhihj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2erhrxmsw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2drwxrpbq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zopifekm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxyyrs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwldazd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxfiokd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2teacfpnx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2usplqrry.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwgzser.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2embrnwyr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjyjdre.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nynddkhj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvtwxyb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2muzzvhqt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cibtydyy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfbjuuv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eckvibdm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fobqvgqp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbrsbub.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfbqwij.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwalgvp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwgarmu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2htpwjwoa.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeisdfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qivkybkt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmzsidw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dojxgcgr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2owlztpjg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcawcvx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gctztidt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbqdryk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2banhprnq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtputfxr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvpiyaf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwmhddk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qffkmsch.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pnydgayv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xhabohst.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpbjfdy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kibhdaay.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2evwpknjl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2otjfarhl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2chmhwodf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgdrgxn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lolzocef.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfqzmzn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wolknihf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zncbeibi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rqouwdma.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhqnpqf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eusyyeqt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bhszduzs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyvqzal.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sjanslwk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uthtdled.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jocnpsre.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bseucbcr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fklbdieb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yajtpuoi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgcuopj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdcshzb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hibftdwb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgsyyte.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzisayv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ugekgowf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgjfrir.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dcazzdwr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfioabt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jgirkyht.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqocvpb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsyhghg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dsihcbtl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjekgjj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoszxwu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtzuklw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnvhsrk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwmygiy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzktnumn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zismdjxr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmeqsij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhybfwvl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjosld.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kgumgjrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uegnfagl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyejpos.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzmcqgp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nscnfhfv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lugvmple.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qngxtjgm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2emzbaqlr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vezbexkf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mncajmne.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aupbbipz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnismul.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bezvnffu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwivlqe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnxupyg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dakdiqoo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2efxpyfqe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhypaxx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrrusse.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwgjrqh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qebyengh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2otjayajb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpdxple.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtidnqa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2auuicmks.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikctidiw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unaearly.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfeyjee.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqahbmql.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drmuqanc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwegctj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juzhdupu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrhommc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzchxck.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaujzjd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pknyoihn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiczpvr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiogeao.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxcvmct.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnldwbow.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djlwzvec.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vksprukx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdteospd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhomgrz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2boewegvt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uducjdkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umevbubr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpppxhvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiurpudf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glwfcjey.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vodwhejl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2diokhppt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2apcfmnrq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbyuqoh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iweopjhm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uolgitdp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hinrgyvi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2shjsumeu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2buyohvkd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tielsokl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcxuxat.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2apkzkpan.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyunvua.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxjdqg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2giktfahw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbezhhq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvekdgl.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2njqybllg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhhpfd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aebiaext.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpfaucv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrezawmz.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwsbxph.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2obixuohv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyxipgn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxcsxjc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaqcmxq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2moxsartu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2laodszdk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlsegrq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjznyim.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2alfmyttw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgjmuup.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqezxsvj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgzsnqy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2emxwzent.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxabufe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqevxrx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fcowyrkh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hisvjhpn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sflmrdzr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdovlzqp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2riccxkca.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcayryc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rfevjstp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zguzyvup.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pieumbip.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2axrfhmid.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnktsbte.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2riwiqqub.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxdwvxq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfvtnvf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwmjjjg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdulyv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fffvashn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yszyhiry.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xajnhbdy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqchypr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2invcgnql.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtibxxvu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgyxigt.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddosttxg.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbaqblj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghialdnj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tegxoflc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2smdsmvdm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2apidljvr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpvmmeh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgynjfm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2erltiruu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtipjiy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqlaizn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcmefsl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctryxdy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urgsuwta.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2telrkzsk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sivqjcsb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2wyufgkmi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlylbkg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjegpqao.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2icmjwclx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtglonk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaciifw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yytsrxjp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgpnfju.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoarvdc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwzqutp.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuqcrad.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoykuis.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bequfqlv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2azpyullu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzrpkgk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzthrfl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxpkgcc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2goyvxqws.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjycoae.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zurpqxzg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2spxsmecu.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2phktrcnc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqohelhw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunnyxzf.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dedozzne.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mdovhkdu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2chbgfipk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvpblra.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhtbgll.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uceevzfd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2noboaiiz.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rerfifjf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbdwwbc.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpyjcla.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2shtafuxk.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhtgtyf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaddolv.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gswfgcdh.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2czmcxkzz.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vucvyxjy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2uihoiuxe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uesvssyc.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhwivow.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sivoycyf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rimavicd.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2krfycjoz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2etsqjcbo.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqjtojt.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtpmhhu.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2grhxnzoe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqmwdys.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmohrwrk.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsthovht.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkfdamp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tayhutss.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvsnfpj.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxfoqfs.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyiujkh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtpwops.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvcnivf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqvkkit.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esxibmsj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwczvps.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgibjwma.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lttvtflu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aykwciok.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qnglwyxx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlyfagh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgybjrxk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzfomtu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fededhso.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ankpscps.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcejvii.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2liynhcka.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stbuouye.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxutgcp.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbdruet.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2isxinudk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrtuesf.html


<!-- 参考信息 -->