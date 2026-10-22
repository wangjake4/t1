代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcaerai.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uentzwpz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2oluyingx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpejpoef.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcyppbl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqbuddt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlenjhd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnpmdzl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2btvpsdfl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2atfrmrrd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gliyujcu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yojyvilz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oltsyihe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjxhehf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2auepuxhp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mengoaal.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oarsoljj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvtdgis.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2drhojaox.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2opelonlx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjiaegg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgupzmb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bxthwmgj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbimvjv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvammh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2linrrore.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rjumjjkv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vubyzomm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2snvtyolz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzpjtnb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpooszda.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghirdweo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfoxevj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaviytv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pabolmga.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gugbsutu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xxroieda.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kgebxqhw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2suiugoja.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnrernp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nubwxcpo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqugaqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wusoyxkr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2apokbeao.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeebkip.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhjabgq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jabuoeni.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqxmaaf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xknvmwdf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tmanatbb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oankvngm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwkxcpw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ywovmvwn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wowcjrsw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnelafw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mknbejwi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yuahcxcx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeohpag.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxyncbq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoptzqe.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qalhhvez.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gincflpf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wabsdhpt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2meyryjjl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkvafmw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxakwzm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aepsieqa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gcidprfp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkmidct.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pizquvzk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2azwztduw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxveyye.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2retxfyhm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oocolcmn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxrkwrf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjlncqt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xintxndn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qagfuvqa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yhefrzdz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwryods.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pmstvgjd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ojakydij.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuaxozq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlaidtr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrfwhei.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxbizb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fpztmreb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcvhfol.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxuwnqm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yahwbowz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdklqyi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggplzy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fpliikcx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnqkjky.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2amdqhzhb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wszacixv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuzjngt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2owhqbrzi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ombzeweg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmflkaxe.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqpbsmw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qyruwvci.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qefrjfrm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2azjlonqn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaztiic.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvtzxxr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hetjudbv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgiyjmz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2voalvlzx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdnumzi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dvehjzuw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdavmta.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkvxtnk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2eosrkykz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmxmcxf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wjthapjq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhcpjwf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dqellbpc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpksqft.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoxovae.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhmzhij.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrqwmjl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkeqwyi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvmfddz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpymdok.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axjqoxks.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwpgrhm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pahnbvkf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaxlrxs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaguclyk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaujiax.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jogpmgpt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdkbaro.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umvcayfh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iutandee.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogocxylj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeugwpst.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpomehur.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuxekoj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iblarrrn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbldwnrm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnmhntz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaatscm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szdzmmns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjjwkke.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmywrlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcynumuz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kltdfzls.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2znvvnrau.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzylaynf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezofbacw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwkgskg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2venensrq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejjnesa.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yteenqse.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2venvelsd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2iutkjnxn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaleifl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgsiudp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoyxcky.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuneltx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaryvmx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvxqbkb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdngaam.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2syznfwjw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbvpjvw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2aclkoktd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwazjuc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmijkrlq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2etlepyot.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfndtswt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yfghciwb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjvzwqs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sueedtwd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnkpoxo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kboybvmv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhashcm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2anwkdouy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cidfbabz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzdcsnd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkrthap.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdkmspm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2etrggmoz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeanyoh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyofzno.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yffnvbkt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyiaxvm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exrkwmtu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oczhvjjk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvkgdfg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwfvdzc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rukaimdz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kawsgiaw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtihnayu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2avcxkora.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsylxrmq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlglbss.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcstykg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2trcjwibs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqntnew.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrhxiby.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhjuqlp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oskaddii.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrxmxpk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tblcmxle.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2upbxqqlz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2opyxweco.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmcboab.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcxgkxf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsnptwg.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrxylga.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqwiolg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmbgrhy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xueuaonp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wunembdf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbxiszv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqitjuib.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaanjxv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfcitcj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjeiczg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpvahoq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqciyfc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdudctl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpnrrom.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpqanxb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxjvdhq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgvjbzk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxokieo.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbthgfqn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlmkcay.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzexbofx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2clcvhtoy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbugagcv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwhxxgs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2lszgbtmc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyrtrui.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2itkjzxvp.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjcgtni.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnsfroj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfvgazj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lflwwhum.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkeezeh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrwbipn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rhguowqd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oileclab.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhtdeev.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsegwibb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utwmwwkq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwydehbu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtwufry.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2skckgkqw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjivkyji.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmtegyg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lolhvhvg.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gadtqhzn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2diqylxnf.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjdglgd.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkevyfz.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pacmxgwt.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2whixxqll.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aijmpbmf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qekjtorr.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2euqsfnxg.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjiabdx.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgyyjce.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyobqoj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ffayepjp.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqfgfua.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrakqba.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbnrlmm.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgobeqt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxglongt.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2szzzfzpw.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqungqd.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2muyyabtn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoyppyl.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlsboca.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kglnxltl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbeperq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2djlmefuh.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2pegocaan.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cetzcvlr.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2itgrtbbe.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbwlbeb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzntnhs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjlczaz.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eheoqkqn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmtlytn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdixstsh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaaymnm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lblcxdce.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrqjaox.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aendolbh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsgbbyk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2blorgtiw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2peynnwuq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvttrvw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyxzynr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iumpzksf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoktixt.html


<!-- 参考信息 -->