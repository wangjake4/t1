代发 wailian999

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwrceee.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qttncavq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjkidzj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvaznht.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lotwdppy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdqywms.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fgonsezc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszinmuv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtvvefc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhbjpgb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crailmhb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijceyomv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdbnjcs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iobifvla.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfletnp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhptnmx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eyonmdom.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2reddyyil.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwlykay.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2duvlserh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2usspmtie.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2elszyglb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2atdelmry.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2canzxtag.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ybehexcf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnzuovu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cthrncmo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzlrsfb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmakcui.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbathqtp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dotnxwlk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuiilzv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrcepvg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2efdncbqa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eghmgzqa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnpsgqi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bxatxzxb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uayrhqoy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzvstys.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sostvgzn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvhfqyt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fogoosrl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkoahmk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgxdydd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gykjltrp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpzsvkb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yzujcyqk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzdnru.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2feqhsdkt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aipnlbqr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cffdeccq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohldgeon.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdvqux.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuupesn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjxhaqd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyajrjb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sazlcbpy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcrfdwr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqrvtdo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zptsprgw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxutsss.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2axvfdnds.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2svgtxige.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cybtlfuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvwcgno.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnankzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrnakbl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eaidtpky.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2seeszgak.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jncuvfge.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2evbvovno.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlrmwxa.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqspnke.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkcamyt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osgpuicm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvivjya.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2endtxubm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlfnwrl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsntfpz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnwigja.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2doovavsi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjgigtr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wulajonp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmzjgrm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbsdmvz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aucrrpxc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxguetor.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmedjuk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbcwgem.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2etnthsbz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ajamcfik.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2roayxjpv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yivdguza.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ownhesnl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdocofoo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxpzrrn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvceudn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hucovahl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgnfagf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2btvjinyb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2typlxyjs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmllxaa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjuvtsx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsqrfdy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmmsblq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvmorbf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkuekhf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvvpboh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2aopwjmws.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgvsbii.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyrkbfq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lonnmysi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wewhnznk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbnvsyz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycodczlb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxnzimh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2siiayusi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnhbfuq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dznfsrbc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvgrnri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoluudh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mghdflaj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyvvgok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzolemm.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxkxser.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqhcptc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfbgfjs.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wppwtajv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2moimxhxs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vnikumqs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jwobazsl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxupsbb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2glucjleg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qenxcjgu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nxazhpva.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxiygag.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrcisyr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ourpfuna.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2eupbilzy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgprwfb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzdcroj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhmhaxh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpkkolx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfefbyu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkyxsob.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpufirb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmuerwx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzbgtpt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqleblzw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eucxdgyc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcasnniw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuhorcc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqecmwrl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmfmjhl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjfowjp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vebbhgoh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpylby.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gydzmmjh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eugkbouo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azddezmn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuwfkiy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umkibfje.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgnmflk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiujftrm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mayriujc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oygedvln.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuoxxkf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cetzbpcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbebrplk.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwzqthz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwnybcq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvdcnqr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfvhbmo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mynxguif.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2heebwpeo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkasptcr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioilxadq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwpndeb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqcervd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2htilduem.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zekajlsa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhluhmg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2terjlcak.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyapdva.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhgzhsf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcwdnyo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwbhbgv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kfttjsez.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuebvaa.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsxornw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbphycj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdqdbjb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yufucmag.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvpojzu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2akbplxwo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpazaei.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxdpwqb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2monfqouv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2meenrvno.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxfrleg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwcljtq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cznbcqna.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvzmnxm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xjahbute.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqsheen.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwplwksn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2uywcvbmp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyecgza.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nefglcyy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kiphjuku.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqallyw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfdpvbu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zranuiwu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwlgazp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrfbnbm.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccazwgsy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgpmadr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2grfmkmmg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjbtcyk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciswgyyp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiaquho.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbogjwm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpporftv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyupihi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyllnpk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvyqepe.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgjslbn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzltjvif.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2krpxrglu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzesxrks.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2luvyvkzl.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpunqju.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2biqwhtgx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdcixfe.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvdobg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2drkicxkp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgtbyrs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfrnahs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwllbet.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykambotw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmgfkkn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2kujvnudy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdurzvq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuazmij.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvagwba.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxhnkbm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zetajhbb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvknwtdv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbccgntv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrlkbs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhjdkrz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djwsrzub.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfcgtae.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoykyxx.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwibzxlw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgkkvsb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mctpulft.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pfexowky.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdbfkcl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzabyvj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlahvqlb.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwrgrkj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmshqzkp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlxpfel.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyejpbwr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcffdlh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eucpstmy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uighyqfn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpmfewv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoxpzjr.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dewsosku.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hytjjobr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iayecpae.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoaigmz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2igvjxbrd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjokwrq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dloqlngl.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqflsnk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgiabbx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2exikkpvz.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxxqucp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2okqaibur.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsvocnq.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsigicu.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iidrbhav.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyutbxb.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uecxwihw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gswxeifs.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oixzjonr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxrkbmc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2skexebfk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjfdbng.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rihppihr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkenivf.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbrzqdj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbklgvl.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtkefjh.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fglxclpq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2omkjynmi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ackvkflj.html


<!-- 参考信息 -->