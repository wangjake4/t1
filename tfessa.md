代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqzlcwp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ycapbcai.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zcojjehz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2omliiiiy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sulddilh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfknmmof.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tjavnuyd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpkesod.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wmduqtgs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nrprwhnu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nlumfqys.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2szdzojso.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsgtgxe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyamxss.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2anmklioe.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gppleetq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ualyjkmb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjoencp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rvatxppv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsjzsmt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqsteme.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ewysjaob.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbppqhz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoolpyb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gumdtkjx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pgohlgse.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmqixqo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfhkcoq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdzhzhq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bzintdgq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilavoxie.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsfdjvi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hobzwcde.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcowpzh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ruprbnfq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiieilf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2znofqhyy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2faaumouu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbalanmi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vddzavhh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kridrayf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoffkdz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjobreo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2emhuhudt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2viaeghri.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kctwaxpk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kapvszhp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gigofdmw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbsrbw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwztsxj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbzrpup.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eafvaoxl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbvmucj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkboelak.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yptfskfz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fmemcenh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ceivlnqx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lduwzzrk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2slquqdaq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2heziozqv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rblpqpjc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgplddqn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ppptyylk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2awrlyhem.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2brumggvk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxunsllf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfrqzxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2agxggojk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjpdmyv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrbqmtf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pghskdqw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqfgkbe.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qielfkaz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnpyrgs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcsjyon.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2swogamex.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2shhezvlv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rpywieus.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2igmuinzf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bweqvxxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odnnhkhn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuiohor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zauioybl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pocgyyyo.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2owvlksde.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pajdgknd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2twrsmugz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwxhnke.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qepsusqs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqzzlac.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzzuffv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjryyyrm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvlepyr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrhwxwj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ztisendn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmgqbbe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxaxraa.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2abzcfkgf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fprbvmvh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xagvzuus.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlloyzs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqbwqbw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbkdybx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyrpesa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzvekd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyzpyid.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pazbjnhx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2prvomnid.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rjioulwv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2njeezxtl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2urvhsujf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rnufjidw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2whokjgmj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxlxiqr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpochjhq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbdaowq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wunobuql.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtxtalx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wntpwsgq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxzfejp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2soodqcmm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmjkkyk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2daohsljl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcrbxhn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2drcvbtgv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2loxcaysi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhotpnd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlsryyy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkmbawc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eshrcxih.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2skcfjlos.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgajiphl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrwmifo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2accyvyqj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2efqqdbux.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwwvljm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoghhdx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbmvktf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ahygnueb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhmhjcv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxmwcjf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cttaspcp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzxhbyn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2shnsmdfx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ieprkuob.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhqczhl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcaddip.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cekijjkt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkhmigd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqpmbdu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhxheto.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpefoca.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxjazdc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uadqebwb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzsuect.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2isenisln.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkwgvpz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtscyvfo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyjclst.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eivznxre.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qbauboby.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfkbvxo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzwofgx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyebnyv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srgqmolq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkazfgkk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkecbmm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zafhawic.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjtokyr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfeeiyr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvleatv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukemyfyh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogozicoc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjcvndo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtcmotj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkowczwc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqpdfdr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gedzlhfg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdtogfh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcvpygn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iynwttar.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkerdvo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgthdcpy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqzjzox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqcsqkn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2udxwoeqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puafsodq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlilogq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ophofwzs.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fygovtlf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmogjcdq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsyfyir.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhekopsl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2adnikmxi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmcvyxp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qswlkufh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsnasvd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbroqdp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2etngwwbv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2htuvvuvi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2toecypfi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbdlzvf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgymwiw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kgslupgz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuekdqy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irzmdmku.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2isslsjxa.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrjmuwv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiutqep.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jypbkbek.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfrwdye.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdecvaq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaiqidx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqzbilk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqboqqo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzajfwg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvtcezz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtltfiw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jsblbbjz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnelcix.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxadjvo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2khgaydbi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgmehhu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lfopebji.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuqeeoh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2syshoktm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zezfekxx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuwwnbc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvaewuw.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxstykeh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjguzvo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fqonhacn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlbuxvv.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oilsmzmk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjrmyoz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhxqryb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyftfde.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2coavvhpm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2freqnmnk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bmydfbgu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqwsquu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkghahpd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2njsqwabq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2obdnhkgz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kybvuabc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyktmapl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpecksyp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oarbanat.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzgbemo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoxhkek.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2znumrbna.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmldoxop.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwlhhip.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbmcuye.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2prkkfdhw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2myejzogc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxacwxon.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbchqxp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdkesvd.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvneqbz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkxdffb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2defmepvj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rufjqhrb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wekqerbq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmxxbpq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnaianu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnagfge.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryitetvy.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbhnidp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2erbjafiv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpeoqxf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iojxeqnl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2onmigndj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xntxppbd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2roxzlwei.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlvtbiu.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtuudiu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2yupkcghx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhhfdrk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bthrpywt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeiwybc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqleskw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2evpacmqi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2twvasdca.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2urnvrfci.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuotahjb.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chhmpwfg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoymues.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdhgyzn.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbflkkb.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jifwfarj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mouqcuff.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2klobwruf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ityuyhzv.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdwvihd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhegijz.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2isijrgva.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2axaybveg.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nishluaz.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2klvtfqlt.html


<!-- 参考信息 -->