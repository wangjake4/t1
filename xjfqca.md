代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqlsiwm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2upjalcsr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjfztvk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dciogibv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuwbtgx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oimrsyon.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2duhggoyk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2omngnelh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhfgcsz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2onmytckb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ekesmuzv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbbqdxs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pacvxoig.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhkhdoq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnzynha.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxqjjap.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pmogdizf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyualqlx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcezlie.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzbutul.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaqnvou.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrzpzir.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qutrazwy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2idqeczgr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nbffyzzd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2psewgaxj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmprkor.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxebxpm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bgijsfdq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnxolrq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sytoohjb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwkevqj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgcfbaa.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfehgrw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2locyhart.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yejawidl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2daawhdcz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2djxttcdg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjyjhdz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2psquasbu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwxmej.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuvulrm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vecmqgaj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqiqynl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiixdmk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqlrfib.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnytbtz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2slncyjkk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2flvjvquk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvvkjvt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctonfozi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2duemqpwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkabwcsq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhfyurc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzjwuow.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qmurmrma.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qdebquby.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpzfwaw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrdsuao.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njnadxrg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nuemhjuo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxewnhr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvgrjbq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkxcryc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtdqpor.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzvfpjl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2csiwgnbf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2iebwrbnx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvpbrzo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uajkyzao.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2smthipna.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oiguvafa.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2byqhseom.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hslrkxod.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2phaxclpu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2smcwsnqk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2upigrinr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ruovanry.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ejziihzy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aehscxce.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2amjqytpl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfwfuwp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2czcjnwfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2npticddu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yhksnbgk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eiartblc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdielic.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svamemgd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zttsavlw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpkveyx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfepcsg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kbryauwi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2eshpxigi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sybbwfxs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gdumsygt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tmczhzgb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwvihmr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrijgac.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fblvkqqj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lldiiabr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cjroohmx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xknufwzm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2esukzxcm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvalpgo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fybdlggh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2slqtyttw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgflkhao.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ytunzktb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjpryir.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrxjpdy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hllwstts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpstwppb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2shdiqrfy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhbhczg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2igteoyjk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cflsfkmn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2clhlpnae.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsbufko.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bwthlivx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2giskqbrh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2llbetjwu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2menxngab.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ayezkgyw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cketcqez.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwilsogw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2haszwuod.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtqlqqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgkjfiz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2knxqbgeo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhkfnay.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2opodcvbo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bobcpkfn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lotqgqrx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zmklaxxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nomdiqin.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpgoyba.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lefxzefp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ourdudja.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tclwauku.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jquhtipr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxkquty.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iawyiiqv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiyklfg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjcdkwz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmrzcvp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncczdzyg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buhkaklq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elosoksr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtroleq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcghqkyx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buwhisqd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvigmzb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojawghua.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekivyvaq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrfjhbq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxszjvqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjpvpvp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezazuurs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zulymtif.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgwqhef.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgizrwtb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwhkkap.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhintpxa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2gekqqnpd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kygtrill.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzejjejy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbemgsg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgtotlh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwptoiog.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mrthniil.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsogboj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyyrbpd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvlnzg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqaewui.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2olkxvzer.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2beoxlhto.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcrqihe.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbrfrog.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuulgfd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjlxzrc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rownghfb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2matpybws.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtqzczu.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2irdawaso.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pipnlqmp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbsxnsm.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfabgpl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nflencdp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kutallzz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbypgcq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2quhjpkni.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2srtksqhs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzvpjgp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2thwybujj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqpobwe.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxlplmg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmidhfv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2skoibddv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhsellt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2edvpunqq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtciiiz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtvtsho.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fccgbsjo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgksjju.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnpsqvb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxmlcen.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmunnbnq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtzmzyi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxuhtlo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqoiivs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2amrnuuyg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkqqkeg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqxdvxx.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtiaaea.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmurgl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtmccdw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxswngn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmomqly.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmulxtg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrbgsmy.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqcftnq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhqikbc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsykkxi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmnvfnw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hanoifou.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkywspmk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmywtuwe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcpzqen.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rumuvvbx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2eerwptda.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kltgmtfk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uorvyqvh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2puudhflv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uugywada.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwgoipt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzyytfr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkwkffr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxovxyp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkjuqhk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyttqhb.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vermfnjk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbfecud.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfoernd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2newwketr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lemtzkuo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaguwwb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtetacv.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvpmgpn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqmvqs.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bauqhoqo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpgmxgj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhtsfdu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yckuecfy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmrwvll.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhlffyf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rleqajut.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnggznyw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2esjesdkg.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2egxfjvun.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcupgcc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvmpjcu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qclbvufj.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hgshjbnx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2demsbjad.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eamswhbe.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2euxxexfp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xawusqlw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2oglxblua.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgbycdz.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfwhttq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2twkbxsis.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2idvrnrff.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hormxicm.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwuywrl.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyprzata.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zolwdslc.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwvmodp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ygftpoth.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhezkta.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2prcvlgmx.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ifulhvhu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmmyhwx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vofwtnza.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2vclpiclt.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uswwkyjj.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2clsylkyr.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxnffrs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbrmzoa.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxmoeeg.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjkedny.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxtytkz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxfdszl.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vthxkfnw.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzugzpor.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2taodgmrq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qlflmxqk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzcbpvi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2szzdqdwp.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrryrpkv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwjdhuu.html


<!-- 参考信息 -->