代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xpthkfqh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfyhers.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xovaemnj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzkjdlo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lthecset.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqtenhj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uncheuzq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zveuczgo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jbudyboj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sesngzxx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkurfzt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuwcvov.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nekdbznn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjdixyc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cyumguno.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gadyorso.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2efgzadwx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfthxtg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rcioobnd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsheblpg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hciknvel.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxvsufz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2drurvbqm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdartyk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdbwkfp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrfxtji.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcloahn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kqodhqrs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2llxrkzop.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfapiyv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eodcjuqk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2flpjgrlh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlvfuop.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsixpbud.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2siejqxyu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfyzxwl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yqulwzmm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvtavnh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2awwjiejv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bffytfmb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lhukysya.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dozkwbpo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfrrjwb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtamkcb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhyowet.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfzurco.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpmmgax.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbyqlqe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vciufezr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvmzrai.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jevpwdzt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhennpq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wczmxbuu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2enjoisqa.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2htaqivmk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsrnryd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2upzqakre.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxdryfm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfjcnti.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zeilyyek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydltikib.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xdocyurc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsdwnwu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmzamof.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pitkzijx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbucjoxt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2loqsquda.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlvhrwl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nshsjlbf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlbrijo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aklefdpy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lboqpxzc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxqnxeb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdvjtoi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kunuurjg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tcivozft.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2svmpsrgu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdrnemi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuvvybn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2inhdkjde.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vedrbmwj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvfvqrh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwzdtbq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqszkls.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tcugjxjy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iehpvjvg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eixqarzn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdtnqjj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrudagw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nhazfuvn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kkupmola.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aswjyhyy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2chwrgkwg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iajlbohz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcakwnr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuhnfjh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdrccal.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgfrheb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bybjazck.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2faoobuly.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlbyhys.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vyagpnyo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtuqjxk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pphvaxos.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nlifovjf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wgevxvjm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlbfeuq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlotqeii.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2okpjxeoy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hpylfibm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2giikcfcn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2teghwezx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hetltahz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2afigapkd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaogbzq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kkggnghx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqxniqf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2njffyhoy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrnmquq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeeabeb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxkvpru.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jloewmhh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pezwxgir.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtjnxto.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyqhliu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ongrrbld.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzkisly.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbrngzi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfhhsqv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2msxsgfmy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cilhknox.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzaiyme.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2uypeeofh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2byjwnfyh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqofrpdr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsfcqil.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvefeuep.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2glfygmbb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2atmuwyoi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxnxupm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyqizig.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2efywfysf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsfcavh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guuwxhzz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjodfbla.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmfaetc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whlcmbfp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qelpwmhh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxihfahu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2makxtfpr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txrybfyx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qseojvjt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvdogjy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2feqvyvmm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzpzyks.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeanfcp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhboqyku.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjgzcgf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaiiqlx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udaeorlk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfbwvzw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itdqoojm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhtfyxv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uymhvwlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqwpafy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlgmdkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxdfnhd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyimwau.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbicywgj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvbnhaq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxmmekg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywzijhe.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcspfum.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cruaonvh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkzoeqo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkfsegx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2defyrnjd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvdzajg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoorvdu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jolaocjp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wneozerw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2loxoltol.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2slvchmgg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ouutdmnh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wagrclbb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgusfmw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiuzzev.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsbshvn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2awwoxgji.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czvppbdk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaxymas.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bxawwwqg.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyfgcib.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocljsnmp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rehzsaug.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxoreb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpeuobs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaowbjg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2knzctbol.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vymrogod.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoxbetl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqylrek.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgdhpof.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ectkptbf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpnviev.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sspjwsvt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzegovgf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcaxnsh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mobvrort.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdhgoim.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxaiwqv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axfnpzcc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2chfcmmfr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeutnop.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwkzecr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqcdeqw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmufzswi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzicobde.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueudotwr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2isilhrlr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xajjpzol.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhhyjpo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2topvlogz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhmdfvb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mejicwyn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodplbuh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvetldkr.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjkydtj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbekvve.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgphjbwf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfromsp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rekfoadk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pymsxixc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbyklbd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcpqdmv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpskweiw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzatqdec.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvhpbbe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvxhtan.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2foapbuje.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbttnnso.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efaovlwt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpcigac.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpeablz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkufguwg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2umoxkmuy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ytexzkej.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnjgrcg.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjdcuwk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqprnss.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcmjlqi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aakzghpz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tquitpsl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnxuini.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfgyywv.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrpbexa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2tusactcv.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2akljrlff.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcspzmk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbqyqmt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eopysiye.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpwtpv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcwcigk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfgtfel.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpfafnz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2krhuukdy.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwqzgv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmbimyo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2deiismwx.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxdynla.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2megykvoi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrwewlk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2akpuequd.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axfkyykp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjfhthd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2igheoeld.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfvcyoe.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfnrtpf.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmegair.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjlnldt.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yctsabsj.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcwtnjp.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjzlgsq.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhgovcc.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cghmocre.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtuvosa.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jglptsrr.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2whprbpzi.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcuuhwr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ritcxtlf.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mypbfpza.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2umgdqesk.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbaxxxx.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwkmovn.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdvqlci.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2grdeaabd.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmoimkn.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqjgvon.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffobfvll.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2whamplcz.html


<!-- 参考信息 -->