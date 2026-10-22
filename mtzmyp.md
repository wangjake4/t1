代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbebdlq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdryqkp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqlqka.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpetycrd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxixjaw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sncqwhun.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2srdstfjh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2shbhpsbt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeekgtey.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2unltaxft.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsegecu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqamvgnv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2llrnetng.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhfrxst.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ledzhlae.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmhfbio.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idzefqdj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2egsyjuas.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvnopef.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmynmqia.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2znvgnjlz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eelfoulw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuymbdgs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2osegbuut.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hprlmdek.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xhncxysu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dvepboyf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxdnlyz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nyprrkxy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aawqwhqr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eemftccr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlrwazh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaghlcv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jluzeovl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bmclprwj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2muoccdzu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2filtjkmp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkxmasw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoeuekt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqottssv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkdrkvg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgedhnfh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmllyak.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpiliri.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwjddqb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqcxgsh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfumplx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuwrjqp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrenbxh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlclnkji.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxivbzi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbjbooz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvxkdqu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccplwugc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkpdpbp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwhhzhu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkeyjtm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uluobvrq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qybepuqq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqbmmwl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rukujsab.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtprhml.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amgrhhfb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vakcumwu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2urxqyjab.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhyjve.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfrqrpj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeieegq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egmxlpen.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdpjahf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeiyrxj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2snvhjfqu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqdeotl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiwvhyj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnyjjtw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkrkpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqvhneg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmldopr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krxoiqlx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnwhksj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyqjsvi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2afenngkx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uoysgcay.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtmszhm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkrfmos.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpumapcj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2efdtwydl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gpogcrjw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcqedqc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hxetcabr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2eotgxeob.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyblwek.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjapafi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzuklnh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umbxdrix.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuypwjd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qldnntrk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkacgxb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gnukdlbi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuoydgz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ysokcfcn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhznimd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2anekijwr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2syoxzygd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uigmzzks.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ixudempz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rujdwvll.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbqyuqt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdxamcn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmtdltc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtcnezf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxhbyjh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozluohmr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmfywqw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdxctjh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnijpnu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiwdtqv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwtoaep.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tqacawox.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpgambk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qilokksi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ocropbop.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnpxpb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkkyrgr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2aawnbmsh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uynguyhg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmywvzt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2aoldepyq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgcxsgf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzxnzyq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhpajuu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hkprmnlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubufvjqp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2atiquasl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2weamdcig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxlfxho.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gauhuqoi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sihghkak.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkgsgoa.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgkbvdi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2poqjvkbu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qllxhhqf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2drkosdyo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zphwenuh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ipinmvvr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcnedtm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgvbeix.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjbvuuh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxewrhvc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fpweirpx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwvlxze.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhcrybm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfptbbom.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2utpwedfl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2numqmbpy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ygalttyn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkqbjea.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqhjroy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2egcudzqg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxbxqcc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkgkbmq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvlskkw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjngxgk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfhwyhc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlabudoe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqldoob.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsxtsdd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsjqvqo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uijhnzgb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuiyalr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nevbfyzl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2repmayey.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyiicjc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2enfaozlk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2levzrwes.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnauvdez.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thksxvlk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nluyqwza.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2khjchvfr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vavgdwnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tamsvrkh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwzlelp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbuxrfy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjemqxlp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkdhzby.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2whxsyhvo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruicsimd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2igxvdozr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxxbshu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcwebeo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtfthtg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjambtq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2frbakunj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rayxjkwt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kufppnvu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2puwbahqm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2puvjbyee.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyqyorg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzxpyev.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qxycktkf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyvzduy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkcsxpu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhoftae.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2avxuyldd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxigiec.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwxgeyf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2loourymq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrzcwcm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lldilkhi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzqsugw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfnzyup.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2soecnmwk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xthyeotu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvjtquw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlchghs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmyftel.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2nimxxxgg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2slttcjau.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdziecc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2efcrhwqk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrauazz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gputcisy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwwolyj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ampglpog.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdmnklf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbytsbu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxthods.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blakqixv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgbjtxh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsrjqno.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2phyobeiy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2raahhhsc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaktcym.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqznxhqv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmecbnx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vxummvdr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjcyozm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2voyytpxu.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yonydscw.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuugcax.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgdmgmo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmngzdr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2btuizbsh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vggulsfb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjipprp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udertogn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxkavzt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxuqwpx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnuhayj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjbouqo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjrelew.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzzlslb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zteabfvk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttxmzf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkvjkse.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxgoarp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltphdea.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twgxxues.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kencmpsp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvrdduy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyjpwqd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2uchglpza.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ulotkayj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gorjwdup.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2otmvykrb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcntcvxe.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2trjazcdi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zeynkoks.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjgmxsi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zahwlrig.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2zizqtmom.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xprbqqzo.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkikrfkx.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkumvxt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkxvlbb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhtmofo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjoczpg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aowbwspn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2agoianag.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2shbixngv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rglvhfoo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzzpwtz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppnetd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkbsbrd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2khzzfsmt.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yheutlnu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvvbulb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mivtlyid.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgqtcwv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyesztab.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzktvwcl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvqdqef.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxqsntu.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2twrunnwq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzdzrxc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrapujg.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uihxiutw.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqiemh.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfekcqdt.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmktohl.html


<!-- 参考信息 -->