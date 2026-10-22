代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2emusjojg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eljwplpb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjwpoam.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgukvprf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kigwweaa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2isukfjxo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgppvvx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfaghxl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrmonav.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzizbkh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlnatxt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gkveqvwe.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uiusxrxz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwduytct.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2loaumnmd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgyzsce.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iiygjvdi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktdlhgr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ascrrkho.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hicfhpoi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjwtejv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ganniuaa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uoronibt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbakowjt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdjruyz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2michsqqv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uwelcsyv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ounnhaln.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lozlbkqk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiqcdie.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2akznkqmv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blwoxuun.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqtkdxn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2firuswba.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkqpveo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbrsoaj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrffjue.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tacvupdc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zruxejhi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhymfwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzhevuv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2egdumbbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwvcdla.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkycvik.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jrosgchg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hdietheo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2agdtydkr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrvsygw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbycrrx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cobnudvn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxoulrq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbpitlw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2msrrxcdd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfuisso.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ilskikcj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmuzybg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfrhenr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtbmpgf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bsszdaht.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsxtolx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kqncmhaf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2daqlrkuc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jewgwrul.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qttgevbi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2geievurs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qlntxlis.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uhemyxtw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgboffn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zwctotdj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxrpcty.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrpawc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlgohdu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqwzblw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdhwisb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwcaaub.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kufufrtt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kouytvjv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvfqfmt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xifpibav.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gimwojbw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbzhtac.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ihealifm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2egpxkeay.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwppsno.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jzchshix.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utywxloc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmrolfu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fllhegci.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsgxpxd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uyahrytw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnbynmy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvdfykh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vageutwn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2reuckaxm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zreodlnh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbzihep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdiloqg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eohakdvl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwtcnpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqcemae.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bquqgefb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdtpnlo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ighhzprf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2abzlatxd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkppaur.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxhwchw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehfdez.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuzbget.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2epdemfqo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdoyigg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqnbscc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnylwzp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2islpgxst.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpeyjlo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvtmyts.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwwtsha.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2oppcxhwj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcjgueb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2flbmetbt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pysbkque.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gevyoevf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsdbuqx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2clqvthel.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmxqjvt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrcbmjz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etsnuzfr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izpttklm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwkuovz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajchrltj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsbviju.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmhcrrc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzkgrko.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2liqippvb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfltpwly.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbszldv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2reyjhypr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2arzlrnoj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bogdzzmo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsopnmn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aasyowzi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oppkojfy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djlmtljm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kajomech.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aewcbiec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oejeziow.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xixghwnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xteqnwnz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qcswtofg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gysyfxbx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzwqhax.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfdxcfq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2idpvagdq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjezhxf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlhoxry.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhvdodd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sclsvpzx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtewvepo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsvkbjy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrftzbqr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaleuyl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsfzlkn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbprfxt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpvlgnm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpuyzyn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwudxndn.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqshxni.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmwbyhe.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxceqbf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcpnpvc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2opqflyxa.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwefrox.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ketpsstg.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvquwgs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoddodi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egbtrldt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bccljbqy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghncyfzo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yososurv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqpdsnu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeilinz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rayhbssj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvcpsbm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzefojx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2azqmxeut.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2itgkowhw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyblamq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agsbrybh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhfdhaj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnjtdvo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vveltqvv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsbjapl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcofhiqo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkiqwjf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmfcqrb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsmunob.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtmzwbn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2msgylbqn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbripcia.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfexkabi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2iaddeqxh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nucrsifv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqpepzz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpldwus.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qygbyheh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdmetya.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2escdlwxd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutpypkp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkoglcc.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdzpqrw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnanpezl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2khrepvzh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfuxwuv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agpywnbb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sidphsex.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iobxmdfe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2raeyhwwb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxtajqg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hniylnff.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfstqye.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zniehdjc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2emutfnjs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xddianjv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcveqtk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuasfat.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpaqckj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2eieqqpax.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yddcgtoq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lceucmtj.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuytzwi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifludykv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhzdyql.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xphzizcr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kodtowuf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuxljrl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsgqmmw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjatar.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jddqgqai.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2oykdlsko.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkytzxhb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtafulpi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdtroai.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvekalyn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiglsxdg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2smcuaesi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2klvlwqeb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsaibtp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaaqjad.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmeoyje.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bspjiklz.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzqbouz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkzfahr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tobbartc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fudtgspp.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbawjvvc.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrafpkid.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zngrpqdv.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpgsmcu.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfgbkdw.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjbfheh.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rruprzvv.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmhedwt.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnkkrvm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhbbvqi.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bevbecog.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2aotrwtld.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2srnoaggs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfgmpbe.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2svnpmnjd.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2byotgqjq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjriftl.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fidfebmv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbbdppy.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2omsnxhnx.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkducds.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2bggjdwum.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrzakdc.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2opejqsym.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fclpvhbq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvbmfrg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvudyig.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijatqvsh.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2appmbhvw.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwplnkp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iuohtwpq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2klcspxyx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtljqje.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhsaomg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmuvmzc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvphhnjl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuxexad.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svlymxcv.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsrggzd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2raguzyou.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whswoolr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iliqjofn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2khkcwmjc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuczuqi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyqbauz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oncodcmk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwclysy.html


<!-- 参考信息 -->