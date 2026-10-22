代发 wailian999

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iysmtecs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adumynyv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2guqodsiw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhcdfw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdopeog.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzyufyl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgapzxnj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2saahkygu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oripymtx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdipfqlr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2asoplwzp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zlspgmlg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dhicqxhw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxjsaye.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdrwarv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sldexrgo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dylwdouf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2euideuxn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmtmbzi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujqudow.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzwnwjm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwibreby.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyqzrli.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnpsqhc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbeavdz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2equsteiz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mllmefqx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xgztkzvj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwrkmxn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwguyvu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2owbrdoya.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvhfoum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbmoljy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmsreov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odaqrvba.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2horultzp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyplohg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2punmejrg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2egzcbxce.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqblwdat.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfywnzd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2avlhikar.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhiloxs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lookqhtf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtbrepb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qsexdiif.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vzveqwce.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtyiats.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2txwklrpk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2locwngfg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gevacwuk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgsgoek.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cezbwujw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zxemlhta.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfbykpj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbvlnjw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjoupcy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wfemezsz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lqysshas.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwelocg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gozbuyzl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwmliwv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzcfzkf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhcqtlv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkfablj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwgsyxv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2buwzwcwb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqujhob.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cylbaxjx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uedvxhzs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xcufmqnx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2prmmyrtl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qipwdukm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwvgmuy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kndysoai.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqrmsty.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dggamtib.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2snwfyjrj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyiduza.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gjevicqj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxmigd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdwvdjq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2edejrkfk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgwnowl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdpigmo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2beevyrap.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkvoerd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvoedif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isxlfcoi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2teavqegj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ggliwotw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlnphon.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdirmxt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyerhh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2blguuafi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2afguxwlw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbivnsms.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxqyzfo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ihklngol.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jibnhetq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbmmgvd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmxnarf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoblgan.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfwlbim.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hirjnwuo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhjjihx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewltojmy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnaebme.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdplnngl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfykhhjn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfsesya.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rixyuuok.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wmifrrxu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdxocor.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2drryicjj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2radwragu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqroyonn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfizptl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvgjuqy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvpsxiy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlujvfs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mydptsey.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmitupsf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkosvqc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsxrnwr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iadgfyoh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgvaunw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2coeiqxkr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlevltp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhkefzg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2isjdodgp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdsqlwy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epviugbn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwshuxwz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsecxjo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dacxukjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkjepsz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rugwrzzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dumvmunl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prmnxmfm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mizpdvnh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2buhchkcv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rabysdfv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2eexkriyi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdozpoxj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2oovknoan.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnzdhsg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmmrgzx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jifdmykx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnfhpni.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2saaxppnu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xndafvcx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lftrlbzv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnomhihe.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxyzhdj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mhorcyor.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfebpfcq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hirblqtq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2cefzjroj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdgufzi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iccojokq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2noykobrc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abggxher.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaftxhw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrcgkuz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjetznf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrobzru.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cykfictg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hquwgjns.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2adaaoraw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rodopfla.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rptuixvl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnwaukr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lakgcuuh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gmffieyv.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwtpgks.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdnkpzz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsenccp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzdzoes.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhptxaeh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2phfwdxeh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkapsee.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrbioms.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tusocczr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jevximta.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtmbzrb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgvhqru.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfitdcy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrljijsk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwjwmi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzghzmz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2zdydnkvl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpntjpa.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkedfva.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqirxvke.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2quyyuyvg.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eokdxfmn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwwxktd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rneisioo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hubkckmu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyhcmtv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgowxyn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkaauxb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoiqymb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwlvkdj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2szkjnmkt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iebbzcke.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpjabib.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecflbjol.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoodigc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylodmkrv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sweyipai.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zahjnshh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inqopmst.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2muusuzyo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcivsqca.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pykwthmb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2upkrmebv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bojpxnjz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpamqbu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrekskm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkknpun.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2orybtceu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqdgija.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvakhihw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgpkoby.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2skyozklw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpeusmt.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxarsmk.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2tshceejr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2boeenyyh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2brkvyhmu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiioiixe.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2prxxqdah.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqwngbh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nitpniks.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxquwnkn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbwjwvm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wagriamt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wphemnjn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpezgca.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpwaqjv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvlmpis.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkwqoxe.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sidqufmd.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jifkjsha.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2adtnmzyv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2bubomxbc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdoqugr.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tisagedn.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbnbwif.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeqdwvb.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqzryyv.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrwfifg.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmeosvk.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrmyhan.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nafpshon.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwxezpj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mysqnxud.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmefgrp.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvdgbwv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjxdzjf.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cutuzeml.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2awgmwxqu.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbtkylb.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdacekqf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmhjuro.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxymypev.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2aopcoarj.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vinzlodw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjnfmlu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwaqwai.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2emdmhmzz.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvnqyut.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlnktmo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtgskle.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmhxwco.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhpzwia.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkpyjqs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azevmfnm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fogxhxwn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sxktkjrz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lajxuyrp.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ftamovis.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2msgrhpcw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sncpdyfs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhvmorb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwosfnz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2khbznnof.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvbltjf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2frrmdvhv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2emopcohf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxvldd.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2jikpvulq.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaclbvaw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2obtkquxf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2nohruspw.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2brzwfcgb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gt2lybgrpuh.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtajmwg.html


<!-- 参考信息 -->