代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhcppaw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qpstrccm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnwcoky.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvezcomb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2notduhgo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktppisum.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwcegtb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhlymbe.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zrovalsx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcolimk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzmexrp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyokdigj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egolzefi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kpznaomt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcntwax.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvagycp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxujholv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2keyjhuqr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxooayhe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gddazwio.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmgwdkv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeibsgw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ihynwmqa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jshdmvvp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjsdjlv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2obmncpsu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eizubfqo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aoocngvw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfnjohy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiwltik.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbwkhej.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbghzidd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qgujrzxr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcaneus.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzfcgee.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdltjmdf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2upxpmuar.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2atewxxvc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uicamapc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvirakf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2goymhvlr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eozoslkk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpuouzw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nhasecvl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbrryar.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxapjoq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzcymv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2okbnvgot.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqjikmc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qehfvrww.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ethmikuy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2inrnamkd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2alqzdcqp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcbhdrv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiecrxf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2khxagxzm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcdhdzg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtzeim.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbesgwfc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdvxiil.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxkqiid.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2quokqkin.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmkkgdq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubigkkqc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoqdhxv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfdgais.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmgknna.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrwggbx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sjijyvon.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yscbtecr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcimwes.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2njkagwrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owomdqta.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhrrxyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgyuqus.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqtpbno.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbltdrw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zekwiqhd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kockazat.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwrbmny.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tvonhhqh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfqrhqy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ztortyyv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tphhinji.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fggemspo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cphnaoav.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2niuqvzsn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2djjzabda.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlwwkct.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrffqcs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwvusvv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lledyash.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkaokns.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vacdvtox.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkmwwwv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pcicfbqg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qphpocgg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rescypwv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rsivdies.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgavfmh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2troqqlyo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxfzufa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jubogplx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lgikvykf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lqynmcqg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xurlfenk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bxconyni.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2omqcocux.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdgtbyy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kojkqpyg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkrykcx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdjhqjs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfnhufa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuuuiht.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nswclzio.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2widsiqoz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yywkywgz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2udyahuip.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2upisodyu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mquasxaq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzoyadk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlfzoeq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxsbysd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ioavabhz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fswzxfkt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ummzrkwf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkbpfsy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2owxuyexd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efcscfvw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eliksgvw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwaveah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yryveijs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyxevqm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2puafvior.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoaysri.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kerqdxhp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjznpxjs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzpvrkc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2owtmuxuq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfikrzs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2skpnztje.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwmeqay.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyrofng.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2samdrofx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmqyiqw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlqafnc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtwfmho.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulccxxcf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iihvfjor.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqnfbut.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mblkuxkc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjsexkw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wvacbnjv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2sppcrplr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfqomwj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvdqdzg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kajwbppi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glzusalj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2deqsngwc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbukzhcq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kurptaat.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgtovle.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phtyckbp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2egizuzni.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvrqjpo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyawsjc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqmcrne.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kglprzjd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmcutqt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvyftqy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijfhdl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcwhyjl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpvmrqa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2liukltko.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2klmgvacm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlkjmjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2beyytvcg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yloxyddj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqefeni.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfozoh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqbjbln.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhqxwwf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2guuwmulx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jduyxycx.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmlvenu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfcbovf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzkuiov.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjfmdjj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbhlfpe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wujefqhv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pztptazf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnyagat.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuwprml.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2entzlizm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhwebac.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2olvwyynd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlwdyyq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gprvxfkm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqnvmzv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yipgszup.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pweurdbi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovinwjwa.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qryphics.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjgvlck.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbtrssa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klyhwkee.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpupfaox.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpwdfet.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uusynsct.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2egineumn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dydbkoxj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yvytztai.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2buclyvam.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dliqauol.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2onczrtwq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xltlzstm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iivenzcz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zynuwuya.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2baerekiy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnrbxlj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmcbpy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2edngxxem.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2toidnlle.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmvnwhh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcmvvze.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdojqye.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2owocmhhd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gztkeulm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovidibma.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pekqyvrm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezckyuaq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcyjvvk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrdvzmb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ouayrouh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2litejuok.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajhhwn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsohpyhi.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdbpxni.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjedoon.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykupfecx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2lumpzabr.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2drqmspyl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfvlnpc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hukifvvp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjqwduc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uziqfrgj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2twhqfydb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhbjmux.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwklxyhi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lzknwyyp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kepbkwlq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlimzem.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkwqwwb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ismxmdul.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavomlk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exumeivz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjbyynw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mljbyxtz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnpzspk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ondttvoi.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zewvkjtt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2luiqgjeu.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbacaor.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stfhjpdu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtiqbnc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhvkvdr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrtxone.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaaubhf.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2krqgtdac.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2npyjfsux.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkslujhk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxatmrfq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnanygsx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzfuxao.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uimmusqj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkkvdbv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyezfsrx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdstndoz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbwhyrg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvplpuoz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenwbpzs.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqfsrly.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2arqncigv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeacqtd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uucmafil.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdythhyf.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxaejld.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyzdpyk.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwggskw.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoeoukl.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2waslocuv.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2djsinvni.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfatllyg.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpvcshx.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfpyxvw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwkgzje.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrmymgp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmmlnz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rusczrwl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2irlbskso.html


<!-- 参考信息 -->