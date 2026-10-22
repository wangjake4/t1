代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fucoowaz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dddkrmmk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2utnbipih.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2slkbvzuo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyjdlfe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvziltmq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yauaskuh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdpsskn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aigwtxaa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxomtdu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2docggbld.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazstoae.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjfokvg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2plsnpkri.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2appddccn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2asawnbfm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2amyxguqw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2btldebbm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fftwsixx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pckrjmrl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsdidvh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyhrxss.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yywunyqg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxrrhao.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxgfjpf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvxuujc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2okjuwxik.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyitzmp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lttsilzv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjabppeh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeqggsv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2izrixvww.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzkdzpu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcjyhbu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yamenroa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ziucszny.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhlywq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsltfzg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjedcli.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyetxln.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oisxeynf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpusqcb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdurntba.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjqbpnf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqsdbjo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnsgcup.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mlllwmut.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdbuhes.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxlfyhe.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmhvazf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2owpkotla.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrzlegj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2msowexbq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jepfuiro.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuqokva.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlqopvd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2phkjqbuw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuujxkc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2exvooqse.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcypvxnb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjnaxsu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhzctgo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yidnehmu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2osytzsgt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jecizdiz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ybirwxeq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjshmchr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdsdhru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osnfyema.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2khxyfkvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izdcnpft.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcvjxaf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyatoia.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfyroab.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oeytwqkc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gduvcvyd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdbouqd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjuvvef.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fyepwbtq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbcehom.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgqjpyc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2imlicbyz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mdviyshc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tuecadfp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqhethj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoidfnn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqloihuu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfxbdte.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjdzwkb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hifqqdmv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzlfxnd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2efvoxtvs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtaxeri.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2riuonlwr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiwgumn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ipueuwqq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjgjekh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gappgssm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fszqeatx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgrqwvi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klszpuix.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zugnkeqz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iudpivae.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hhedbrya.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcmndac.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyairps.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pbufwtlj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2icjtoorw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdsrbtg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhbsgze.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqhpxez.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2owwwacgm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yznzpsud.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sddwggoj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnrdxou.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yjehggtw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uarmhrwq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmvcycz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yeppqygq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyfoenb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2prxyepci.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqkftvj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhzrgfn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwpxbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnjdmph.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqfbke.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uxighdnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfhqqps.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2twsmntlr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fuphhxwj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqopubd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vytioyts.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xumqyaad.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2epugtmgy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjabnbp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmlixuy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2drkrwcyz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2awnvyhff.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwwiqdi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lesldnmq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwygnnwq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqfanik.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pznswair.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrtmced.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2oznebkai.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lppbebwg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2flryvcna.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjnkczo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kuephoqa.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmxtxdf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cajpklwu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeofbuf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvflttkq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lumujjzf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvszapeq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpvtvwj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckojxuhz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcwjhph.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjmzbpu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psefgeqz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtycdbs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uodmxtgu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwgifvb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2onunxbjt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqdtwbv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2asqvxusb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpmzlle.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoosylx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkyzybv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkclaopl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2elnnhuyy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spuuweyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mftmoyjt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxgvjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emqkgxat.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etinaeky.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2izhhbzxl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxvqisi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnzsvna.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxbgzae.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtuhidi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaeqeeo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzjjzyo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2puskmwxi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2snqqzitj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2evvahjuk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2efazrcwa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbkjgyg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zczgkodd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpowqmgn.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2euvzkxox.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrowedy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukohbpvz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2krbmwlka.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqmobtt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwqwkwl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxltshqi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2awrsvjla.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdopqhmt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnxrunu.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkoleoz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2deqbybmy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfygnco.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyfvpvn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgbgivm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kevfmevk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdqbxaw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2smbsydbu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2eolhokdt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmmennj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2sctzhaxq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfephxu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rriyfutd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrnlhjq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dsizmbwm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhvexlq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqrzqtb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnqhezt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrnxnfl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbvyrla.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2juszlpjh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpvsxoh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjazapde.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoetmjhz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjehzjsf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrytlrf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilifospj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqdapdf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsmejcw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwqaggc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdehyrnf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrmnnot.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxcpbpd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeabmiz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fspmzoxk.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgitxmm.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvbfiip.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lphvdbcx.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2othyjzce.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiaupfn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyjiqsi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhljirdg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiyxxaw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecstbzqa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xebirchx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rrldcphm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkmdeam.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnykzrmw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgbwbwb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzfofxd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sadvydqh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqikmpgg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktscplir.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwmbawn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2thgtimae.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzbmgjq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kywntjmz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfmkgcx.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2eififsge.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sskgqvdn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrhgpwk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uijueydm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndusii.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhxtkpx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2goylvlsl.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpjqwbr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hastxxjl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qttehpqf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumyanei.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgddbzb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yffhykjw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tehazhjj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjewyct.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcwmmuj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iejeeobq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwivhulk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2thjsmgha.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjoiitx.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2aquivvct.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2upfhypaq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cegbnhwn.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkckfzrx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hblxdohk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqukewn.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cndoxoja.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnwklkb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rawvtbon.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eslhcltc.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssamuthk.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbsrulm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2idteuadb.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoxjjee.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwsxxki.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2srsvvjdm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2evrbnldt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuyglho.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oitatwct.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbszpwx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhpglht.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyvebrp.html


<!-- 参考信息 -->