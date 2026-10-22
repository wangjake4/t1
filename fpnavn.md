代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzmbbdi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkqibns.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uiocbvdr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuvjogv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2remlrzkw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzomwiam.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxiudqg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqubrvv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgxhdif.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagpfoln.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2twbsrszl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpnfklc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sftlfxjf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlsxhap.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjdouda.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwbumlp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnuvsij.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2txyflvuh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoyvyoz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkstfez.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwxsiqx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbgrjji.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftzzgd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jezopwjk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vniuovop.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2geliaqcv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbokpvpm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsodysz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wldxozim.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjxkypr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfqmgcq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qajhjuyl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wplmpozw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2evckprpc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vakbdmpu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqxiibm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtigxcc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ulukhhhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdeffsi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzuehki.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hexikaan.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcoymem.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlylvji.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrfnkoo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwlgzw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2enmniaas.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2imsbuxbj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxlsgdt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2osvzsdls.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2govllgar.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnehdpo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnfpwxk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2macdymvt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pojlkchl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2utitksdc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ficbgpom.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlbnulx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ijahccuh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2akhbhjan.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjqzxit.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwjquzf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2snvtpwpt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrclcyu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aphpfbsa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjvrppy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2earqntcf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jjprugtw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pusmuafv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2edosiykk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxerdifw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmjmumx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmadngz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfnyetm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kljpjjze.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrydxhb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvefras.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qekaranf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjrtwxj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2waczvtia.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuhcfof.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mufltsvm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yycgdmbd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbkdtrz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxhgblr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zflbjqmg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvuwncg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iiranfob.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsojdtyz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkfdhjb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsfixew.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qydsilph.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2moqezjlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fodlsktv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zemvesgk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2egjzjrwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbhhjgp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2arftdzlt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mqilsjjw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2enwycmjj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgezyuh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dfehztda.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrbjtic.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2emdczjxe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2amzfoanz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbvlblb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqknvfv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqgrtvx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qljxzwfl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bcadxjyl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpulyzi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsihgoy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qaozuydt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahowxusv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uiauzjjk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2byhguwkx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhjglgb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqymvlr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qvooandq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2astlzxgp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtwtsvb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyialqu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2miqujpqw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2peysdzpx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpseoumi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjhlqfc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsitucsd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqswglza.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2anmccwdb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eodxwnzq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tscpfpfg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmthtzpd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkeshvk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2parkwnku.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrikkwwk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwjypsx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pslskaor.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phxonskz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdlkkhj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfbqjcr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mstuyinz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zoldxjcf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhxxfiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwhadzn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jamtsxkh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qultxmcj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuejbqh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cglicbmf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbkspue.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyezbcet.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmzfhce.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbhqqxv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsduvrx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyclajj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvguukz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcnuihj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgadvczv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2riraxsnx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2phulxniq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwqqvqi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2drqsfgsv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhvdwc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzvujk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbvpwnp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxxyhsf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yarwrsjr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgjpnzm.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2edgvucsx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jgahsknd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfsxmwa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dssxkwxa.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdfdwuy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcswgbxs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulybelrx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qprlfetd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhuwtmi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxutnpx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jchhggqe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkdvxgg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdtdwjn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvjywwj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltitqbwa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svcnsxyh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysogaizw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhqmusr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nopweuoq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxouqyv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxrchyu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eradqhtv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2judsmmxz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqwsyub.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgeduwg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2umuedavj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2senrujrc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfndkvsw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdeuocp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pubeqbxk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzccknnw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rsomwinf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmqflwi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzqcpcd.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2neiervaz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yncctllp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2attxubmz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrignqqn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2spyrgjtr.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyjjmiy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgumsykw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvptgak.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2szbqalna.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2npjwoxsl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhetipvs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dovmbbdt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxquwiu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvqpyvg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbkhrhf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ramnqoek.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhogbxsa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsoadci.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkochmkm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzihkhq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlefrfy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2swrpwjtr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkfafmw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sstokyys.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yawawgii.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfohfjeo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dljdqtem.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmrcnlh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezunaohr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgvnasj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaomgly.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiyudmb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2chkdbijm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzavvzt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjdppkn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvznravg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyjuerj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqooqqm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgstgivo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2srogzrdh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2slupgxee.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjwrbzy.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rxarnplz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2esuhnuno.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcydhsl.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiialbq.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsgvwlz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oracinsc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzvavjg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fopdzlgl.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbxbbec.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ronmnorn.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2atpetaif.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkubydnc.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncafadwq.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnyvter.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjdjfhx.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqxnemz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqwvzrm.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvwzhnf.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eidkxwcs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2jceohgya.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wrixiczy.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ophxatpx.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2icammimb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqvcxox.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2skpbngfm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdocbzka.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsjsnqa.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iugmgqum.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpljhemj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsabbqpq.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2korhihxx.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2itdpoxwr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2phpymqiw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjrlaer.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqttdfv.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyrtqdq.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2lomvkxdt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzvtgnm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsorjcia.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzdkisx.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpznbojj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcevpds.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oftplagu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyscleh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kivbukuw.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxebbzo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfroulpb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2weukisjg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szzrwixq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcafnzho.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyaeahn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2guapeomx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvephnxa.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkykomm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtkitfk.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaokxnxx.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkepswi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2eincmrgv.html


<!-- 参考信息 -->