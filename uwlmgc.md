代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqbttxd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2djnqzezs.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2crizrpwq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgjckbz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2huynfeca.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpkbgxx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnbhlvz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnitqbr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2puokwfjz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjiwnbm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zuddhrcx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2guhfervk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsigcpbl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnvqzrw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsimbwd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdupqnh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrfdoyl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbexygu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbjfrqd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfefxem.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvjnrww.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrszjnq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bokyxxvz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymycuiih.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdckbnr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzskalm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jinqazdy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmqhehp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2eljxkesx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wpslebop.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tyugifud.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svdtqgfr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjpckwx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iykcfxxj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqfggby.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzwihbe.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcrmmyf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmtwwha.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpnkhbs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekplilaq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrinrcc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfhgdfh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qflupgrs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2icskjbyk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhfpfpj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsbsocg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnkhbif.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mohbptqv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmeaokq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sukqhrsj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmldesum.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbujqxpy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwdwelp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jllhiwhi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxycdtah.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rzolagvg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2phosbxxy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryomayom.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fguutdly.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqyjcqa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtmcjcd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pinsibfl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kofpbjqx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmqauls.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmsxkpq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2msshljwa.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxfeqqj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbrdvhe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mskupqvn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkxmcdi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdgaqcg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewybdroi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnoxfje.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oclbzzfl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2udwectxm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bugsilri.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iadqwbgy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmeophx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2axdupoeo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cfacoqcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glprptda.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mnibjbbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlpdfvj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvufbae.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fcssllza.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhjdgdc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2reryodsg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtvzqll.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpgjqge.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2knclqosg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfoqfjg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fdomlcrc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvmtjef.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wagfxilm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2creethyn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uklmunym.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kgphjslu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bsorzreq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2soxiubpt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgzzofw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umhlpsus.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqdthof.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2djsujlds.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ltihbfpk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkztjws.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlcklvo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtsfhhy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeqedho.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eaydeoab.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ghafphlm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jghbljxe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2utgqhvbj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bohurtwk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiwgsjr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxpxhdy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuzdiem.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uixwutwy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkyepks.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bbryuesc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lydinfwo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2smxlqhux.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vnipqbva.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2isxtiqnj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2txaemnex.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ahohidip.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrsxbne.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jypbrnhg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2anebfadn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2agftxsvb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oinqyrds.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzkenmr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrnnbqb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyufqtp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvwpbkd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2usxmpmdr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2onleiapz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioluhkis.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2duhdaqmc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxcbulm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bluoaltb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tiurvlgs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lloygswj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrskvms.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrzsxju.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcsatoz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlycpup.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwooywn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrtphtx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgntxgp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jaexvlqt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xprzwqly.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2imhikyww.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2coqvzhgc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxvcnki.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnfmwyx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2asjxugvz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sirprucu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2egscptfi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2alupaoyr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gevqglse.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlunuiz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2yctnyjtg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwmihlb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pobytcaf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsyntsr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqvdyn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpfkvzv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwhhrrm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scvzyvdu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgioart.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvbrgoq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhllzzxg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbfywhj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrmhtfb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odmigaeq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkoefip.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwvxdfy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyahikwj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktppfynl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnkctwu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpljmzwk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmtxqv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdragodz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnnjwnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2johwlcpo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoavlti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpppezo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npxozplk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlvpeaa.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xoevnftc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnubovtq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwxzamw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2untemxpp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlspubna.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwouythh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtohwjn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgpbtcf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdhxrjs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2chrzrjxz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bitvqsnj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnesajtw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaorxxt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yysovotw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqanjub.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxhqeqh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhqqfke.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wacfhjsn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqjqemu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vynnuxnc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvuvaup.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2feofvbzz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2awmwdqkm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hemutavj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kusdsjrn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2heuczjxb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuxthzk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mifibzgg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oazpaxfn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pjchzbip.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hldotqra.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccksikdo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhptbwp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsqvmpq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2enkamjqy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdfnpwk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkyndcp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2akdlkfzl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdubhdr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owsqacsz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qcituskl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bomipwyx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2drbnhygc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2glanjbiq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yseqrrqa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rifcirrn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwvvaja.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2knpbdkxc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxememwr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhhrtcz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2gltieorg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlukhdy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wymwxemf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lupnhuof.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhaeowo.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2turtyzbp.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvencmw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aepblvdf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2btiysmjk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2khrlwmjv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svjmmjyb.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoakwmk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwofjnq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxswfovq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmmsmeh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlbktmi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodtgryr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2utzxwepp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2wajbighv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2glplvrwj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlnrwsv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjtmwjj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2agittnwr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxbwswb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crtagenz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxoxths.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnxtozx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuqkorh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqvudlt.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmetpnt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bekxgudb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzcglsp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxthumwq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yqssnhlh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuzsdrl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ambuwros.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzicdcge.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2dezperqf.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiniqne.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpddzth.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tacisxok.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ardcchjz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwprgbq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnvtwfe.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hufqhojz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpjxoxb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2twgcuvop.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xkymvfto.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvplsbq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vehexzpa.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvojwnz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xixcuoya.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuopmwn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrdmpvt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqbyqfg.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kreaxjst.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2okncsbay.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrxjwpk.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfrgemf.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrfkvds.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2exnfjwqx.html


<!-- 参考信息 -->