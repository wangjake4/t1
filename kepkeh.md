代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdmagmh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qiavxsyu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2chiscgkv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoxispn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fckvmgnd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtrcjob.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2frghcsqx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyulybh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqrdclq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dplgawca.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtovfef.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrluguz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axfaaokr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lzagxuxr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2huovqvuz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fduonawj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuuwxtb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzyhcfv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhnmfmv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqqfdvo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgpwfsd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zucepzqa.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfgzqbo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuzxpur.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2itdkdahu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2inlvuzmh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeybbbf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2avmjrpcq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2plhfbawx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2szmqnhym.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2msarhkpe.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxnczx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vviuhcxf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrydyuh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdterjd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2iymntqpu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwkvonu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhkqflb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbxofjk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoilejh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fcalwemf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lukbgzux.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrjewzo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnwhqtd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tespdrgv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nciddkpi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jktibqtl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcchvcs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjroeydl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hinjndpn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2modcboba.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoihlpm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ayutzkav.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwegzlm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kvquauqb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmpifcy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhdwgfk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxgflfv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqfzmby.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpuppa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvevvgx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xddbimfo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnimtur.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvhpgdv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eywpzmbc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjnreks.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtbglis.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hduvvdjh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oafyccbb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcsrxbx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2saumsyap.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrteumn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgwacys.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcyqazm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhbzuzo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nmapemkg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfqsfug.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfyvznb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jncxaulm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uepcdvfl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2awoujmht.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2srxbxlas.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jadbmtfk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ouymqxxw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsyzbrp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fikmyqoc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyommxm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wauzwnip.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2enrnsllp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zlviilse.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kabvdytg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2frldzssq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdomnta.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxigdzq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcpacho.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2eogstyjc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpsrwhe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvohptt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvlfosw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjbgayi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcjnlsa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsvliil.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dzopeqdw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dstgztxk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2smfrhwsd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dblcbhuw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqkdtq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxkqidw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2imucrdjz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrlxbfs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yimxvfwo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2euhigpws.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ufchutbn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wueejdqc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvambrn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqkkftr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mscruamy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xcekqzvg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oixjiebl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvdwmgy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2aepenpdl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkipren.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lywrskrw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwampwma.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkvlwbb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgubjdx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2utnmkogu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2urfkqpyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzypuvp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuqapiz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2trdltzsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtfcwek.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kspdkvfu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrqmwfx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xevkjwuq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsidlpj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2aneebtrg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzwncum.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjrlawh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwawedt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2glsrralo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gudlnbue.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2znaahsvd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnsoqhm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2inlmgzct.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2aeotwirb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2odnxhuzw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmxznlq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cllcwuhg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzupqbmc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqfcusx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2psfpxbpo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwwovvk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bfanszmw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vtigztnt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntepzhcv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbulvlds.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlprhvyr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txqjmyqv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slcnbdhz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeeqbfl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbnlyvu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhdljfs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaulndx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqtbcxo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jskstrei.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpubaqz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kutvijid.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uybylxno.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iidzmpwa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chdsohyv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmagkhu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kftkxiul.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtzzxtz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vodfaebu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrbhogk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fftxfztm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqwyuhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kornnwcy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbghujsi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2axtjilfi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqqwmkt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2waogrbdk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jszndzrz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihscptbr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2duuqyjjt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvhswnz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbicngm.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2kclurkyq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mapgufzc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfafeslh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ergpomkz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhilnijw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuivyfdo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2phlolfmp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ybobtoca.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuthgwss.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2idazitpd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zevdrvol.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkibprh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uneuhyak.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjqkgpq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyfhusl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ummqxowr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpmmoxg.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtsfqwa.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2behtthqq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwpcumu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epiezfkw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yknbndgx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgbyvvk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2nkejwelx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnefksxw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaiwbwx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxmwnod.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xomqgmlm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2opteelgw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzooosl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cihpiavv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhazzjrc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qexmijcg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrxltsr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpksaim.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaegugn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2duqdjmzo.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2unearhbn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2logmosap.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cueoyedm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2osqxgsoq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnjiqhy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwrgbgk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjfdvge.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iltqtmrb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeaoaol.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwixsuxs.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikbvori.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnhhoef.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkziliyy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzdjgve.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcuhbrg.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2fobupxkk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqcuaej.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrttmpp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwuoekj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxdffqf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mocnapjd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zydpegbk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwbspey.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxhnrjy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zzncohzk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbagtzi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfcvxbt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqynuoo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzwmrvf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utkybles.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxndvulz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czkppfqr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhgwbms.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2awsamboc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrmeuiu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqeewls.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojaarxp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmtntqk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmgrgxb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uztioosv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyrtrpr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcxwuvg.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunkybjo.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfkpkdu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqjkgyf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2asasidgn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsicpci.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dddcvalu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2khdyunci.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmgarok.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hfluwfrn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kymwsjze.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ithlxppe.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gclffraa.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzqreid.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xepyhlib.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2nulvjeeb.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wykstvne.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcijsnsq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvgzzue.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uixrwpry.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzvzset.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxsjfaa.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlxfbfg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2detkmzsb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqirpnkt.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwrmkvf.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2etmnsvml.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbillxqj.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyijgwv.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmekjhc.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dpymklgl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiemwii.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfkzcks.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2deqbtznu.html


<!-- 参考信息 -->