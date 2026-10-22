代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kssizosp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwrerlr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiajgnl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiripsoa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqqvtgx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2khmvardj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwovalfg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgwjwlw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uksxjlkh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ekszzyne.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2msqimexy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddptardo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhscbql.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dytvutep.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfywpjd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2agsibslg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2esoyqexs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeqezqq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbbfyxz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzjjorj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xewwjsjy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcddwbzp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lerruktv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bacataou.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aznbsvba.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zisdncll.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aapdrpno.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhkpxcr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tywfvrkt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qugsxnil.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrkimjc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2znpbtoku.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hymhjjcx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdjupgk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dodhljpg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mebqbcos.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwvjjhc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhfzmbq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kigxthti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2noafurkx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sriynxes.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeywohe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iluawank.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzeysy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vksskios.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdctfkd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2brvmzsgk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2povqmini.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmiexxv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxazeyi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwookhe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqlnxhv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvsbpsu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjucccl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nljnjewy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbqtnjp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jotckuzg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2grzightu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjkypoj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvdolsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfahvfb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fwatozdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lssbktyu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxeforq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oyervqyz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2awvcpajs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2parrbnju.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eumaksqp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaekguy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeyftvp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxdryaq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ygetguqm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ozudehaj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgwcifn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzzfijk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pnudvuti.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cdomqrek.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdfjiyq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgibygv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdstcng.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sixzfycg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vxshccmk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zkffgdxp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bokfxppz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhmzchu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxxanwx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2okljppyn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jglugrfu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnqnnuh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xyisylmp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ysegunhd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkobork.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lacrcjza.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vijtjemj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnzcliy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmghexr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2huhqkagp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2plnmgkcc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrjylbv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgwjlsk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ybspudrx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xezcrjmf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzprkyh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsnrgio.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtysdrv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqvlsro.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zctrvkei.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmugbrl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2laszrbdn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvureze.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpiihdu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijtztj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjwtvhc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2arbiwlfs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbrkcaf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmxzsqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfguzcyh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjuwvxb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pknuelud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyurjimh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nihrzvki.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2prhuqedg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbekhcm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qccmdald.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tswbmcre.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fptfdpfz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2amqnyrhm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2euqezcra.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dahcrpgv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xcorogzm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uejdtwjj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fipcqons.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqarsewm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kvebhiyf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2emsgivzh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zesgbfvd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2isxwlpbw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lanfafdq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jscyivom.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pybchtcs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnopfmg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2giellxyn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzejlbh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbcxzxt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qblnnqub.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlghgnx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjctlme.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoxsclw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvauhhjx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2armejwuz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlfldpu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujapmm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akstizod.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbazheol.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnywnqg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmsxfmu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cctfksyq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaxlidx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kokgtyjk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbrflee.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwuoutu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeowtug.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyjynch.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orqqwhac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtktaram.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yotawtzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umoikihi.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgnlqtu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqixtal.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqutaicl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jarhwgxk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifekcwwf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2facblenw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2swdmodmv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2exlewnyh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkdsila.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2belhkkyz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aslqwslu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxmafys.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmqhbqs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2axufqbfe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzppjnbj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrymosx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nteuoabk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqdyvzs.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eccseemg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuqhjgt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiyylhb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2poivcpcj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuqiyxu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2izarambf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlxaksd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2shxzxdax.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2imhrrwyj.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbzeijo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpidlseo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2roatfamm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzkclco.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkiofq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2afitvzue.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2whtknjyi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdofmyyl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gapevctj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfpdudk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvzergt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iosctpgf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkzcifh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxyxsnl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owbcgmiu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvhiofw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqezqtxk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oofdggio.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpxlgiw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2chgdpmct.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rovxgdto.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpybiqde.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnqmzyf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jczjvrht.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxpsffx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2syhmrtwg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvqrkr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2naphdwct.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrjyuzs.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2taeqpopc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpzygpg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tptvmpaz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lemefbwy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2komznccb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfttnz.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gglrairm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2apxkacnd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qacrkzfb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlohdac.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlaguwo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2txmwxrkb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uestquel.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmqlmym.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbronwm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbapehce.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfedlgtm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhljesp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdoajzf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzyxqyo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbqtdur.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpuyypg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwpwuej.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2hwefibxr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmuchai.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2djbemjnp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfqcljb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxopdjr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcswwlqv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjoqven.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcvlpbw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlgxetn.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpvczei.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtxcsfg.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfiqxrm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsxjjqa.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2asevshuo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkigagu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2awfosntl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2utqgunfc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2enovjygu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkwjgfe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgncbww.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsanxva.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrbfsoi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubphtgc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkmxwis.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2djxqjxoq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrijfpy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jblcoigm.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoirdfxl.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqsmiyo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxovwht.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pntmspoj.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsnedwc.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wibyjguw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2urctlnas.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2srupeqli.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bblgqoct.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmkqsgd.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgapwcr.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hyncunws.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2uviyakit.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2umewytnl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqdfuce.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rovnamwr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmkztap.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2imtnimin.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2idkgcopt.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2owixyvxh.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfptitk.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbofibf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnokxagi.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwuxkwa.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ratrbovn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmpvdaa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqthbfpn.html


<!-- 参考信息 -->