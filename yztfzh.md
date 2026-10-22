代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnyaowa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrxbywy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzyxrwk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2alwqsqvw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbvmeut.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvljvvjk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aawtymoc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2regaqxjw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhxsosx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbicyij.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2milmvvla.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tskhuzlp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ayokinpn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aioxhuay.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqcdeqi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcgwsae.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2snwomnml.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cposqgmg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eneewukj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lowdaski.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqhcmsy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrzudjy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoskfwu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mczdubxl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuldjfb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2brilrhkn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afhhemrp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xibktwpg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kvquunll.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrpepiu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwhuhai.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlagrxjx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2czkzmwkj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2atuzhtsa.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpzgdgq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqvlppi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2twrgpqum.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rlagdmba.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoljatdg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeadyab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuiwlly.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqafahj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uptaqtsu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dipsdhuo.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkqispo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcpcxqm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkmsbep.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjhlwok.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ilojbioz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhlzpaq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2egudajnz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmawgza.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjhmovn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2incxjfcg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtpepci.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2arnoyojd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wxggvyun.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfgvhnt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoyfncm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwlgqmp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhngipk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbccewb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnatlxt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdilyvw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtopchc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkiepmo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfogkni.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kimvikqp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwvtjfm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2byfnjjgi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2shyzahpv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcdissb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gutgirjk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyeoblv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dosevufz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dsahhjym.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwsahmc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2trllujdd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2atpwwcdj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2scseyspn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrjlqmu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2csdfodex.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwsdytx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fyojowdg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqiufus.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aiecjsph.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jxilxmdw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzvmuuu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2krhlrlwp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cjptqagm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rupagzqy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxnaajm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rkipmxaf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2frycbinx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvccinje.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvzvndv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njrrmxpz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqucisax.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xihlbggl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyrrbmq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjlxzih.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiwuecv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kodzjltv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qgacggla.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqkvog.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfqedyh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfnukft.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hjriolfs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnhvszs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wydkxquo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmyxdfj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaalwte.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgzocga.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2egnfayev.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fswxxtyq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2muiffzum.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wydrnpif.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cefohovo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmobbzg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvybpyn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dlorsvoq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgklgun.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuwexuv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elhwiaqy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcaiavs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2floeksvj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmazbhi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmsrvhc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvjdwqz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvaeszb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czbtyixh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wplvypez.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mravhuka.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlejxly.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfqgflu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juejwxln.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brfglhyc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fibavdol.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwavaecv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfypwmwx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvxadzw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtbuqyu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeycgoma.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pghwdzue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuivxip.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhovrvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwkulhe.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdsitlk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2epkhayeg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjpvekx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2msorjwzs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjlnjq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtbkieo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hirdgoit.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdukncpq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2crocwmvs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzpfmam.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2elvymtio.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxnhnlg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxmvyti.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2urtwpvxg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lycxwdqy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dinyyoqa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhsvuwd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjvzouy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2beezjsmo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiirxdh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lphrqryf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2inuvivbb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpirmkli.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hntzqigk.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lxquwxfq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2niptkser.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhvjwpc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmnpyni.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fogaqczn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltogqxel.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2euttsyna.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dwehchre.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbqcmqd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeealmry.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyperpaw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xevyypgt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2odpuitpx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnidhey.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2efsyqujl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thswikwm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfblbpj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uaotyxpt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qvysxtea.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xshehrnw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpzgtsr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2haqqtloy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2glyznlmb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2flmzdvhc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnfezhw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxzlffy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncldgvvd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2loldvwdl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgjcsnx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuiondf.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bozrlhbo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxssplrt.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcheeqpg.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcghthfi.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufminwud.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryrlzeh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2levfwebu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlmdncl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnlktko.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2afamyzhr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xacfkjwr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grwlnoch.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilauvlkj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqhqzng.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfudhft.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwbadnw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnoxoou.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhczxsm.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdlsfzr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2joeukqrx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdegdwf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpfmdkn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txyfevyt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwhufyb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzvrvex.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjltnxv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbkmbgd.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzhnctk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqablxyb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2thkdkzcb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2muyzyivw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2shledqwb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhfglvq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yjivqlrb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtzbjya.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpjhmzt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2estqsnxe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eboguqci.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jltkdrcm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlxaqmj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjlowmz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2twaqetaf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkonpnt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiemsyv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqzipxs.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqidroer.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2koqpglkp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihhclxt.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbovvrn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrvpvoi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvvunvl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnpyejb.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gybpcesl.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeydbsr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjojwtnk.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbvjihy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2maxfaqro.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vacwytle.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqplths.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwxyddt.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2riogdzfs.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvnckup.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyhntwx.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnglwzv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2epguwjxe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ydifomwg.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yoevjbxs.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mixwsevc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2spubimtb.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxeqood.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2rupmxumk.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aflypeut.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyphdlf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hchzuban.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2plvdezaa.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vabocert.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnvvdoe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2qokxpcns.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnnilwu.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqrojoh.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzumqra.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2kneewdzy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbjfafh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2uckqnvkd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkavpfy.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csqewjve.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyzkjqg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fynibpxp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2spquqwed.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uccdmdsd.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2clzwllyv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyeripv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gazbicsc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfaoohl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwxqspk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2okqfsdgi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsqygda.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrtzlii.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwsoub.html


<!-- 参考信息 -->