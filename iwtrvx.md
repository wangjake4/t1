代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzmwomv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uvizrmen.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhgudgp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tphfxxij.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2trofegct.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmdfarv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nojbbowx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oowdagor.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfifpgm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2isjhxjfk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bjocweql.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwntsxq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcqilyz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jiypkrft.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjfktqw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2amxrqqeh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zedhmpiq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdthawpt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoukxeg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjapiu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2agsfigrp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rblndrhm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgtfck.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkivryw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjosfli.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klehdgwo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrhicgr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjepxitl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2czmhknpi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkqcoop.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbfdqno.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcbixfb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iiznbmfj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdospnvv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xerwnxqn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qprvdvuq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdfqyxl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2niarugle.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbwvnik.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbsqkhg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnvigiv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xajehomh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqlcysy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkeynlu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvghhwx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iywotczr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyomiaaq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzbdrfa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnojgla.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbxviqg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kcresbbn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqzcokx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzxjrnn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2umncxvfc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdozrhjo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hwonuyve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpkguxm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2agaziacq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipinuleo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zclieqai.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzfklpc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pabgjwmg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pygqlsdf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqcxqsd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwxifkk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2udejajox.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwzfmyk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvozamm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vvubqwgs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxumejk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrzujzz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ashcblzv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mndnfxbx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvaplna.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2creoglpw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhkpcrp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gynpbtrl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnkpqay.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aunyybkt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gdupuzqh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuihkco.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oxosgppo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkbffsw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hchawdrd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pegvoxja.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwkhgdh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2elsqednf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2unqlldqf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmnqyqi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2khvsepad.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdnfmcf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyvhwan.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmyjsur.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdtcux.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bvedbuaq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgzslll.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2diydihfh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqrlzen.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dtemcvon.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2swoygvda.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsxjwkv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvmbisn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkhpnlh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2arkrapav.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2whlostjt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vebccdow.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qogeukdh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgtsycd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfgkyvs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2awhyisvc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2slnvodiq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwurcsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxxoxtu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgkfzrh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnlqmgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtycxrq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2syamgywf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2srtmdbhr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kymtqqsr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtbswek.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzqdvzy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnhmfgv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2inyvbkpv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2taxrjwqr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnpaoww.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2eknjatzv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvnsvje.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2srzwahxp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlpwarf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbbgokm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2txpgtlng.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cerwvoew.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkuqnio.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kgibpmmm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqadzwk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlyjour.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlzrrvg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2icpytazg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxftzaxt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttikwuzf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpbwfld.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cesgkqfo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztluavsy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdtuzwi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xisumycn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwswrzd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvdovta.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpzjhff.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvdxtzs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvffxywb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qunlvqmj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sarmqbtv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmfwxoi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdgllyu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrmjnkn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpdgxud.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsuuewi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlpvdxv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xczbwxra.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwiqivk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnscadco.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqvvibg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeyfusv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2esoqwurg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zskqkmfb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlcanos.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfzmxfm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2benysxsf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvymmrwn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jowjpfdq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcfwlyp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrctfexf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgvvlfh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wabquspq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyefspmh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dltpccll.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnhwndg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkoectn.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaubjeq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lapwynyz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2esglqlqc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeclufe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpoaxbz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghitqiag.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjkzhjh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldgzsxw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvtuvoy.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvyrrxn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2opcqavhp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mokpmxbo.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljezzmaa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hktpadpr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsrpuhn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdzfnsp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwavdzf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsxulzt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvcrjsp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmghqss.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2npmbtpfw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2agbopady.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ombffndz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxkroll.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhicjbf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ysitbsfy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjcmpcj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bndeabbo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdnleha.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxlpyoh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rivlmuee.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2trqtnmwi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrtwbiw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfleuox.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sucvjrhr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnsvtwp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhgklhq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnffgyl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrlqpwr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrftaud.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lndmcgxw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfgaoyv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2viciwwge.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2drlekcpd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2exrwnazu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrboouz.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnaukth.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqipeiy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2iljuazex.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjrzzot.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfchzcd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzizljfv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tecndxbj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ollkzefx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2trwncaov.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpqgasx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhetyzf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcyxayb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvckodxf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjcekyg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2myyotwnq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashlbqqq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhmhcbs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2kithsucq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqtzfpq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxisbqqg.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvtswcn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqgqwba.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2avauqlog.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiezkss.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjmktdl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hatrdtij.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qrifamdk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdearnh.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2mloqqgjm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlgmpmf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tedznbka.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdbxyc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcwxdyt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjtiyba.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuugejw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjjtfp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kikcuhyu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrisogx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqkgjdj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzwwevj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzkpquh.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wsydhtis.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2stpyozld.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnzbbnp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgseznj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iprviguk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzluvbqb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2utsdtcnk.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpteqhp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iilpvqyy.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwifsxlx.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndysxytj.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2thqookpn.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qepgvkyy.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pydkcicp.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wapewmbg.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qekgueou.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcaehzu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qolavnkg.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ziguqwoq.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2btcofbys.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqflmhf.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2whlqdhpt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2lriuzhcx.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dzirsesk.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gniwsawj.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2umakuxhq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2avfdvbtp.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tedhfqgh.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwbwbdp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqwzeea.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwdhmyp.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kluegwnh.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuylmiqh.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpbiuoh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyqwcyt.html


<!-- 参考信息 -->