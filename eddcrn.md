代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2olqgbbyd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxlsyhm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjkacvj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2emgtooxt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yohnvgow.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2psgytsxh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2segkircd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qprovlug.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvblfu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uujgpyli.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tizfvjqn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gyutmgxo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxyhwvr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoznpcq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iuozjscj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hevokrmv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eyliyhqv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmweltds.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflbfef.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvubajx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbfocil.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gluglpkq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2itpztlno.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acjqgznl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fawexhxo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2akebizhl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wxorwnjt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkjpyhl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xizrtpap.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdlnunn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2txkytspr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtastvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyexbfdi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxfwurp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jugfjwop.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ksncunrr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wugouvfr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sngnlfif.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzcwkpf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqljqfu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2friozhkb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2litcyozn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zagutlgu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozusdjoh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkzjaht.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyesivu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfemsco.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxotklak.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqlnygx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2foaqenvy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhsfomt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ultjlcab.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2huplyodn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbyuzdo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2utgmkphq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uymlrzpf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aidkcpxl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgiosjb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqvvxah.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2znzoyfxc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tggcyhtr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcjucqx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgiujyo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhdbsqc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwaajud.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnvqtox.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqbbocp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2amqssqty.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ittyljjw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2unpinrhv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwdtuxv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cglvnxfz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbjwali.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgpeqsa.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jthbntwg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdbcfov.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzwnypz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2opdikufz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vhssryci.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dahmpsca.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fahlvqvk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpjxgmy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2eftbmsjr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2glvxekij.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2djelaeeq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fssscmqf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2udqumcgc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2eesnanjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlbwnvx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfvsgbo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwomntf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nusjcsgu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vddjzoje.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzytypy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iloagliv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2czklyvdt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yytucxjf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuopktk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fyanhcis.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2txmnumgi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsqdxje.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hapsterg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jbysijvb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdggmyd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvtncna.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2iuukgiuo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxkjofp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2aksoikzi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqidqhji.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wpondlqv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2irbcgylf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2scbozmyn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxosvm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fkullkfi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zteqalcm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgcuaqi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nigcgxjd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxocvzr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfvgqwp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkewyub.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwcaso.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sepsvjec.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrdncay.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqbxjkx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exlxoaho.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vabpfjgy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmjpuiq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbcxycp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qappofay.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyooglg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvqhwmj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtxywh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdalbzcl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaewagqo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcgdsxn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyubhgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlefffhg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzjxfim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcrxkwt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2enwcluhu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdiyxec.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nifufthv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gureomvi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaviiji.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxjjrkb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtoabny.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2spiumstt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaemegr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgrkkzn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ffreekqh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jylysyfl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbocixa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivwuzir.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiejullk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfmezus.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sifmhlsv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mktlmfgw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gepzylze.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzndptty.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ityolofi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2csxxsvsg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uherzanc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdymfnj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2poclbwei.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gemqfvqi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tghwvrzb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2auaposdk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsscotp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvtznyk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjdjqrh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrduahu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2mtswvcez.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gybaqgnk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkbxhfw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxjyboi.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvzrrtl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwecubj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmahbsy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orfrztmc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlemiosq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whvpxgrb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gklpdhdi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcrzjoa.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qeetqqmk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfvxniv.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbqpoqd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdikeq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcyszpk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2phwrxsyv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbosriai.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlshgnb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2tobnonbb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgzkskr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwuafgx.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwygyljj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxsdrtk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvgawxz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2khvdejqm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yumobuia.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpoytln.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyyolpo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmpytiy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmizumk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoffhfm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrofykv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxxlczr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2silpabeb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sozcoike.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbxezgj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zmipkelx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2adoqamvo.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyjiwla.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdyztyc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsdnugv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipigxri.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nclgcziu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjfhzff.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qafwxjnx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2deuwiatu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgjuezl.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wycqyyjg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqhwlke.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2iarssvlo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2obaietlz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2weiwnmwm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxjgyhh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2anvoqges.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfavmchn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfyolgy.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2toillyxc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynidmwkg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nehyezpd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvglpmbx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocedmlya.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2leesnwyc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnwjvsb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuclsnb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrjjfoc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ethbgxur.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyetwwz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2emcawdwu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbzqast.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqxcfp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwbzuck.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ativistv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mffihcnq.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzweemj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnjpdog.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhzcisx.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdijyplt.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzlgcvo.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxlettn.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yamnqomo.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zatatqyu.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mexijvhf.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqchgcci.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2edchmxmm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvmkbny.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cuilzenf.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyjdotl.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2iesfxxem.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2somizrth.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhwtkby.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxfnshs.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvajbyc.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xipfnkqy.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctudsnhm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbzehlt.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2iadwtxzw.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjfksaw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2flmdtwlo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyieewcg.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2nifveuug.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnmrucz.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlnrevq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2szahzqcx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2xiejtlxx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vmritpce.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rveufueq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyxtwlm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkcmycd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zneitwig.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmtqugf.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyitwyv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbdznfo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2llxdjbop.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zdimfbmc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bylcbmau.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xqltawvl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcigtrk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoljgim.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lnreuauq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkoqijy.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgxxdkd.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2udykldtw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2syxcnnfr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxmnzn.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrmdtbb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkzrosy.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlslmkd.html


<!-- 参考信息 -->