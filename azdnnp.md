代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2scratukn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrayzqht.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qypzpcjl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2anuusrav.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkanbzlm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cifiwfop.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoihwqt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhxgqak.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqozkja.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkgjxsf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvgdkpc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyemtax.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sszpqsdi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfohhjj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jiokcwiv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnlnbct.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgvwgcz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tebpnvlm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cisfwasi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zajrzbwf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfkxsxy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2imjoczwj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aunlzqbn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvltjak.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnmxalu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebroovtp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqgacmk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoogukg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kskkpfnm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtvexio.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvfrwbq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meyliijf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyqqsyw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjuiihq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dohgyawl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rixqpzad.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnrhgio.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yipydanl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjprganm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hnybunkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meojpwro.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzckkav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbfiwwe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tmabfetx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhmzqil.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wniugiqv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hiioujdl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqliahs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlazbxq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbuzkur.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaneiie.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iayokgmm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bljzjfcc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ruchesbd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrywhyi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2irozuzqx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsxajrr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2soifhnjr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pwseczdm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuyiwsm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pztoopvm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbwpofq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2azzycmla.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pimoxkog.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxdbjsk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpognyy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hubugjxy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jnirvwaj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcnblja.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwofojs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuutzua.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfdyfbf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uctjwbgu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwpzqyl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxztchsz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2abpefyzo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2itvonmoi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2afcuhcdv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2skeopqfo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxtavbg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyzatjr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrjcuzf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jxihjegk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sddxfjux.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvhpubt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnbnzcc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hkclycrt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfawwqu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2blnitexk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgmuurs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxejhdy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyniunv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2oprltgtg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywubunru.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rworcmbh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2thbssiug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvebwiiz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqldkyrg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtfwuao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnegtwl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2umglcwwp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqtyvvy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iditkqzw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdpuopw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpanfuw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2llpqhqkd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pamkzikp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2retsukfm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzanfuk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxpwtwd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2slipxquq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbsmpc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cszipxov.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqkuxpw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxgrlxa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tagwhmpz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2opfaaplh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmaeqwa.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlgwzgk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdokzvk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfrbxgd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2srnwelfk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaqhaou.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcgbmtx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gexerhnk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwexkts.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2biklzcjj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndipczfc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjhnsgx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgadtlfi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjnbeaa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdldpeb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juwrhank.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2offcwjoe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyzqycf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pompsnyh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaztdvny.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyoyemt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xohcmvrj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykohkulb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnkbfit.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoxdset.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrozrhy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbynjvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mokjldgu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwgyaux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omutrtmc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqznzgya.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpxmukf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pimzokhn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rinwolpd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeibmwbo.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyzpkfv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzowgft.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeyoklb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2emidzlrm.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpcitdy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eebwbscc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2slkgzkke.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxamkpy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mginhrgm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2krvwtgmx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmpwaff.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jkouhjsa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfauqgfd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwvptqh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2skfjzcef.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqohzpf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkvqgra.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhjatvl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utqpgsht.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fueykiai.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eojedfoo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oopgabwf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jytjmkua.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsigoek.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olqideck.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2whfamuje.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wixtjrqr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2acvyhwzj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzxjeka.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ensusxyd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2erkjzjug.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2owyntkus.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzyrfpf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeispqw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spcjxfec.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyutoic.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iipkygin.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsbfswq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjumpqs.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ecagdprq.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfedfds.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjzkvcz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zffszvzf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuzaggz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2phlgzket.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2upccfgdp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgjqtzu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ozurqcfz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfpesoj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xggaqpuw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2htovteae.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vctofwlm.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rejikyby.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2avdiipuc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsogtokh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgracvz.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwpinnb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2siwxjwlq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2conmotyt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdwdurr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eelbrnim.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbwjoii.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcecbzr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiypzsb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eobyfkou.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvqatpq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2krymwqea.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbbuszc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isbemcxs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsroury.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyxmylu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrknjtb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrlarhh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2xnluijjw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nehxjqmn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotqafuh.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxsxii.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cttchxzg.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazstuoe.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wosrslsb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmapkkcn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhlatdi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxqzkuv.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2roenigvd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2njquvaox.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuafcsjj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gijcsiqr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaigrcf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeardfc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwtjtlq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoegenv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlcwwnb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsinojbw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqdegzj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nisqoojv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgygggb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuwpjdh.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmbiapa.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cufdtmwi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvbuirj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2burlnodv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oavkcifc.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkwnfza.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2glmafqek.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqfweem.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eldzqtbi.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jalcidjo.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qreotkoj.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2efftxyoa.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhxbzkq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixevtxpl.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dybvjleb.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zaspughv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2syybkjzo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wblbnmns.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qomvwhrv.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jmullyso.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdudiwb.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2npuhchkz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpxouqz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lprjykdi.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jginaxve.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpimxmid.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgstwdj.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qveqkdns.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zixrevlw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2kewepour.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2njfnumyy.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfgochx.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwslvie.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2iveusqxj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwcjchi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufezlxqm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tanlsuqi.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pujekrhz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkkmnby.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgnhqoe.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgudqmv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkyzsnu.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uofdbapz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oolqqlbf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqbkvvf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpbceig.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiflvvw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaucjtn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmeskhm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeddtjz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsowszd.html


<!-- 参考信息 -->