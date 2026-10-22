代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2drrrhupa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoovqrek.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2beagkmie.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oawupuod.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2carokqbn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpzouni.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbawqpq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2godyrtoy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqfjazw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hopkfjjn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bozppins.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2omowymei.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2abmjfzso.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jptdxvgn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsogcyyr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjcaji.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2texbgtbn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2siigpqho.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdwhpbc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkdwuri.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfltwgd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeupxzdh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsgzmop.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvwacur.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwpjyhh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2reypjlvq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsgdlkb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2juohckcc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2exuxugpt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjffmeuh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pakxgjze.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaqybjm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkbgkhb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkzmfbo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2clmkhxcv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjxqiku.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sggdnxfk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2aactkeej.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmhjhrl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiysrte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkeylen.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wonehlwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbpqpoi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jojxuxmi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2quldkcla.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qrveoppe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yunnmcxl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzvlwsx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owjnoyfm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2andthgdw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxygvck.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vbipkktd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aexgygyv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jyitwqjm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yosxfusr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pjonjqgu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhesgad.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcaqgms.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zbowdbry.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wivyhjve.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oasznlfq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kaywzfot.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqlvmbf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xnibkmfa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvcombs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2srtavayc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpweyec.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eeetzzgx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjugazp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2biaxdtdw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzcmekb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtwxqrd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdprbmrk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2owrdoowl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mpximxrs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyeaotb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrfrogv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cutdxjth.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kptwlcsu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwgzrcb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwjebje.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcvkjul.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvzqfor.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxsoduj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vchbkcoy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwjmutg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmfkdax.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcqqmac.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2msynzwmr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2raolwpon.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvmbjhq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bpttfkwd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwgjnve.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2icsyydky.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhbyhnu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcbeqgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrszztwf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbvwzne.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrlzqho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmirpmgu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrzcmwz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xawprfgu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2alpklkxa.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmmsqjo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnwnsdv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rnczqzft.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rccaonvo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvydulu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmreama.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaefbdw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2clrpltjp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvwazrf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2awpuuinj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2phzhniis.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ixargmfb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2olrfpbnn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbeshim.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwevwru.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eslbgllv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpucleg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjrtnoq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzuszow.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqecmlg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxuhqhy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkhjgc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klpfbxvu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xstcahbp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nauquith.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouciirda.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uznovfqx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoiwylw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgrxwyu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrbqrpy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2piptijge.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhwixps.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjepggu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blomrjbk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiekzmow.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeelgll.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zorvxwey.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdysnpkw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fauemveu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bisuovok.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irydgaqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiucetiz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbbxypr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaxzgzy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhxsrkc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcidyhk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2juxurqah.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgonjvd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxffcyed.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnqqjol.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmoeoit.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yklarwkg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbbkrdb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvtcbnr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaaswsg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2knceypcf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgmdjpn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbmbkas.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtczlduk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfvkdsn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgxpdja.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtkirlc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qscjuonk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsdercu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuoetok.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2euidgeas.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlfdryw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knihsmhj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnlgesc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2drjrnvxl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2znvtktot.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvxikav.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpjdkza.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2szpelwnc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2myownjvr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dcutezrm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2titbbjcw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rljorfnq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbxwgpw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wnacypby.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgihvoz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2motybdsn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfantyev.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bawoznfe.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csnzokzw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2recorydj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2niinpczf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwypilz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjvkiym.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tullkjpz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ossdamth.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mczucdmo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfowrygw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtkgfzy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lozdnlhp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwnynra.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvivcoe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoizouy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnqcydw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eesdubwg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2radjxawq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaxqxpt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmoshrl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2itjslqjk.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2owhdahya.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdkhkab.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzfnyuf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2kbslsrve.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeovzola.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qddlrbxm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzjbajg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdoruvh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2goghdfzl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpcvzbf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkwbjbo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaaqied.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvypmpjz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuasxyp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrclvat.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifltxcv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmgxpmc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iupcskry.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyndyyn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpoajew.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiimeyyp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabrkek.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejgfoql.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjtjglb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qxofeluk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmginoe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfcnudt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2fklkucjw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjacscnz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwokulw.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqibeod.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqckqbc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfsxwdk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wramstcq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbuzlno.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbwrjtu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnozgtn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yinosgqe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueysimxr.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkqoxmt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyfsbaz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbzoudm.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jiftouna.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwyclnb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcapsmdw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjjbpeg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmvjcgv.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmqicid.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2skmvqutb.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkubtai.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdevhvk.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfixkpkb.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytphjiem.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwrfwgf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxuqncc.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xutcgasd.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2obqdvnzm.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2velekfms.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcsupku.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrtiaxl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkygnuf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aljwvvge.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dptsxnsy.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xnknjlxj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2imrknapx.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlrawzx.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2agwpllsy.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrhjumc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xardanlg.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhouxxc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwdrggi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2isfzzrzj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjylfna.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvvruoi.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtjkxfl.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqqdkyn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ejocrhpc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaxetym.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kqilhglp.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhixgiu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkqzfxm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltohapam.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2htfvxlxc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdozymha.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvxnzdw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkirqmk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltllknlq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kplfeagr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2auprtjbx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvqgeyl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzlcpze.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xsllncpj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiznbys.html


<!-- 参考信息 -->