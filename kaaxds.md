代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2anrojcal.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2svkhbeoe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhdnchc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkphinrd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cefjplnx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxiozqc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbccddd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kltlqaon.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrbzzpi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2elxzrvij.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhtwomm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2thdzvcae.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bigeppfs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsaosnd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2toqrdica.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdneull.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sshjqiow.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mollpmqg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvarfiqu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kibbeclp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyaorsu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtxoupz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvzxmlq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2adsdbzqe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvbecbq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyobvup.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cudcvrgi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chgfvpzc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpdiycx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdnupma.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpczfbot.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcmbovc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bbozgizv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxhbwbb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2apzsqieh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2stmagvtc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgtzvwl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbhvhyf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ellissyt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kotopjvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mekkcfby.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iowreeva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iewrnear.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfrrbsp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2umxphrpj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlsijyr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvgoxli.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xqublcds.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfybrmr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2srzsbybc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uooqaqeh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogasfyyu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2chtiargx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzurpty.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhyswqc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyfbibq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xpraxnsr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lctwblgb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2auvtzzcl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqstmyn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeslggd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgkrvgr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2duwgkpex.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwgadjg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtudovr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2foyfxmcm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tcopxdna.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkszzda.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lhufotcv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2asijfbvi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wyizvmul.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qaejnjhb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvstqrn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lohodcmk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwpgox.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eroesxwb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqeybpv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcbnxba.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fixomqhm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tdttusvm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2avlmupid.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtbyrra.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnsupvi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2njqbudqa.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kblwlbke.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrmyhez.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjbuzll.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2krvogifk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzcpwpj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nkznysqi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzsvsfh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbnsynq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnwkgvx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwmsqhi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2watjflbm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jaykedix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkivzbl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqzhsru.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cjelqjct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkejfud.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2riqftzhk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhiuvtl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2edhpugnh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2imypjufu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbwjfqx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgyezkg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2heljcddt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2darrbbqh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtzuxy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyavgyw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvxotmm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkzjesg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsvqrks.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsjawdz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzznqry.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kminjhbw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcknuvxz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zaepekvm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaywqlo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhfjfmv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2svnyuapo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vtorptha.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrfoejo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syykezno.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inzgslqw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcnmbdm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbqchay.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxcwysq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxwsuvu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkidwsj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsoituc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpatqug.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhqvdyp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkudvei.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbdxogl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfmxcex.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2woaeqoqj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2maygncjn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hucyduwk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqwpqcz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gceotbgu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjitelaz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqdqlda.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otzwbqbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2livrpgyw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqprvkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpocuuo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjredoay.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxfyxiv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrypjy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvzxziu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsctgrdc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzygappf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2obakfpfd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2teobfgje.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kovzlawn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmloqrpd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mdukedbn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcatjtz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypirftza.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtcldom.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvcvtyb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lrffvchw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqcsfqq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oimqxdkb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtjxvua.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vflevofs.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2asabghkb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2meysxirp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrdmblt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpklmuxy.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rpihhlsc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ganzizvc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dreslmol.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzzpivb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjvrpas.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fumzaxnp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cssdyuhg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfqpwcr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wihxzerv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2mshxeqvg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbctzxeq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcyzcqs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaemsab.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfyvcmj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rerexsie.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prhlgrpd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yusjsgor.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iocjlzsb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrnewrd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcpjtwi.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njdddrks.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2porglepc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtrryuf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tegbcnbt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpofhkp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsglqlaz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmfsfy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuscodm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2clniqzlo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2veuwjudp.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbsuwve.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiepfhxi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2efxrxsis.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2niyxmlja.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2thejuqsc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgleond.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aonnarss.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2okvexggp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xesdxorn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gvalwoui.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2swujzunp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxoilya.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2shzsyfhq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2byoolbrp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmmarkc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwzdgwi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkintwh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqjggmq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfndkffo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kubsrcvl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgpioqz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twlobvff.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlogglfo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjhjbqe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdgndre.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhnxdoo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xicqwwdy.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pinysmiq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmglnixh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbrhvvh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxienbm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ordsjdaa.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkjrlmd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmciobb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqszalbj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnclkhgc.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvhccpd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rclbfuvm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2axmgldmn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogijbscc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdegrtk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekujzgov.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbfzrip.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgnakw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrdfnuc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwehdxx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaskvhk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoldjjj.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpludzc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zvveovxu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvziypoa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyxnzop.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmzajtt.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2grinxetq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2brvqysco.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtseaae.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyrynwd.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2flywtfxc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbtutgo.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2unpuasbq.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtfnnbf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkixredv.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcgntvi.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gksfdrrw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxswskj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2knbfwypp.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2eszolvuu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vmijmdny.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqzudwv.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zicmdzxe.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvykymy.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2esbkedig.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2komtrnnf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfljouyk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2acojpnfu.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lunfwjam.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ponftpcv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gupjsupo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkhsoyn.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrbtdla.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjugzujg.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcrkowm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqoiqtr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzynycjl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmtkejk.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdwvwxq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlobbgs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2acdcghjd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2itjkanhg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txhdqvcs.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqmdxmt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxutgfsq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axacyffn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2raipkthl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gumxqzgk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mffahgoj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuujzlc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ccudioys.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxigyxf.html


<!-- 参考信息 -->