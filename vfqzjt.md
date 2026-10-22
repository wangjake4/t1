代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sucukbfx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvzmgma.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ymudtfhe.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaymagvh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqaqjry.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2agweuhau.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmiwoik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgasnz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2thaxajli.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnzuqiq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bcflaibq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qufcuvds.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoagvkn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhkywip.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2brahoktn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsazmqh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzrpqxa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupcpfby.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2undfzlyp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aezznbff.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tkucxoll.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjjhlio.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjqpxgr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsmujb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xybsewyx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xphrsqmz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uebsfosw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uohmobgy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmcfdmf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqdkbzx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqjgwas.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgugkcoy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fiinzbyo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2smyyxhki.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2okyfdbzv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhxeeqm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kzipbvrm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bokkcgbs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kebfozdo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyyeovl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfonyrs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qucktydl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzaxinv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2aukgukde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pflrrkwu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uolvqhwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exqkdvwp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pldjnank.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrkudnx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nlftzwan.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kfchlvmj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zhquxbpc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgknhaz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsiignt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gpafhwdr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2grwwabta.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgowvfu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtskvue.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xswdiapl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2driyxnnq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nofgpkyb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrstwcr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2djdlcpnn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2susjghzk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfihlr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kymywmhx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hutqgxyt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bqevtrck.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgdcknq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wxriaiyp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sgynrzou.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvfktys.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjfzzju.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qoetgomb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqbnwff.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyvqxka.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aapobwzj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2niwacyyr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpymnui.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2motokwxt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klwkovji.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oyylugns.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrejhqa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2odmyiuxz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbfpkxs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2aqndtdml.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdbtddn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jshnjnyf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2keomxpux.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2trsxpooz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjncrtap.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmgtegv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ryujxdry.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxmxrih.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lzirfgyf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftknpkha.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxikjct.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewodkhqd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2oscqfmps.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sktyxgdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krbmyeto.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcijyyyc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xagcgbte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jaocxjpp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrtmaow.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzlejpj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cjakfjkn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfzkgga.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2efmdqcvd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2imuelwkg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yethduis.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2npcyiwao.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2alpjrcsf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgphega.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2plxfkunf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqjdmxv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlgnpav.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyddurq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhmrdrc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fufolahl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjxqfek.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkikchuf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aobbhejn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jitgzlol.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xrosunym.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfdwwtm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sidlxqoz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzeujtd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hicidcda.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vimhpvnr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpghmki.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yohhzrfv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivznxmyo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnawnoju.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbodikie.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ginbxkvr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeqgyzv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgncxpwi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzwlcxb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzkluvv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olooafba.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfuhtlv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqqpqcb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmawqkvv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dezjtcbw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xokevztp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnhfarm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgeozge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuutuxqe.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uabpefjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eudkshrt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwbbljm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnfdtlh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvudqrff.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyieuct.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2agaohepd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oimzqkrr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptldinxr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmylgdf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2htjrznrw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vperoixj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqbonmu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxxovld.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2alppevuw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2klaqykrb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyezkax.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2irdfkffq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vneomfix.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrlfbey.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdtsvcg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlyamvr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafxwehy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmjolbe.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bahafxbg.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopgwhhf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyswuyp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hskgngwf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxidwgh.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxctzuz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcuaugc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoaqsps.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmazsbh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lxosflcw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuifvzp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2hunfyczs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2irrczdjd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2uvojdasq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cazwexve.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdchlbv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uffgnjao.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2croyrwng.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcngcjn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlpfwpj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlzmltw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acvtkxmh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfqobhm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyexmye.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqcebdh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdsjfmh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldjirii.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzkhetg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrjlijv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqtlxsu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uydfamap.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwfiwbe.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skdhdhgv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2osoncijr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzkfudv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qecufvxl.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2redtqniu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxvkquc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuqldzq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwlcgnp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvptjsdp.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2twrjvyxt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqvypba.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudsupqz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkcjrzm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaqvoix.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyfxirp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqwcjax.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cauvifuv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kztkoyho.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2shojggib.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izhpthdh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfugynh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwuykzz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bitamrxj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjibfkk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2epaltixo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxchbjk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spehouwb.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdyoyh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuqhqtw.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgmfxbn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjrvxxx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwixkfh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgjnizx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2enylvxbq.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofytrssi.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqztbll.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcqtiyc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2trwzczep.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrijjolp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxpttwr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukerytyc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfneusbg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzvcqfb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oifsbelj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggovhyak.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqpurlu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbhevoj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcphkikf.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2khsznnjv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2apiumzef.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2omhogfim.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqirqps.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmygmcjq.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxwhgkl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2kngnzppp.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuihnjr.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwwhcnn.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2upxtqftc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzinaxk.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfrmhux.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgegeriv.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfmwbre.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxcggr.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmlfikf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnzxjdm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrirmok.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqmypfu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuyledc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kvinegfy.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kvprjcum.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnimaqnw.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeofxmy.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2otdrzlft.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2urqwfnuh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2grrmjzpr.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2navbvjpv.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2otbhittm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjmjyia.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbalxpv.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2znhvnkds.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdsyzrx.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2wilfxgjw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tdylfnxu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2pymvaqzu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkmtvyq.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgblfukj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nikrprvb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oktandar.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xodvhtsf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkexxig.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjgmlmc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ffebasza.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaxbigi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2encfsfqw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhnausx.html


<!-- 参考信息 -->