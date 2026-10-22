代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2azanqjka.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2buwgubzk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmpwrki.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wggwwbxb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aessyxxt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxypzqfm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgzpffc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nytwjepu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gsolwjmk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2acmcngkg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyikjwv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmburwv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzvreef.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyqdwcu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2npxueilk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jyihqowo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cnezzwig.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2npxyatdp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcktkcyo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2otmhxquo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lojiopkw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjfvncx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2irwedtob.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2smvvkojh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcdmyvr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hszeibby.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqmklsb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxllinmo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qmylvtli.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecocnqyc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsaoihj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alojohzr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2opdqzpvy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlezcrm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrbguxu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvldxpqc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wgocqrxk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rcczdwxt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpjbvfi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcpolpa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqzmuwg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwfniqy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuorszs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uczluivj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnvdxbu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpjwczz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjmbwyh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2njkffymw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dybogdle.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pngfujtu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2upbyjsbu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2asimjrxg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vepmiyyd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2adjznqft.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aajwofea.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqjvfvt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmmnyhs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnnefab.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tpynybur.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxglstc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoyllyk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wvytqzfq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gnppvqmc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmtjtrt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmmeebd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obpqdabk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaojfdr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jszigeuf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xvasglgn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtgzxas.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2osltuxzw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tosrnmvb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gorxutux.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvafyte.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2badrkspd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhnqzge.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2clyxcmrw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wujipflm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kureivwu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mndxtiix.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2epljrybm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuozwqq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkihhvf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oytalbsm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjgedjt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zzofypwf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eghoypsj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkmjokm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrqyxfb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cingkkvh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2slxqmbai.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mplbukxn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cawgevkb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yroqdzik.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2amijvxrr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbvollo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rczzzbyh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqgzhen.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkljfowb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2odoirxdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmldvuca.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkmyhxj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dbytrnrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tddmdfao.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2crdujikf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tvruuipz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gebkyyuz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsbniyg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ypildvda.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwxwuhb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2irpnbbee.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzqszqz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaqlkdv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wyukjdqb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxmywkv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2efvywrzd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2szaddfxg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmbnkca.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqznuxu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgfqqyx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aolfxvwh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxbquwx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjdkgbz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xikxqjvo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbrvqvs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrqwnr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuyfrei.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eweosciw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxypiwxk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgyfngs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmujdfnq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwsvgon.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fepfwznk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpokcig.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mblvuigi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsoxyza.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbrgppi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhvjava.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfqrohf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmptdav.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvbbbut.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mulalsak.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpdfjgx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdleehvv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdspwogm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvbbifw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdaydxg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acvmgmzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loojmooe.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzrrmhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hirbdwwb.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2upjiylmx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvfvkva.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzohmcr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpnmaxg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfvxhxy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvmwpmw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbezxsge.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpuqgiu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujazhkbc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vecrtblu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mlglubyh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyficum.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2juvbsasj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyllkhrw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeymati.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfuwymf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fihqeryd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cirdenqa.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxihhli.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2icbheosw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2orwdcgyq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tthpatlv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aupqiktq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndosvrql.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfmvfzm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wibsvepa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jparzrau.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eomnkmak.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lunhwezc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdfszfa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrkgmdw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2egvgyqui.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmrxfvu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qszljkeb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjvgvce.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxfwjdb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lcntnkhp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcgtzuh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iyecyvwt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oltnzppl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fsktzyor.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddslwxvf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zegtnlnz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnwugcu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djhicsme.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hseclnnr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtrxref.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2honrloqw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsmxffc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uevlomxo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmjrzig.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zopdmlsd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpvyael.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvauhdo.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndablwec.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xszqsmgv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxrtspw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yntveibu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqbzhwm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlsmgqa.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqgusef.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2amsfndgw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuytgpr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyjfdyw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lskpdvcl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwslvjcr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2puaeilbc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuanppv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrdegnx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkbltxi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbrhqmf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfvhbvh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mprcpfvy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpbsdgc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orqjnvgn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxpibzg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkrnpzn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqoosky.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2diylmkqz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2usqvnznx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aucemehg.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2detcneis.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyytxyny.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejccwapo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2niluyprs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjforlip.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ikurstyu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrkosbb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qykvgvux.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnynsjph.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeborwr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzsegta.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtkvtum.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyghxybn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqvtthb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbrppmf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpjmstf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2htesheay.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aasppzbj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlndfhs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdlbryw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnjysif.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dmecjyoa.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2urvhygmz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvdltux.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwedqepv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gojkybbc.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dionmipu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2badgixln.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bylnmglm.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaznpwrh.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2umpbmhvc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jefuuelg.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2btdnbzje.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyoolhs.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2otgtsraf.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2adjsrhgq.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2imqblhhm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrsrkiq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gslpndoh.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvikgxp.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fdukgfyj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2adslmlox.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvmlihf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2xtajmgko.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oytowvof.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuobvtuf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkewhjc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnldqgj.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2roxylvrh.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpfddqm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldynkiyn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuabnjf.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2sldckzeo.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgetjnv.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2iucjiqlp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjlydtm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2aziylczr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xisaczgh.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgfhzar.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqyeioy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoymyxp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbeznsf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igxmmopk.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgfpboq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wivmgkwm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rupraauc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvccyng.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxcjxwv.html


<!-- 参考信息 -->