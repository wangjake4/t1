代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeutpyf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2znkngwfw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sfypaxmj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlglkwa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfhifec.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2empkqxrx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwdajps.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2slcjejej.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyodfkc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2elhcuryl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvxylfg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qybtigdh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qsugihnf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfqolpn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2urgrmhcm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsepawu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2seetwysx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbqqqxy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wspkvfwd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iurnwkxk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hveckkxu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2huuttkab.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwcyjrc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsozwun.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2krhfbdgu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqfrlhe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhngtzgl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hpahprmn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jookrbmz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gexevcrl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxgesdw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmadfze.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2frjrqosq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkstjjj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zndxbahb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2spmdtuxk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwuyiyj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoenbxn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2foknbaak.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkklfhwx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrgszuk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2matozzaq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkellecx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2talnkeqz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfkaitw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2itqbgcjh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2heqxmboq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2emhmqwci.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnihdvt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ougchvgk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfniqsly.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2owdahlsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xooeqrlr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2thifqfst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nypyzche.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdjzrwl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qorlmsjw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2urrlwvgs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rtranwza.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsentsf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpykzrj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2utyqltzv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njhsrxug.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtenecez.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jonmybix.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pwogsmnu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhfrqmc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvhjuom.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2biiynnaz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkjfusm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jovxbmpl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vflfatej.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yawdxuzh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dklksdhx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dutfcohl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2extvihud.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fcepkliv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqixafn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2loqmurcf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ciquxonv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kakkrtll.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qelzyeqp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxfradr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmvmggo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fwejrexn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfhwrnj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rniqkris.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgadbiy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjmsbpv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2clktechm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxswrai.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rdymkigf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmdyxep.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvvcwsl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkctltm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaqkoyb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vmveyxbu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dozrvtgx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrtkaba.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nprmleua.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fwijgafs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhjtspd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jbycvkga.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2spdedqig.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzewckv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuvlawn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqbppby.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwqebsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tibegclq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcbwkfn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2oequrgcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cktlhgkw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2buttmcsl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sazaauoh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaxefgl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfmlryd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2lboptghv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxwmvsa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrnddkm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eslhdofs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2atfrdgoe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hzumfpum.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fpinbadd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbvdddw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxucnmfh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjyodxl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuecosj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bmshlusz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnajwde.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfptunm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2brslxbwh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnlkmki.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cjusmalq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoehvnc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjsgybl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krqhrnsr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqjpvxi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrnukxq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuusdxr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtltfqb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhltyzuo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohygympj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmrjppl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgwjtrq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvqykkh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsekrdh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcztahi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsevsvlp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbllccdd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvvkrtb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqipnkn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtydwsh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdozids.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yutfdblc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2abxdhgse.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqrxlzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gptehzrf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiankvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zchexmko.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oozbdrcn.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekizuqvv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bppaizto.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dykmehot.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcxofja.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdesfsg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnioyjr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfruxhjv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcqztup.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxuiqjt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjeruzt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2adtotvgt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqwtmyi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrccrfiz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwecvkzw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pqymsprs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgojzbo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsplmwp.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2etfivlzn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xigdkgyd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2strubzqe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vshtsmhf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lurtqzxk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjiuywz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfwjuai.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqfrkgd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkairmcc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxjhkdo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfvsftq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkpyset.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2woqifgvi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhxyaqr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoxlnzs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzgalll.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaqmtuq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwdgkli.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2chqanqzg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yohewddx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jutslnij.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnjzijf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmszldnl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2antevqoi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbosjngw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adfuqahx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olphlwot.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2klaysjqs.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhumauu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2onyvvbtq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkethooo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2otophxyn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2acwcweva.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoffsuu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2edjuyobq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvjsvjg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmbtqoo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dihaoyqc.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqhltmz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjodigpt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2irbwwxgm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmckfyvb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vptixcxi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmdids.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhumbyko.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiofqmu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eevjknhd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqntfzf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnckogzp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffidgalj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2goglleip.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzomwflt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfkigwy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkcqazz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoxmkfv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hihbwffl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amjxllfc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrkkmlk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabgeslu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlmrdaq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fulnkxxt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjkbfhi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omiyhkir.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jclrrrel.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvsoozq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxgpocr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eksokqpa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyjauub.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeujphq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkbmera.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2huxyjsym.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2buosxpqq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxmqxm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rydjgshd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2prcrxsgs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtfqkwg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpneiun.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjezbtuo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtsoch.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmrwcfh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eruectpp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhfkhzj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vullrqhl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhaysnl.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2msxgsndr.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoqoslx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodtuebx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmrwwiw.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtncpozb.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jihlylbs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhvdikd.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2prnalxnf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqitvppc.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjhzcau.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvqzqsp.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhavafq.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vziohxux.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjvicdk.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzzrkmp.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xznmkaui.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhndokg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2whalqpsx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2blboqkpa.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bttieeoy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2enbujriu.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrvuzxk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2vghhnrwe.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlxpsdn.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsvliqv.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2cseiudco.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jasrgiqz.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2adxhtmjd.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yertzlyx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtjirxz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2znggsqsm.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnxsveu.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvtvypy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2lcluwuky.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zrixngak.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbomhmtx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iigtghpb.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhavtlyw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtnwqyi.html


<!-- 参考信息 -->