代发 wailian999

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkyxoqz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzljsiy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkzqihr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhubocyn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hurwselk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbwlsiy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ozavgill.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyvgubf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmsewvt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuorraw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwhunhc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhxjwez.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhfqmbx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjjochw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2glbsfixm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bybdnqwy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeskepw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtgsqgg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vldsqqzk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nquryuzk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2supmkuqc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqgruwd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2knhixbzh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhmlzrv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2owchqvhq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2casejtcg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2oszlylcd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwkisjc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aaixtjtz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjujenzp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nosdlkql.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqafscm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nopxyytw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvajnxbb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2furqvgwa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dyedzpda.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrsqplf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzanxkdh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfxvaoh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zcagstjn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdqjxeu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2djpizsek.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nphftvoq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2saccsauz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zloartom.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzeitro.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeefvbd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2apyoqnab.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzffuiq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljumhatg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrzasrr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnajuqfk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2plwuajbb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjffpbf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnllcii.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufskrjfe.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rwafnspi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzeiwce.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaicowl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rxunovdw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iiktvnyj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2odnckkfu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvbgjba.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uqffuunj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tunagitv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2utkohreh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pextqudd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvqmxcg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxnoeeg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2afdzujvt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2seutrqud.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jigvlsva.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hejwpurs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqykgnap.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mimcmcdc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dytjedbq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xehqfksr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrrpxpv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2urtsaipo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiwuydi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzlwawf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdbwkuq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tocguojx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2htseamab.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkycvgn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2evxkjhqw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eblicbsz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbakwim.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2brfgrdwk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fddslnjv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pivwjzwf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoxzooz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2apyaamft.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2igkcrjtw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjqgkap.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cghrwana.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rhusgpig.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2knbeedyc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdvcpnu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2soszazyy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jghsdkye.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnikxga.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoqmpyf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2epkmcsxs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqcujbe.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqhdlid.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtcyfeb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxebibo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeraafh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdylnpt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vzambepq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fndljaqb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwrmhph.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sowbxjqn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2manlbchf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xekcitnt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzftty.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2szgppsep.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jumpqxwm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gefuqlfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubobiyze.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwwjhqu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvepkjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dikgljpq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yaejtaqd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlgtyok.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rartrhtt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2abqvvevl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqgwyik.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2shrmkzkt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wknwlall.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtsqtwx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdgdnqs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2roctverf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjhfoeg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvqrhnp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrkoeop.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2psjcnvmm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2whcznqel.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lctqolcg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qanqptkg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmocwawn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zizmzyuh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfbmkev.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrjoxom.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvpalrp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmmvjya.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdjdfrl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvatxsn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbmyzbj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxlbmnt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxffmjz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jywcaomw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsicneq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2devbfeyy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srwwivio.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clqcqyhy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjkustl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijishnze.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqdnbov.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbaxban.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsptcjm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsutiwxt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llxesvgh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvnhcaz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqacgsmk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqphisrf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyegsxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrzvtqv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irvjxxbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeebhbm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhjdpbq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwqmeeu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltakrbdl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcxvuos.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hirbkqbg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwftfqq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lntmpnte.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsatgix.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbrarmx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2naonmfjj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mbficeyu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcsrnsd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbiicfc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfevsob.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzalqzq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2aiioutvi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiyfuly.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuxcijd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyrosqg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2viybugjo.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyimlpe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lefmvxsv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpwniro.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwugbiao.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoznzud.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjghilu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hypopjbg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdptrcag.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxjznmb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2axooitpt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2domrqqhe.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjsthuw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2knlrswok.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2okjispvi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqahrco.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgjpspa.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2eamoslze.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzsvhof.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtynpok.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcbjtps.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yohupnhw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcavibb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2parkxlrv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kykmwbzt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeqqnzf.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2arodsnwd.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrpcddh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzdbwcx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2exnhenef.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ropegodl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqauhmyf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjovzpi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2givzoqhv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjhefhe.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvchftor.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aovgxzsu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnujpxwl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2trkbkjpe.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wardmgth.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwvbgun.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqgkakh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ibistbrm.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lybtzmbp.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2pffmjuuz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylztyjva.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmanyhd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypajfuur.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eculjvak.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzglkvt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2veczdnvo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2puckuasr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpqprln.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxodqsie.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcwemuh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avamkqac.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtoyrln.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfswdgv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdzczev.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2uetsvrkh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzsqhxa.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fimcggwz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxzmort.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2susmslyt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhondzl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zriaknwz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfadgboz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxulpyul.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmffqpp.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hycefzfh.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2hztiwxtl.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2tspnigox.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kysqshtv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivluuvnx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzhuemn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bobuortv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgclwma.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iysvimea.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfeiltn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqncxon.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2erhbgylo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwblngcy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2luzhbvdr.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mujuysrp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwxfeex.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojploqm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqawglf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnyovjm.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmegwpu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2stqfagea.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvsexvi.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jooboatj.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdldrmv.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tekeobxc.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpziwrx.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2irmxlcqn.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjssvuk.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sushbdcd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iheohuog.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2njddpfse.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxhjqnm.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tdltteij.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2trodskox.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcigomn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2blmpfxyt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2kmprbqbm.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjgpacc.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpdfelr.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxlyfye.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ingnrgtu.html


<!-- 参考信息 -->