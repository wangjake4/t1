代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bydxglhc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnbpyri.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2goocwulq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvghzaw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtpkroi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagqgtsf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cssvspga.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2osoyccbn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2metbykry.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsknaodx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hvizrscl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjpdqxp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhnquvn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2furhqgns.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgczqva.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtlaydh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lczbehqa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhqcuor.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wufcytkd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqppdbi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwocmuq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwcmiae.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpckohxq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htopluvv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoeedvy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ufilabcn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yimyeduh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gybpopns.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gsevewfu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cmswbuss.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqbbji.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhpvgkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yowqjgtf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rnweuzct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llxmmbwd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfomwry.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkaqjwt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rknbwsai.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dpecxyfj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2slkknulg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyovxxcg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2evuxhotx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fawpuvqm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uocfuykq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrnkkxu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuhdcfv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uglsllcl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbasmei.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhthgth.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjjedio.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjqvzey.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vazlfrqc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2glxvonml.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnvbvhz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjbjvju.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bklaotao.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuwljdx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlwirvc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2crzkhvpq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjnjohq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqnqjpb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtyvioy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ueopwboy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqpqmpr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhxvcbj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hveytcbq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pygjlkhw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvtmdol.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlfngsh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2neegnnob.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpprula.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgmvwjs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvnlpdl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nixgxabc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mevtkqbc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzbvfrq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gnruxnof.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2okzoqsrq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqgvfqc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhsrava.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcflsxg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2snhlfsht.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2obrnzzfx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxmfvzn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2taohnerf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2arzepirb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlqejsj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zliepzws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iadbvdta.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2epavxizm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjtfbmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nchfqyzq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qngtmcaz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2czmmhdml.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xonxpmbh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lipcvsqs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcyzrle.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhhyeyf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpdfrde.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeqtmli.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrftwkr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2krhknekt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxdnoi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjcyqgq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvouewx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmxschc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2leatupfc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyruggs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycspywbx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvrdvxq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgmgvpj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbslipt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rdenveam.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2aubfjrlb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2syeaotnv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvoscv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mofcvain.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slbxvtln.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzepmklw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ononfqxy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiybfux.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwhcrtp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzjqppc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2relftouj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufryjckh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbaowps.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlyxgta.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtukmngg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhicdsp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzwtrla.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgbkhja.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inpyrzmp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpqpjho.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmxnvr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uchqifqx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uviiehvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbaztgv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbteniex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvkhilx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yadtsrzd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eddfbvnm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyomaqw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2swqkctvl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2niwoaqvd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtxobat.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxtpsxo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2scjjnvrx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeqbwqw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbeoeuz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfqfvfs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtcjgap.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2immshygx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyworei.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjpnuiq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbriqfk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qehapwbo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2chxrpbea.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2czwngfme.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2morbxzmv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2piaeqnnb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhauwil.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpsoiki.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdunxgdo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcjyave.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bntliktl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nveltzbq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnshnmmp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikpbipk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwjzrpf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxusbuz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2eeljoexp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2veckuqgx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2hchwnnph.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrnjppc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pzagpefw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbpjlhv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hunpqiij.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyjrfff.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqlluli.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmclkgdj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxazoh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jubtnusd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuhkrvl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpbgltb.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzgwhux.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhkrtkw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhatpyy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjhmuvh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2awbfqcvz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaklrog.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2udaomply.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgnexrt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbzveot.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zphtqiwh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkukjer.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqhxuvj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uivkmsre.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicfsqmu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jetveodv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxwluey.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdyxmuk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvihkryw.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2itqxvklj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nodwzynv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udmspsnf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwcfkaj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2styrkiil.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyapcxo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2awoymqnv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2jccljkba.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kssmagsb.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwbmdwo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvrnqmq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hidkmssk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjimjed.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klnygbuk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieslceet.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2afjwwaxn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfwiqsq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpdctf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2frzhywqr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzgnxtj.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaepegeb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uajvfdkh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2njffjrmx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2srynxdhl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2nibsrove.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhqagio.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2aonlofxd.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfngqnsg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yirqwgvk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeqnega.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulamtqnv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzcvjka.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyehzltn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gotcszbx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxdlkzj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2czyxxihg.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ilplfeok.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxyeiby.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfccmbqb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqjwxpi.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ulifequf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfsdjxw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfopkol.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlgpogw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctibppyu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoydjfl.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaqeuks.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkhrgvs.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnvuptg.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwnqbud.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uddwtbom.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2egdcyeaq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyfrutf.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xenhggwt.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2crdunnxj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2nazxmekq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2utgjikts.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vqptigbm.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wawtnpkb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfhjegj.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2unralmnv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsfidxs.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oakmpceh.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxgbupi.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpefhcox.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sevkhjqx.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vovfmejp.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfakeks.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvrvyyq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fafgdkah.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssldxvwq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jszvbudi.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2vumdvqru.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ifafcsjz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtsqoq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2stwdhzwg.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pprpgbvf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2luzeavtd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfllodrj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mirrcubp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlaydgw.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kiipqadw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzprcaom.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2znyfevdo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwckevgr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbodxbkw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vornougx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2torvmcvs.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcxsdws.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2quvqxpbm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyrsrld.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2beeagkmi.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsblbhgu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdwsnnb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewllnyuo.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsqcxuz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkeyucc.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2jujrygrj.html


<!-- 参考信息 -->