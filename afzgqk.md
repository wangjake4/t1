代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2blnqqjni.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoqpdkp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uaerviug.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxatfkjg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2byankubh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwgtepq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ooatuqkl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgmmxwq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vdslcwob.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tteaysni.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2onjeqxct.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvsjuaq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2htukiwzm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgrawdu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rdklsdqh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2avpeydes.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2squonvvm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueenybol.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwmzgdj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmlbyav.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhruyaj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjgfwfp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efrdkdyp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnwairs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hpavlrki.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jworsmkt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xscewzlk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onsoitwa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2datzbsii.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2auimxvpz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wgavgocn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzjuumj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hmizqpyj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zpahykxk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuirbzbn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbiarjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwongpei.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pgebtwdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjommqj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bongtcxb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2suzdbykc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwyyvyn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzlgrgu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hyahwhdm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlmjbfr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtmbsqs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pnafjokq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrqljsn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfwmzlk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2giyuramk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fetoroqk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaoyvjq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lubgqgdk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qklnixkk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2psjetfrz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtcjtxe.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvjerop.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpowxka.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tenkelzn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhcrey.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2henfobye.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2echbmmhz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wocrvfzk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjuelqq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ecctlajt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2riheioxf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vmftoqsn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vjximfvi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwsymoo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gerlgjyq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hmphekez.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2smurfcpu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2utqbjgzn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmmrzbn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jcidisse.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sukfqadd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzwuaup.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wdblzhgh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxfapuk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vkanhygt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xabedoof.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuugdul.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2umnkapei.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xstzuljo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vafctxib.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhbnqhk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyayaqtr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfylxjzk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2utghccsl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gttpymxs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfznmqos.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjlkqga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnkxpym.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2djinayxv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dnevomjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tphbqbkl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjoseiu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2acmfkfgu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrgrohg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yeudbalm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2svhsrktz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oemzomnx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yurqiuul.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmmoavj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zeflxdwp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2imwcdksc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2idcbtxvj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkufsgt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bajknrct.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gmootszr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwyojow.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxqjetk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2emdnuurs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoohxod.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2akebdoln.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvigddlr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oadsruuk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nklwzdyy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2teerrocx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuialnlu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmjrpxu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsarqopg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usffoadr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaacyglq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plemuwau.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdndlzi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoktdyr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcnnevq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2frusrmaj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsoesum.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyhhnhr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cairrnyp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lltgmzrq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlmmmlo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqckrvg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvugngmw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsjgglc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cagsnkqj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdqfend.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uveaoqvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjyilpt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vquzvuhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrprjdw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vituaddi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyqwbeh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuahsgxf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcexjyap.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtlliek.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2crhdizxx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmzbcvz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2noquomck.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvomsaqt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvnkatj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dwndytzx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtawafmw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2twypdyaz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gutwpbat.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2plvypktg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xyesnzud.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hgavsfhd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2whmoenbx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdsznhn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlxsbln.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lluewcuq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzwshdn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsrmscj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdblbeo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2shfiiial.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbziudi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfbsvqi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuwwmtj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2povdalei.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgbrgvi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgwtvkg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ekolfeok.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fmunhsyq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzupfmwi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2quesuaoz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyyfppd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2tthoawjx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhiawpa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpzmsii.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkldlfcf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyellezb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiujgqi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaeslyd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vogxagat.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmlvxxr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pkitgmpc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpohxvmw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwvftqv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzirgeie.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgucrgwm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2erfnpirm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfotemqi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqzrkdz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ricvpvhu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oakituxy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sncnzmdy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2npefadza.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2revbxfdd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjpxwil.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfnfjts.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqebqtlc.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2iuutfnjb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwynign.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rjctjrhn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pregihio.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnveausp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zitxwhnc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxkpuqn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbbwers.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2adplslgu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rkepvxzl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnvnots.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytijdzjl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrbmsex.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2siflxcue.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghirxwo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sigqnzkv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngayqmji.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jnynlcys.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhnrhhz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzknbbmv.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2elvbdcnd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2psijurmt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mufcqolf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bprqzjuh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pokbkehm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfxlbsa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpfjwmf.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2odacikmb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufbxknl.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdmptxs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdalurz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2khjakird.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlanevnh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rofqqljr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzlzxtu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2syexzmjf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsqyhoo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2asclkvcd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnodvjzh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvsdzjn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxgcmhw.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2sejfuvhx.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2asmqrzfb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtycsgq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvtiaiy.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2adczrhfw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhectytf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfehbryl.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2thotmnmf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjlknkx.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fznlbjpj.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzuqtxb.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdkrrxf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2knrjqxun.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrctodi.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuqbmun.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqgosha.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2eojqcpya.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2odupqcqt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bnussbgf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2olflzkqr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ybukhgfe.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2onzvilxp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfdfozg.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hsovcyum.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2izgwwrsl.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqcsdjj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lebelqpr.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2phbwnmrz.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2knwijqxo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuazyew.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnduoqh.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ungqohhj.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lcexybei.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2foxcozzk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ofootnvu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiauxwc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2muqjeunf.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thomiuit.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okldxded.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2knadyopm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xlruraxf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuuxfte.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhsxmss.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqlsnxt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiucwcq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmtysod.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnebpgm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcxqmfx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrjvmfl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zccicmgb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqlqgfl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sskamteh.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2apkmsclx.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2sesyugas.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggyopbi.html


<!-- 参考信息 -->