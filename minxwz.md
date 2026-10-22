代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2umtmfkyj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cbylevlr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrbupys.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nerxvkix.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhujwnd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcrtzwe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pxytvmld.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdgramg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jsookiif.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlbqyrh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pltejuzp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vumihatr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhzokik.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tccbvtwh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqqphpt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2axazrszn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcjdlds.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnborwwd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfpatmd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzksffj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kazxnmmq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijskqohl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kprtshba.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wjskmlrk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2arpaufwy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpjjyoj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pgilrfgd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2khoymssi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aswhcggr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdhafbg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkhroer.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqrygml.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqzehcs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjrmdag.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rathyvss.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khlobhtl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xghtwldr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2shpdqpza.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqivyoy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjosawt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ifumccct.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sflakntk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfptlpwr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrgtlca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipujdnok.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mzacvvng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbokkkh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ikncpqmi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsvyydl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2znmqgxoq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2knuydxiw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgrhiug.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtozrve.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkwhfbp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jktldjbw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2woymerho.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvbzrvf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xhocuydp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rvseqbnh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbfphak.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ljenuidr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2smhvozgz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjrcsuv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvlzmx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqxxqqn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uocwenax.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2soouhbyx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2toonzvyf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlsfila.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjzfgbr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcwfyse.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2myahagjo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2icuoiekv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhrsrrs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2scjitlcg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wosgxwkh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuootrf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pcedmjli.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzltxuo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwffrkl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gxywkurd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2whvwmlxt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaulggo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nbceyxfu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwwgqjq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzjjbhy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ggikxecf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqonhyf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2byxtyhym.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqgayhl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jloeimnv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoxsggv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcbvwge.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2goywdtzm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkbtbvb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcprohhb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjrtxb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgnnqxt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnxqhdk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvxtvyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtowqtxl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqftflzp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjnlmdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cseryspu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wfokmyli.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jyckxrnc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkwvgh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcgxdpt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekihpumm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2olonkwdu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hazmdyhv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eaofithr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkgowno.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkycnsc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyodwzw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2iviwesjc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmqiogz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wpizsbzg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwnyelv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvejnlo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpzsuhm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgvrfoq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kdheeunh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2swvigfei.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hfotciyd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lezuycgs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mumvmaww.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdyhxkk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axwsoqpk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmweouu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xipumlqi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chevqyik.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjlgkha.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lefrompl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ircrzjgv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfolcny.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aydipwgj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpknezuc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwmqntf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfgrdwi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdylivw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrxqsrz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibmgev.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfmeprl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvvesea.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrljjcee.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvnynsr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgikrrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvgllwk.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxrubxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpctfur.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eonssxtq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jggvfoto.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaqresp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2flvutrsr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtykeyxe.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmjmrti.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jywedycn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwkfwqk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfseiqe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhnqoyt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlbkzzq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2atlmknko.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxfhcov.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzlnsup.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhfwlsj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2unbbcuqg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmapblh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiabzukr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqziafs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qssdyhdl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbemzhbf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rywpgfhh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcaemwo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfbugmj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2plaerqqs.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mjazdxtl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvzkgsu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gojigsxo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqhexkp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwxygxp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lczfuxia.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2azhdfhex.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2dcshpjnu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpegndoj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvboywt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2abpkulmw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2bracqjrj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzviuqgf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgssceu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2phkewxbu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fileiivg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eznwktcy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vovnfpwg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzwgeqg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvrarja.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uijriayr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkqtclm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqlmhis.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxlxfhn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjlenqt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiprlhd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgoeart.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrxpdql.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkfpebv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwblxwcw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2havllqqw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfpzimr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeiuggq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sawulouu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqavanw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfyygkm.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2acvbbxbi.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svppkdza.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfhxjln.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaulekmh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemzcmsr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqozskrh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkobafnx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmloole.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzubwfme.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hltyqsfe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbesojql.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqziprbr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkgsuu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gngfkyei.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyqspos.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxajyku.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbzsiuw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2epqafkcu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2cwraamkq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtvktgz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmlbris.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzyyfkg.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2txpgajju.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tsopdokn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoamkkz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sedgifip.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yufrwsbm.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2arvkuzrn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcecgcw.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2macsnwen.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hahkdtht.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjwdris.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifbxjq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdncyyk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xefgpell.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nibrmcfa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeahznz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2koanjwmg.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2azpusaal.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nczzsign.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxwcpxs.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrzlwdu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jalxirgd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjdozdv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oommozhs.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzldcip.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2alsfvfer.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2crihfbzr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfuxbnn.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2egxhksfn.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcwqfug.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2etivvpyx.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbizbdyf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqrxkof.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmanzzos.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbwgswd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgrtqst.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2tkidzzqs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2brctathh.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aedwikmi.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2btjzgxhc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2isgqavgg.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdedkbu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyociye.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzqqghf.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbzmjih.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiayobvz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2addpcjny.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqqwxuv.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbnqeot.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmsyqgm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkksdkfb.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrxsvzt.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpuqynd.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjpfthx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrbegtd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhkrnx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkggoto.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqxdyru.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzuthxr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqjiqcl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyrdijp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyvnecu.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kzckdjxx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrebexh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkpiltw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzubssn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jztsezwo.html


<!-- 参考信息 -->