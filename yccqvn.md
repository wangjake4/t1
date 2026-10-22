代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbcmpyg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uycfbgvg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qblmxdma.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxlujga.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfaqcqq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2svyymhpm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nphhvtzn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gchtjlfv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uaazhjcz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnkesbl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmccdvm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsdubbf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ciultuiz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2plqaxzct.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ocevptsr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqaeqdr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2norcuajx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2etokycjx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hctnqmut.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mggnqpnj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rnktxlhg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wykwjhay.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qhehkjks.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vthofsui.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iztvciey.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqjnsvw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kygvvkwj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acygrghy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2crwpiyeg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcwxkjb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfgntli.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbpdzkb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvulnfzl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvzthit.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbwhyru.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hytvfnhk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ubipgtdl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtzzfnm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiolsbw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2acxbyicc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfnxipb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2znhuqipa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2thwoazka.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2faikqhqi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgtzfyd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtmjkiy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbmvokd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlunjjfk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzdlxon.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2brdmrqty.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2znyucavz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijarvain.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gpungvvc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2actzwpgx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxxxtcx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvwryja.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nckqnedc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtmcraz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzhbcdu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2isoksrya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wunqdywp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfmswxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkmcydj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lbderumx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qssqezqk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvwqcsk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwoqeap.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mcasylvt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoxykgf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpdvadf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yixfhjgc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkiwhhq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mninfsns.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbyambe.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuwetpc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2orvvzzui.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2urqprhab.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqctzwc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhuhxsl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kaborvzq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2noqnriso.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjgmadv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgzjgwa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhnwafg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hlycslmq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2htljsrxk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kuodzawk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rravrbob.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrnnddt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fetsizmh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2krmchpnd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jemrptur.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ocktnfiv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2beiiyrqr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsiatcv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2adzcnnbh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvxaduw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgivddt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqorrtx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgncrrw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhlkfpl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2twerlzmk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrdetcf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2phfnlqsn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrtymfd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2byhnhlnm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwagmbh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrqkhfj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfvfedz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2klwlwtaa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ojayhetf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndceuwrp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aprpznow.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtuswtz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dchnbeej.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrvhorl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snvsttgp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrzwuie.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2refltdut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rorsozlo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhlsjzt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oidfwdzu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nuotyinx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ultzxnwp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qeicwdhp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjmorvt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2towesmum.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrqqjbs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtjdplv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cifsfkgt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnbysci.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhzjqjk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmqswsh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkcwcbl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfcojhc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhgpyhj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2duxrosuq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pppupfco.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxbvqgw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzfnyib.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sarafpoo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpfkclz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vlojwaob.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaptdxn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwlcecm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxcytau.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twtzumvt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjzdepo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wflzwegc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmxoybl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhyulfg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdloocer.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnobzdry.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfcuyus.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giukzntu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqhkxng.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcikowmr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkllnxpi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lihvkbgy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuqnzyy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dviistyv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcamcqc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnyvnic.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgblnsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pffeiova.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrayabi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcujwsqu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdekgcux.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bimddbxa.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2alumkqqu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhmrqxb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsalyecp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfxaysb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeqntzn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2blidojks.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfpyduk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzegftpo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uphctosn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nreflwrt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpixwdy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqolqriy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yabdpulr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrazgrq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaapkbz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhikrbw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2koigpvdu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rbadkcnh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcoljtf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aihuzudh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2noerlmfc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtpfspl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gcistilr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdhfmzp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucapceys.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2diiriqfo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcintfxi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuumqnde.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuvephx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpuqqba.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxddyyo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvigyxt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtomraf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhdycsx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vkizlkil.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jygvmeth.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzkgagx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xpowscac.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksazfdza.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwiivt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtxmgzm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2boctxgsn.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yclbukwo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqavywp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbmudxg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqhwcuj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2selemspk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2obxooauz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwockmz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrzgjkr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtjqwpv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2llsjfufm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnqjkti.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyzxgde.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvngzscb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2praggllf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqdnrrh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ermmdlxc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2auzquoeo.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymyfqs.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2etalvmox.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrkfqnh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgxzqpu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrhrngv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvsuaxj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wacjqngf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2odnobfmg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhbvfzf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gbieqdpz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmfczr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmmnixr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrfouau.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2miysvzvg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhuvkyo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnelbds.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olqbbxyt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bdunqpct.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhgzxla.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjakydn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjdgjdk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqavudq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhfytrr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2psqxrpab.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfdxnme.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuwpxmk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2uykuumif.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fftyisjc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsgubic.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gunhksvi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pditnieu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcssnwpb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbjbbse.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztztkpmr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2magsrlur.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxocdbd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rultaygs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxineebe.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnyrzea.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbayro.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbgvfra.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fngrnatm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hojllbid.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktarktur.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtuvqml.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdoeohe.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywydntdy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2imxgdesn.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2swafmcbs.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqcmkls.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqomydqv.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpjjkwt.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwchess.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2epjpyhbc.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uejakkhh.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwupfyoy.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2azbfuphr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkgebpp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaaetbl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdgsyux.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cjynbhox.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfjywwh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ueppnlvh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwuypmb.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvjzjbt.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zufagyxt.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmxqcmu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxltlzr.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrooouz.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifndxk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnseftpl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxqvrbk.html


<!-- 参考信息 -->