代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tobjzbmy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbzibbw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfnxfte.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lebeluve.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzaljua.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kgubrzkt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yexsnjis.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvrdbkd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfgdbpd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqmcfbf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mqttbgpy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2obkcpmlo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rscfxbij.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iiglvkgd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jomadlpl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvxlxnm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxwtfqi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcpsjlc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqhsouz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uowokwpr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkryvepw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jldykucq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpehiubq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaffuyi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mfutyqsw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bonshwyk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2josfxyqc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwqzpm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nroplyre.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxleta.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrvohvt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzboujqz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlvtnqa.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnqttwy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqnutrm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kejyvnzg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeuoqfb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdmrwtf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2keopefxo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzcgujf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zewsephm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2enkqzmtg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwdggna.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqquipix.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oyisrlxy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2riefevrg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2utirbkri.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnufred.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bumbtqrr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhabxct.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiazrvgw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjpxtad.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2csuwuymc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeibofoe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvawkfl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgcyhim.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pscihifq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkjnrkk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dugvyekf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmddjzv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2njbcgpjf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2juhlxssn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2malxrvmp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2spsadhjc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2auxpcowm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfszbyu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyjwoag.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vckfvmjh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhyziyt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkmbzya.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzqkfzs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fygnmfme.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhuwylq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2myxdkaqk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2funefivi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmqhiki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiesgmqb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdrztod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqnhcco.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rozurxdr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqkxpxw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2modoxoec.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkfdcmj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeaqaha.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfygufw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbnstsb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iofvwtjp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2esxnpybo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2myrajqrq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lomagnal.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2etpsecej.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzisrda.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoefjqe.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwmivyf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xpekidcf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2izmcdqyk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2llzzrpvh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2spdknqnc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjntdlr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2owtojvzm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuvielj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wxitqcnu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiszdae.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dutietgj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yhacgmkw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbddnnk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjxurbe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnsapum.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxvjcpv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrgebih.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2swtlkhde.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rucfbczt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmxydln.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzphske.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2rjydawch.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgihcev.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2laseanmj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfhvafr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcuhmkn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wrssrjim.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hjszvtdi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgzurjt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyztobc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlzqgxh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qltssfsv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rwddqlld.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gphhgrwk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yiergxcd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvakhwu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxppyqcn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjsnnys.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmwascl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkxlpdu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxnavge.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtercsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apeedyed.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqxzdyh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzitgbc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeilcmw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tusamooh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pakzmjbz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2whzexjdf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uqivdwku.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nzccrdue.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcmcbvl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2itwkchbe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyidwaq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2puatonib.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2szqtmowh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hycnxzlv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvytedx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrhgrug.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2anbatzks.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2awfvbkkz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lropdkkg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrsrjvh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2usuaqvie.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbxubvx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuuysqw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qslkglky.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krazbusi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akyqihpd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvnyvvl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzuzulx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spbxafyo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvzwohp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxegyxt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwtnjun.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrgepao.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmwdfsc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afcpxbsi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyfsiyt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2enndsojv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmityvvm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2znbntuwj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fptpwogg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvzdsjc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvskxmy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiierrb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfazujdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsfxtcu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrvjknp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmklesu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obkhenzq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcmonim.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aowdacoa.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iazlxkrw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfsmhmh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgvdgps.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlukaza.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2okytwrjo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2trvlzvjc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zeftvykh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwxvziw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkytihiq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogshdymu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bopjmtuy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2shuppttk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2crljjsto.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuxnkan.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvguwsf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yeebtxya.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhdhglg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2motafzha.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvagdgt.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmynwf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmnybib.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvqlrlm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tssjhtvl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2upxvwvud.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yshsctmz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbtvxkb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdsfybx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2shmganke.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jlupskxg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiwqjeu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjubbgx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshcpusc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjzevjp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlhewad.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgefhtek.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqkvtda.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2chotggmm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fceqejio.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iscqmdre.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uffeekie.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udutclhk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhkzuar.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaqkgds.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoorjmk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2osryrpey.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2abovhckd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pttowgin.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2glttqtuc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcyzpea.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2raimusxk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzwrkxm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzknfvk.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxjywdv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoiezpy.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaarolya.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzedbov.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowmacfq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dybgsjqz.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbjpmnz.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2amaatfvz.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlgxmdi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeawiem.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2codkjrhd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwgqauc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2amqfropz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2biwhpqsf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iurixdgh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmtkifl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2giogtdzl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2frjcblcm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzobiy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbddknx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tobpuhoa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemiyztg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qreqyxwx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jsguglsm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjizhap.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeidnndx.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyvlngu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfzmygo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqikomm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpbctih.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvmmmnf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxfcowa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2nlovmsac.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmlmxpy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaitzlta.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqldzpa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpakcxe.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzesjum.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrkbwod.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2emgubmuq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzscyhau.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgqebzo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupvdor.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfswzqg.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfocicfy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2beunnsfr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2irbhqvct.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ynirzazg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2puehagxm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfozgzaj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjihgup.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkerakxn.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcamxvm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoxoprt.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cedusgdt.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2odbkamrs.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyirujr.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2omzpyidv.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwayttnm.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsvjngo.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2viijwdhp.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpyzniv.html


<!-- 参考信息 -->