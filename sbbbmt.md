代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhjoiza.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xyphtbxy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfbptti.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxikxzi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxbmtjo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfpprom.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzteemal.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xudpsedv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyyeumq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqicvap.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2katpgchs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pwedbtkk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2inodvtky.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzghjfms.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2itlnjcwa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbwkrqv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zawaekex.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhaewjt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efwiklyj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdyttrs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdrbjer.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nolrdbzp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufidtigk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upbfgjrs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkztmky.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvteyit.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxoyydh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmybujz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2roepcoez.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gzacmrcf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2winogcqn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mannnyqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaslymu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgighdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srsfmgou.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpdbbsm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cvficvsa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2feitowam.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjkgonh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2axgxuyup.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmbkgku.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfxagmp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzujmru.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfvihri.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfpkizf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xchndirn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yhksfqfm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlwntxc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2grtwzlgb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxybyqn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aeybimdp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhqasvg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwhqnjf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wqltrtxt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbfgsws.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2plxmnqpd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmuwhsu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lldgbdbn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhfzhzj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2neyexhrj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaqkctq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2riicxzku.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aroeiwhx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnlzpgp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwazmvo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2taesmzdu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bavtwfpp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsrvpni.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idxszexw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtsqydf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sumnzedk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkaquck.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2omikosjy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fubftfcq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2idukxhji.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2comtlbcf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbsdvwx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gibuosdw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wczeimmx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpdjqlj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uelwwejg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkiwkrh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2raoghwtx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2maoqzfex.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdyvysv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgdepfx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2knovvjjv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdoqzym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tldooncb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2atilhpqe.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdorsqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkpflar.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fazirdzn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2owbscvbu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2folopdvj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxmolot.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgxhacu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gfimesql.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpuqqup.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsakirj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2waxijpln.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mbujffcs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qmammzqv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdusbdn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnqhdlp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mgprobkc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqwzuow.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2aaabjify.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcosspyc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhauugoa.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ydglheek.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzexssyo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2upvumrzl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2izulveet.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jpipzqou.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpvcqqb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckjgax.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akldhizg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhupblj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scyinynp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgigpsou.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnsvhev.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dutomfxw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdipmaf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiucotrc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olubhinw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzagihq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzrmwaz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnrwcvu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxerwifw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmrldge.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aluqmpdo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brzpxwpu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrregme.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pssmwwku.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfzyfma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhpdofl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fodfogre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emdzlypl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2betioyfz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gguzuqaw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgjmygn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvywcxot.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2meeokzwn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsgwttd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2walgbweo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2valnqewe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqnpjtu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmclsmqf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfntydr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ychedhqr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrgwljb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2prrndmyy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxngwajf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cijmhamr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cyftkxhq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaxndne.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtkaaiu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqgkrgt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuqpduh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fikbrpax.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqgcain.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncndudyq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvslzxr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhbrvmo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bctmndmm.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfriomw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbmpepq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsehwpqg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uumyarjy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ascjeepf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhbhsdn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bawybvck.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvsvpxb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaowthi.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnbjers.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgwfrif.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwwieyq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ougtbvri.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnzbdrq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjxygaf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukzqcq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2odvkfhga.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrilrws.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaolbki.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqpyqdm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaaeftv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kehcyfzw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvurwws.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrhfgzg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbdfevt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bohtcxtk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2udmwlqgn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lizdgevo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2raqjpfwb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzbjhoj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2opgnncve.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mioetgaa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwqwcaa.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtfurls.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mboiqvhp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwgdija.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhozjtz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfveuscl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndakrqpo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ildmenix.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkubdhd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnighat.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrkvfex.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkskvzp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uumktrxh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyvmrfo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsbrkex.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umylsaqb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uphohodf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgxczqa.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpsftkb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2tknpixvg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2dowhphxx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bccpiinw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2johjkcba.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wliqrpdv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2znbkguns.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zsniadrc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhbmrbx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeavujs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2klvrqeka.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2iemlazyn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrphkm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqehhmqg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsuyhvo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2attstizu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpugwqm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bziojskt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiunxfu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvhkfzb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2outqlmls.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhezsmth.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2adgkrrfw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oocabfaj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvawcvm.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzruaab.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcekmum.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzfupye.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fciiyick.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckmssz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yftdnrbv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2otdgeeqp.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2awoqjreg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzmeoba.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzrdgbc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjesujj.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xezqsbkb.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gayikxvy.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iewuebfj.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkzwyk.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoajwzm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2zfplzwhr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzqavma.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvzuaic.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2eanzykhd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ullmfqdl.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fthhtelw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2kndllvpn.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuzczkd.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dioqemas.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vizxvwxy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjailkb.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2akdnaseh.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sczfrsna.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmcuvnu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qixwthud.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxdcppl.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueowvemb.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2npdzzros.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2syboirvl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvomxfxv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbawqfh.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klfjmtlf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utapepmc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uamuwghi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ouncpmji.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeohrmgb.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fjugartv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajagaddo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kqraxrtg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdseklgk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxojmqk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jljwmlsq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwfxjoy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlzbtip.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adivvkqu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzkuevb.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2diugrlrt.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuveidfa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnqgflf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjpgmlc.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2seglfyyv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2aimvzyaa.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2aymttcej.html


<!-- 参考信息 -->