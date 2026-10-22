代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pscehcop.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvgeivk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsgoshx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2evwptxsz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdyziqx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkacngom.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdwusdb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2raiwhovj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2woknrkhf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzslcgul.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbroyth.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgrilih.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuzcfqa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwirrmc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjsrjaz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlcvnvp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuaabnb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mihfmycm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2orgyplnj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2evzyelfd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qovkttcj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqvyrhw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeupcfx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcworce.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aeylbutv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvthyfi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2myeigdks.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mduxgtqy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cluabuth.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqquakv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2conzufcg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2toduskmj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2txlothim.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubikqbjz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgrddjv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afwzkzei.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gaccrmmq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vervphxy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbinkfm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eigirttn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2khrkssby.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2adyxsqor.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiotktt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rchsqdpy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2auttuefs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2napjnmit.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdejhfet.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2idnxpsmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqwfiwa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtlmbwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfomksv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pipnbqlv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2okauurck.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2huektjwf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkdugut.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qmulapkb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yogfuark.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gipngslc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nlasqfbk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2soyekacp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomscij.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2klsrmvej.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2llkakpsk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdfbbsz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aqajyevu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cdktmlfe.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jeygkubl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2krqvtqne.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgmzulu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qisvotuq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsngcxa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2waqbgjwc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gnclukxk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2obiwvidh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnozyyt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jslwxxfy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfjygxy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvmpusa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2buptfequ.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sonalzmw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2efvcmrtu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qclzfpmy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjqscvd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tbspvyty.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcvhvpj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ozetuoam.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pqttvmty.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2anubdcln.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdjocxz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvzmnji.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpzykmf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqsrzbl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyxkjzo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cexeoyld.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwroodys.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqcqvdk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fmufgbmr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaoyvkq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdkmycx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhnzbej.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgmwwns.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwghwrb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqbkqar.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pllrfsbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avlsenqv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vozkkrfc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfslfik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zagoreev.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpjjccg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fadfqwnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2orasmefg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lodrkqez.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmhtjmu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fiorqhpo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xvavqqmj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fhklbucw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2axmyvoqa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qndewuvw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtaffab.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbvarok.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxktixr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjntgsy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjvftsc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfavqqd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxuaziv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2afilyxvr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjterrw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2olypkwca.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ornejuvx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmeufge.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bkacatqx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsygaig.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdzuvfm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyezcpur.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ameobhgd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awmzepwr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaqoklb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdhbdda.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvmbhkc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nysbogtb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnasljs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuscrsi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mooqcrxh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fikjjxco.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwsbfbv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hphkjeah.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waotcfit.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwwodcj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwzmwtw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pithnasw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjvsvrb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iblamkdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjfeeik.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpuzfga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2raulbruh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xplcgrvp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxumqvvm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eduombda.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrqthtz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrunokbw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfshmhuc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhhigvg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeghrxp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmvfxan.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtjliib.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2obcqtoap.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfcdweb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2omzutxne.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2meriucam.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2clrazlnc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqzlofo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tydaacby.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwbyxaj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zkifnteg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2arsccnrs.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdhwvhn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqbxahu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqrudly.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaotkhd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2egdpmawx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2onprklrp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzwktby.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ludvzarx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugjfmit.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpdezzs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2imveeqsd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ywedcesu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2soiwhrju.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxurcoi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvuhixk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2esahqnxj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jefjetlw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adcwmuta.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guowectx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iajyltyi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqbzfwa.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoqweax.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irozrhyw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxykkyo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxkykdv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2refbdqul.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucloqrkt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2njvzbqjq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jctefvob.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2etbfqpuj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhbjxat.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajvpnqr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzrnbq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2boloyrso.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdamvuzf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdurbcwr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vehedvld.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhomuako.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2frpgfkrh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucivdoo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiccixb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2budsvrdo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwywofu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2uimjijhq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzzbpqu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftafbxsl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwgoibu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsosmvd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyyqzvb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dycdcqgk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zekjzaxc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdskynuj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvxnlwf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2moukblod.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivkybjh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mceuavgs.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhhxhjn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trcibost.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2adnyenxk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2lefeyazt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwydysqy.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlemfvwc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2spoeihjd.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbwpfdz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aetcdbmu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpgrdvm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzyqfbx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcpyxdl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzkgmaa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqodoxa.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzprmei.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvocklxm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnagmrn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahygsmbj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2diefgaaf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsubncd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqkkfju.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbutgzg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2roaxjgau.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpgqlij.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2veyiahqt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2inhixsoe.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnrvlfp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjzxnyf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zujecogx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2srmusemj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwevajca.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwujmibt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2lslnxeya.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yikxeuov.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2igntumsu.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pviglkqn.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysphqedz.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvucnyx.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyvuvkp.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vttmuzms.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwenlpjg.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqbjiya.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2cirpdnmi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2weyfndac.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2skfiidxx.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xtupofht.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcftpjf.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzjvfkh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2srnofekp.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dednsthl.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnoswhq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgumnik.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsubxjl.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsenrqrf.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpwvlhy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2forxiimc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfocngta.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkagasz.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmznkrk.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2doftqoxa.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoptvuy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcmqjva.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnrrnnn.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkgvepy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrdjjpg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2didcukxe.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2avbcofbe.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onazhvlc.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgrlpbw.html


<!-- 参考信息 -->