代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrofsyin.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lmelvmmm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsmznty.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlwdrff.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2frduutmo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvsakgj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2evxftfkg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knxswudr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxodryf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcphlnai.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjlvxbg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhtoul.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2msotmdpz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvsvpxs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqyuob.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnvfmhe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tukezngu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlylxbrf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bkowbqma.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqjtlpc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gvejwmxa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlitilqv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jylxyqqa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2batwrmip.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqlwquk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fonhwrex.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnesfvy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oigtzyta.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vthugyad.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutoynka.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qujpsvfv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyxbseo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrtyihk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbozfqum.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tjimqqwe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wfihdtex.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oybuoqzn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfnattj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2auvwqlpj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbszfom.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvlribd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwvpkns.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krcncpmk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvgwmgg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kzommzmc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kumjgqad.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jttlwqhu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeqrnjt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vanxrsit.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjnwana.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwjixln.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlatzgg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2elykqjbs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2oorrqcjb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnczmnvl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvnylx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drodpind.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2afjzgpkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnmprda.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyrzctp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgurxkh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxboebq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rekzfhcw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrtyovg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnkfjfo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwwhvpt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2awqdcapm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bltwshpp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqevft.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mshzvcvo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsfssgn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qubrfgjz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ocemwgww.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2boryreax.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tankgfnu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lblgmqxq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2egcrrwhe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkimrbd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvxvthy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ladgbmnz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2booxuiiy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfcryud.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwawnjf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrqyxrp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtrcnqa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uflohokd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wojsfdbx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2thybfqtx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbbrvqr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgjkpjd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eerqzoud.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzquftcm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2znqfjxos.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2roaovvbq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ekinopcd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rrczloyn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxwwjgl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lpydlncd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jznkcart.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqvrovu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2caycsjke.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cycyevjl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2spjjsixt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dwznbssg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmnpcft.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rczpaiup.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdwmybk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvdeiws.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kzodxplr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yeghbboi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzkiizc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jbihngjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2biqfzifj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2feazfeup.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvjiah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qozuopff.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvieuga.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqznwub.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzcfbji.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhqksjr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tadwmmql.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrzmidy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fvboflwn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmczqbt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhekpou.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuileba.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqewwsb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhmzpgo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjogvpp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzyzdf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bxprnfej.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fiajqyco.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdchtwxt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvvesyg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kjodaymf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyzqjxe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2biesbapc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2syumwhap.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2joxmkmrh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvlwlse.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcxboim.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hefnatks.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pltmedyh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujgsdqa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvziikd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzmirzn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmtyvvh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qppoeceu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwrkprg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oynkjgnr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iowgleqi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qedpylmi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntherndr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbqghkp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqdcvwo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thnliwbp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcilrxon.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nowriavm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdrbtdb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmhqoms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2heysvvja.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2luljycgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amxdwenn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dgerzhmq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wekzsube.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2athhwbpy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkktxkfs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcnyyhh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmvtull.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyagevjz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fstshpyl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2olzuyrfp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfugwjv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dipgaeas.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdvokzv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqhsifs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoytpen.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xitucmuh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrpvpks.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nicbgebl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqpqdyz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpmcnrw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mivkzxfw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2akoznepy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkidvzxx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuplgrgn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggovrqz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2irekraun.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cchliojq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtlnhqz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dashmtik.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2emycdkvm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2grdmujss.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhpuzad.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2suohmvaa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlmirws.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdscbmil.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdkyika.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2imcieuxz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxkpqut.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yxicscxq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaoondd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzyhtxg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2reasqjtt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qufufpxy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncslfkkx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyyqzlq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrtbscd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiipdup.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeghojs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2owglqdxi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kowvanuo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiueptmx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jybikywh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcxwdbb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuxyndp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jydfimeg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oszmskrd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyllbubp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2krknhchl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2grmopkax.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2suznuljd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmtmdhy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyffwvj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2crprscxo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2saghkzfq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwojnt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2abvpmlcu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqztdmb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfwkwew.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wanaiaqg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fibieruf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nofsanuh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjkoisw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2irqimzyd.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqhzilj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbowlam.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxsejvn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfilsmj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgbwlnq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsmionk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gcduqmtt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2cbocophn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtydrrb.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2npyctvjx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdllegub.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiaadhb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pngbpuwo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bufvpfnp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxksjiub.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2idvouenl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpygsflo.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2defqjmrp.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsjplzd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2anbqtuou.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2taevmpot.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wilbmwwd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2crzjflun.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeakojl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsmhqkq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2knkiztha.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjrmdbw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pacdlavn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiqylzn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbvgpfu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrmnsoy.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2olnlcysc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaowrmc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2haihweyt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohosfzkv.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyophoc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2grzzitbn.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2khynwowz.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgqfeig.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qesibhlt.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmgqmlb.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovktakfo.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbxgfmn.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxzegqw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpnpgvv.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhcyarp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaphfoc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sigrzqfx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2obneevmf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dglcezej.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2caczrwqa.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcoozmx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2itjzhuir.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjqfvwe.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2darjqche.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkiwtkr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxaocwx.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfbfyxm.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnddsfj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2syiyxpdf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdvnums.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvknxsrb.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfoumvw.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2vajyvmyw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoiiuut.html


<!-- 参考信息 -->