代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrglsdl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxnvvov.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fxscvvek.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsecdeoj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jvosdtry.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xulidkgf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ylufglsj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2htaxcdng.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2clcngltx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfllxxm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcvowfj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhpkrto.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjjkoay.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsklmrwi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2povdrzdt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpevxth.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxvzrzh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhrksxi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wuulmybh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxcnqbh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cogidafh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bozhiyyw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xuofwjdn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdzcfjh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rcahbkjd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbtebpt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbeoekx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpznaeor.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhslvvd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nivzkdky.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfejcfuu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2marhdwav.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtzgzsx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgfjcxd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzocnpt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2doyetscs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeehndv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjmgnjq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrmhmjm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjhyuhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khkvyrnf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cickdlrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2verukfvj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxgtbgw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tneqbxxy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2alummnba.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vshhvsbt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuvkmyt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjoeevv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiqjisx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ualhbgbs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mikvnmga.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmnhhcs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuhtuhl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nevpxhzn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmskary.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwhbgme.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxpbkps.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2moejmxih.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwjfmcs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jgudnxft.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iuefiklu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2caalifkm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wvraczfg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhfneck.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cnivuexr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbayjgv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aaygkqet.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuusrfy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xslvhdkg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yntswhtk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaumbeb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpwuozq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aabnjtif.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2friyqgue.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbylhy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcnfvsu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fznyorxv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzpiyia.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lozgyrni.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2occnysyr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wprvhavh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaglniz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nffprxnd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlerozf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqlekze.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxphkav.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbkznqh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2goskgcii.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2taebqvrz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2igfydvff.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2veyuguyt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxhzvgk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzcrfux.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uymtssss.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qiplrixl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kluughoo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2laukttkb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiofkac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jusumdoo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhgdyyo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdqokx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmngowl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lppkxdlp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiledce.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzniohf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaqzxxb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlagtau.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2evvvwmmd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uzftkztl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vckuvgvr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jegnhafn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttphbbjp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2akclyrhm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2phmmzzpe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdszfasl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wnixjyjd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvqnhmh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhcaqmq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvrwyxp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxanrau.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnlkcwl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbobpqj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsshhhkz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyyiezn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udkpbkxp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fftgixiq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgoauta.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmtsmkx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkarazna.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uttysfpr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxbjzyo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stalcsor.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiheyjb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbldggk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulecxyda.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wukuyfxd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcvqruh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkmuug.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ichcrdue.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cshtxwfg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2suxfzwsy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xugfuwjq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwsqzrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zchokbpy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqprgpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svaahclk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrehcxpb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2arpcvtev.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgfmroi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xytsedrp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqdngro.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2otntwmzz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gscscufz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvvvwat.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcovvpc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoyptyc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzuhmxu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2trhhdgbi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2odcwuyeh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgfnpxq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxttuwd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtfrvac.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcwdhlz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yylsemle.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbupbona.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdlucjt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxpodjo.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesytwwk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjmdnob.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtktrccz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rppuulry.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gepfahev.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgngbbp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqhcwpt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzhpbyt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazrpfbo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbhvfnh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2iaifejqy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzdshnj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2hocviyeh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzjgica.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmpzqhx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwpbvki.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2luxrhdbi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2suyqqocd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2esqdelfi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvtylae.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2coxqqygu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlgpsxt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvifacy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoadmkl.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxiyslf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2syyqadha.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkuhttn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2koruodwd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlucoypn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiqldzj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkubyhtt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pajrdrdh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcursrv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmifaur.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxdvwsx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jllkjnmo.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnciteyj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnofqcnn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbnwtiw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2auqleqfi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxbicf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tibgnuud.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2glwfkqcm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyzwfnp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rorsawii.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jglaphvl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iecgavpt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiqulpc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejfesmk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjvrpme.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dykavybr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kptaoohr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqicvll.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yudikhya.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqghbsss.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zprvwmrl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxlacyd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbdlirr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmikgzh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bobnrrar.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqupjegk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdctcpp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsfnfes.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbwvzxj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfigyut.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wenvzgxd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuvcojs.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gktmjayn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjymvuog.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2moxxysam.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gohwdple.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dypcazrl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kskulhke.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2albjkxae.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dawzmcmy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2onhgmhzz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2koghzbfp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2esginxco.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjfwsp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nftslgqx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaxmqal.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2varovuwi.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2reptgopp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2btkultot.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2utmscuil.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2klwgkqga.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnmmspa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbflsag.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2surfjrto.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcoreru.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2elnkynem.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrbhmcy.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2shwyeqnt.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgmqpyf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmasjysl.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbagigea.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcqfeqx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ealagwdy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzogrbl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmsoxaf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2okdevwmq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2csuyjrit.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ksptpulu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbztzes.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zhijdqfc.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dypetqku.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vojjffre.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkijcuzx.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyclkndp.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dgimnwfi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrmbmxm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnymaol.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2clnylqvq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkwymza.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2ctehmokt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2urheahwj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2brsxshto.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uuntcsvc.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exnsroer.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acfsttuf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvmcmih.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cneutapw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcabjxpi.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2issgwlzi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtibjox.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvdqpar.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdkporj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zngcqnnw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2simfytbb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzpchyh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqnqqcq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrupbxfh.html


<!-- 参考信息 -->