代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrsboke.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2drqtkxlh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2htwknvrf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpphqqwq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjsraip.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2usvlnmuc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2akdvnund.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzmperq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2acxukunv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2acdtwdxi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fewnqlma.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kazazwvq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qffvjdul.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zixthmal.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2plhhtjsi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zswniiiq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hioyfaww.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzrnsgs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhhqxkv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxlucxa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmqmodz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ancjbzmt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjbxrhk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ryukvfug.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2comsdmdo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2karsuxxp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrunxkg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2clpqjeua.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfchjax.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gindpyfc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ragtccaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2butcnift.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhcjixg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lexovlqd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2aovcexat.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgfkyde.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2srmijxgb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2isqeesrp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eggmaoxv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nyprvnvh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcctfqp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2knagerdn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wljrwhdm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xyctedrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqcyeuu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrahozp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlujilrk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdkjxpp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjnstpi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyrpeuq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrnjkxc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbhcdyh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smxplgdg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjlpiqe.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvazkmx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2scsfmlnb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmupyjo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2isdriebz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xygtguia.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rajrrtxr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vevquxjc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uwabxrsx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxhjwex.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hzysnrem.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ieidguin.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2spgvoigj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbbfvel.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhntfas.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nwogwgwj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zgingdcm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eshcwxzb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkiihnh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yeelpaxu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bbucamov.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gyirbkpz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzougvd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2emwawafr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2suizunto.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdfnzc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yksnbafr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2baxdvmyn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwhajck.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwsgnkb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaodmxc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2okbcxymr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrorgcz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2laguknfv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmmzohc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pskfdhva.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lboalttp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zfquocni.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mvculnem.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2npkzezzr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkcuuar.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnbpixe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hshdcfjg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hsthmbnl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zngczadt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaaytix.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vsakunso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdssjwde.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2falqsxsz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiptoze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2firyzpcl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwogoro.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pusdytan.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pfihprre.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwqtjrh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmawjpli.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjrttla.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvikyaa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdrqsms.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtgoous.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qcghhqmw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ylahxfni.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzlslfi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwneeur.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rixixnui.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmtjwhq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjncnvl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzbwikz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2camenvjx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhxohmf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2erhnbqhr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rditpfll.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2iskbwmbu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kedkufzu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfmadva.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zksrbber.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2togpprkk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcurtxno.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaasgjxd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgttvfx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmidewo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwezkna.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mexlfiui.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtevxxnk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvprpeki.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbatbbf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmitgeak.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfyntud.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shecbdsw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjwvpdh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoasojf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcfifvn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hceyknfc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2emlaxxpu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwheelz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmlnxgg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pneedfii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxfinvj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrivuei.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqdogck.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsruwfpy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfqcvcq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkphqua.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvasovvg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldilyqzz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2asdaxggg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhefozgq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjftqba.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bofrxhsk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvybwobg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2scqwayvz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sblfwwnn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxfyeal.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfscuwj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2leualujg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iecnxnjn.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxwfehs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2iyddoqul.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ragajnpz.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqauuje.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfasagk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcikgbq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wboauoes.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxmprip.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmmqsno.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbhdynd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywenjvmd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdasbgfx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kidsrbyk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcsujqr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2oojpvogj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrvctav.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cywjuahb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrfdljf.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2myxvmgza.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ufusxgsc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2seeejxgi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcjzewy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tormxkdj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgcbbaf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqukogw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2akdqvsvb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2peaiguzh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaacysb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwuhlst.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupqeluu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkskzbn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rizttlni.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjlikq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtzovnu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2phgixpzn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmunskjy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kohsptwn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ippexeop.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzsikjn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaqwswp.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zohtrsfe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2valbrcpc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgbjhiw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sheoyimp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoyjoqn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlzlcqm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzkriuo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhqcuku.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqpdljl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnvwjae.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2msovkxgy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcawdhn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxvfohv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqueegrh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgouidl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbvilgc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvpkbcs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyckzqj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxcaouo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjrgkf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoochkt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhywgw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbyfobf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgocbvfw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uossbpwh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhitnqz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2judysdyp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xfchnjqh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2abcclcnf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yeffewpt.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhipifp.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpkedhs.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpktvuzp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddazpilm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2piutlmvy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2naillzdl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wavpbivn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2btjbbtly.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yaseludi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2boecfxan.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjdihpx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2phcqngdw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhblrne.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhkxyrs.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvzbkdb.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2esxnyzcx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbprolr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fehytqrs.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzblyniq.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rowlmurg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjldjbpc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkkdhgh.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2unnafkhs.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkibiscf.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzigjnva.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvddegkk.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lymfcueu.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpwoykm.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamidfj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkrzdmh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhaysom.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoauouj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2getzfnsr.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhanzmh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lulcfnar.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cltxowcr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxnopcm.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2efytxopn.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfondtnn.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdrsjnn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2isflwhyk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2omjtqjcq.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bekuouzk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajflyvrn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyultrh.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2phybkhnq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2szdwnfln.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2gzolsvza.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2akjfwtjx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvakibwi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzwwgyp.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlgbzvx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuyqfzv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhewohsk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhxtvfo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koyswjgs.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nnikizif.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqarywup.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrgldpk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhpyckr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2slucmlsp.html


<!-- 参考信息 -->