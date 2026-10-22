代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuizbnb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxncdjt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yajtpikw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqucpuah.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pctgwfbo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjdspe.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sikytksq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjlyepc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2exxorghu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcdcsgw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbyjqny.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2povviawi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szmbwbgi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcpabwm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywudatmm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffymvbvv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2frxwfubc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqawljg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oknouulz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axydjziv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oxysfqkm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbevsldz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rudkppyp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jchgjizz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mrawlqyi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsdmqji.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aapscpzi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2haefodxt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtjjbws.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rswnipke.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jablaxdg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvenauk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhswfzq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gieqhelg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrrcdeo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxfqdic.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pepyoxqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mujpbtqx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgbqchl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnbpxli.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kspmwqij.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssidnlbk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nppxxtqp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2owmumigz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqdbkoz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxqstrs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmarfrc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bsodwtmq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjbprvc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uarluhwl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgajlgw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwucxilv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwdvqwx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyyyqfr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfohlcy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvflpnq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tsydxnjj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhdsvyl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfemscyx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnfmcex.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkxbyfs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xrawxqtt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlovolj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2figlbnmr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpbsjhb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jejlzsbb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2byyiswvp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuipgfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aztplkry.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjniveg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzaabgz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qbynmdni.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzjznrv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2prscbgdb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vkizjkal.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lccvueor.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaxidne.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2icxyxzgh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaldufy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hmefdpnd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kwssnsqe.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqduorz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2eklxxnar.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxlbgpt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzcyqai.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqqqnff.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bzptxcyx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqbecyt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2coouypsx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkmeisi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iukfgikf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2epdgmkgu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cltuaheo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oepqdmkc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rphpvcpa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvsidpj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kdceooym.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhngous.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnnhrlr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtetttd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqwjmhx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2myfxhquj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxhqzrv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wohlwrgr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jczjcrsp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrmdwus.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2agedjhyq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ztplnfdz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcbobmk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkcydpo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gblyacob.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rhycacoh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoxmpge.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrsrwck.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhradkb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaybahj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dtytdtmo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkdlnts.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyzxpjd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2njhckbtl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zvglffzg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkjlmmf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qblptsog.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rbowaqai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwnvgei.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnapqpj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzvutzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cixjfjml.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fuczntle.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2opwxgxib.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsxoxnu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yoepdleh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsbxmwd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhjdrwf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqlbnko.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sckuynob.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kjigswaq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vwogqrmd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2awyckdsq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuxzitf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlbqlmu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoxsbkm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtefilpf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcyjxvi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mamuztqc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahylnmdm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvytsft.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwufkky.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xlihlawk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwtdynn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkhzbin.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmnkxkc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpfdkkf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmefxft.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnegdwh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkcxwvw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iquhykei.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrwtttb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iujtbumx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owapgfli.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqehijua.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyjkhpc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hocvpqcn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huokpesp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjlxuxu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaurssmw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2duscislz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnoxxpb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2efaxjqvd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lloatlda.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eusrahgj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbujblx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paqicnpu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjcleuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oextcgto.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vivmzulk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2talkpuxo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwkxpxp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sosxjoac.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpdneqj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uusrslbc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dktthlve.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zktphtju.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdymxeb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhdflfj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pgicldxb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoartsp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxqcymr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbrnrzo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdvamav.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bybbjowm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzjwtbx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzbjtmi.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoajpdk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2byaeiqko.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utkffkeh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrarygyz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydjgace.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xumrldxc.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2igagzwqz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rblavtku.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoawxfua.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfcviwa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdydoyjf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuplejb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqldjnf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcgdybe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gecmzyfl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2thwszokz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqigrhjt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtihltzn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsrgrrr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2exzalwxu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsfogwr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2euffnebc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvqwalr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhzsgun.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwmkvca.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnbjzbt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wutytwyo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ykixvqjt.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2buhugzor.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbxlgpb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2irukfqyd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xztcdewz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvnirjg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbfjwxu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfqesqm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2isthegmm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpddwvg.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkjmioe.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtbcvob.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghetwdme.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxflags.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbshfzf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpygheb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2htjsodes.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlbdedo.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaqmlwp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhkyooo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvfidlq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbeagg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrhutdm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpxdzzj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbrmucd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsrqogd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlivxrv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdmmjxs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsqaomt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mibjsdwu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgblmwa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqftjyk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phdjenhp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ildofiwr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2sdijlcfu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzrjawv.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnbsynu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbmmqkc.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcilvsro.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokwcjm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyndmgy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpgiyoa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmbzzvr.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmujhtw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtnboof.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakzicx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvcgagd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnbdmnb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjazguy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kktlgzez.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxqwcxf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2igderfnw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gemdeyyw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpaigwq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gwucamjx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjhjxnl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmjutfa.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmojfsk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwalyiq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqnnurt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwrbrie.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrnsyef.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2skfqrjjl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnynqejd.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcoqcbj.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkobpkxl.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyxzgag.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjvchiv.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bifjyhqf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2atligsyf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2otfgdeiz.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkluuxtb.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nompdobm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuyglnc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnrmmwo.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmbwhcn.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2atnnycla.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwhydkh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhfvpjs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2flvmyzen.html


<!-- 参考信息 -->