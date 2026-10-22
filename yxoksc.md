代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhcyegi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gayrkxhn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zweevhih.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkxiqnu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfnfmpz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeaqtcv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyzhaei.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aniedaww.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfsketj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrelfkzd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jidfcetd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbdqcbb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdbqrpk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aukdqcsz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqxqpxs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tygwonvj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwhrahi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnqdfjp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2erhgkshd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzviohb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sedaciad.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuueexqk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgajvap.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkfcpaw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjgiafh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmikrbfk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gltdhtcw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgjdlqt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2govhxcjj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cziinxvk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgnyvfi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zlurxjqm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2leukldcx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2udjgbajv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2guemlkkj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2krolgrmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgvrykz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2omqkblar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuacmjyn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2myeuetdu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeywitu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2inwzchxv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nwopprqo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxhwlrl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvgdjnu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmksoiq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeqgctm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2purvyrus.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaavenx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rycnnzfs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlijchp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdfmsje.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfrnnhi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2khmensyc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2keaentmr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgpenbq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrjkrot.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cngdyzab.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2swiicckg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrcsfms.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2axjblhiy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rwighbdr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zyujrxfm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nejchmaj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhkjtmk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ditufejj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjiqjxy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cglrwvrp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2odtxkjdr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdinypl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvsdlfi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfycjtl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwvnmox.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yomtmaoa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zanwtodf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klglhbzf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iosykteu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xcptdyqt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fkstcqow.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pdafieul.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjgktdo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2icswqxcy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnwckxv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2belpkzai.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rckwmooo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrwtlyn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sipbxzuv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zeijopur.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kqozztqs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyubyde.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufymzuan.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmmzrsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kntyjxzg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkgaemx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbceacp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umnthluy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbggytr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtatxaj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwpeopx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrlmhbq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmdzhpz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ztustcly.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ezusvqxu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlocxdp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2uyovtfvi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnxsorc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgynmaj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzpjbjt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnxndnp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2aieiheji.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsppghcw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsnbaib.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2csfvxhmq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxomgnci.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2onkvxlfg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsyzytw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjbzaot.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqhojrm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tldkwkbp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czikgagn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luxepndf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qybznwlj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdfnbb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avxjmqvo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyxpkky.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2woognjia.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzinoqwi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxlyhyx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zngdszxb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmdcckm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzplgvu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yknnhrib.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkdithh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aifersbu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaflcil.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntchbrkd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqablzdz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ennkoorc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuqrixr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxqphcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fckcyine.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbdfydq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xftyucsz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnburclj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfctdvch.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2geivhaat.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vokckbtj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvpkbvw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtektgt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2asvroyll.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jynbzszp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iskkrmbo.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nugkrmwi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkanrsp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqlbqol.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxjgdyr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeamwhj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrupdohg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdyysgs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwibssm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvldtnb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mohclmze.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujloex.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bllbjqqd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkgqwee.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwmegfe.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrnzfod.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2osycvdfw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gapqascr.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcutydok.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvqffjl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngetqyjr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqexwug.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlqucqd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlupopz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zlordccu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2esvbpfis.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhifqqd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiqmasf.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfkonam.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2joqqpxny.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmwbasc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2slwwvvlz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qaftrhlg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afwyoila.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hadlnpuo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqinomzt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xesepets.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jygtdvce.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2msszbpcy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdylftpd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzpyevm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdbwyop.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbmfzym.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpijcku.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yahvjvde.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vptfpfiu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dohqcmpf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgxdmoh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgecmeuf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmgvorz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfahuga.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbrmlhg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogtmdxh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrspnpe.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwyflde.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2thngekeh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbotepst.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sduucmvc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fprksnng.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuzvjdp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqophje.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2prsjehgu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2efnqewjn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvhhjn.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhqudys.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udgzxirf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhenoagd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzzscwt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xclyzhny.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmhgnly.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2wuendpni.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsffypk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxflsbb.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqkgers.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbqexlm.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2uotykvtd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axkeomko.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzdcivy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyyillr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2cafwabvk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokftkll.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlungvkn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcjmqtg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdcdnix.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdczivfc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgqnkbl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfknilk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wprmrwty.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfgsqhr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvryxlll.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxdkcpr.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnlgczr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2poozqwbv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyfstgh.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkhdyql.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jibkxupd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbooazi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlgebmu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnlzhbw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsyyxbh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhgpalq.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nktwitnl.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmllgik.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfzbwlw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2okzhmdwl.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fujotefl.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkyynbb.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzhblns.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2thfnwjwd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2awplwlah.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2nykaznve.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdrlaxc.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ubquweju.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cadxgpyg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2inlsfozi.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ucphzhar.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpysrier.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqvwsqd.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwdbnjf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsxusmx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jluetqzh.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xneltkov.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvndeob.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmtnqtg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnckbzi.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2urpvsqcg.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2piqnajrp.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2uoopoezs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2toehjwlj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvcuseh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqosljw.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvrhphn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvvldig.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoqpbom.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lgozlzvi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlcxvus.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lnajtyeq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbkykwy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrnoajr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcidedk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2najgowif.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrzkutt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqegnzbh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxcigjm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2imvlgsza.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cckwnfrr.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqboepf.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2tirptkjg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdawpnzr.html


<!-- 参考信息 -->