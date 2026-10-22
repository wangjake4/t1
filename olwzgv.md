代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cojdzduk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuebjcc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tmorlwxg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpysdcrp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2swjlhfky.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwiwaaa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gubqfauj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2icbrmvkq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhapkzgg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwublgya.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfcktbu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayebymge.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2siivhsdw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnkaadn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2syqdfeii.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2binirpfs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mquyclxb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nohpdvdj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbhpnze.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqaggsz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmdnjvi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xpltutpu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgcyarp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cktyboaf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2satbtpgy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2msfpqyms.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqayqen.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afpsqyxy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmrzbpf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzheedsd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvfeivi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfdkjji.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdsnlxe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbhsnfd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stzinssb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2guqvvixs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xinymoyu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdlmzwk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2anoqplwk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwajek.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmkhxcn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2orxmcsvx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsiszek.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhijgjxt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2crcgmrwh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxpwcmw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgzfqle.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkqxosl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2typoljwv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdscnkb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvgfjpe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cnubzyop.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqszqlld.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cphiysmx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ncirptas.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ddodtgyk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfceeeb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiobpsu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwmiqoa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhnkkql.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mapfxrmx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwvaeeq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2atihtkku.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaorfgk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrfgjmy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tseyhpgw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2saqrdzet.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaaqlez.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cpifxnga.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2riyjncdd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cugjordd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uesuqjgd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqkqqaq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhbpiwl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aevoixfy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjjxmoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2havhigxu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fuazqlpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhigcyyi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2khqxdvnq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdluygd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsndiih.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2outadaxz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvdxvlh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2exxdnwad.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaqyzuq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rctmyrxa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlpqyhc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2spoatxwk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfvwpwo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ljktodlf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbrafxz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrgofmt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ygguveir.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2strmgdln.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmrmggr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2augaoikz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2npxkbrnj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ojknzqii.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmyrdfv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtdnsyf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjfbgki.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2acjmgpwn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfanxrs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhuqzoo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2whxycfus.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlckwqz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrqjien.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzcrmxj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2naaqiacp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2olxtkvzx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqdqtyn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqaibwq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2maofovup.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gytnfsjb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjtidmz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrzkheh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lvioekfh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgrrhob.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fskzajgv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhhqqwk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gvinsqto.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnjcujx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxreoflz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqdinug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sluvmiko.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyhnkko.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2whrnvgks.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nurjisuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkxjvif.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dihidsbw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ajizfgmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acgnwdox.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kofgzlkl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvdkkzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cumnbjaw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiwmqan.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2uysdplcc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jedithng.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tijjhewp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2npijsejy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2twrrlfke.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlmxbok.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdtfpov.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mejutdjx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uynyljns.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzebviw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhljfodn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhjfjox.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fejwugtg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2emopmntb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqimdyvj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2padyvfjm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ksimswyq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjivror.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjipwdp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgcneql.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cthzxmgp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2frqppxii.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfucsffo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyapyjms.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tusjcxsk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gslkpvsx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpxhdlx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfrtdde.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqqjshj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acxxxbzn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kplkwvkv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcsxjja.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzbpod.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjamesma.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hynnamdk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyszaaxa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzzozgf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwvlgqe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juuyfbtw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgyzjmp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeyqzjz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmhzfrr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgohnzlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjydvlcu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgkamzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxkryza.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrajgwis.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeisvvt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbupzswg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdmtqye.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizkohi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzxwzc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xixkqcmf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2llaouyil.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwkefhj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjvqgsi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnacver.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qldmtahj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oornklaz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbjepwn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdmhroz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2udfjkmzp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2izutaobk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gprhrtgr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dccwmoff.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqsqacl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrfxrbt.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsncflml.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnomgwv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsowcsjq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nexftqir.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqxiczq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2coebeleg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjkfpdr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gitqciyc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfhhtcy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjuitlf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwymnrt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2idijbkxe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjmeycp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gryxddps.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2crxnpnma.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzjwvso.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2juwqzydd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udajzbos.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfjsvdi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgoqeqq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbioipu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyngnhbi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyavklw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adxryvmv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxnwxab.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pugqukxp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfzfnri.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuopbus.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2apgfkmaz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldidrgmd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnllwhej.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jekxsclg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvxgcrg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krzvekrs.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwayxgs.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkwvaaw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2txbmbtgq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vadhkywr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tansqqto.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gribdosd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxgjsle.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aepivvem.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2uaadetho.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gneevzfb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwntglpg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfawbih.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2flzjlwfb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxgcdjf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvqkisu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qjveziew.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrwztmi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjraszy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagigocj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfsoauq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmqwxch.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmhppiq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbbkjtr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mknyafsf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bncsuxuv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llnlgknv.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sumtklqh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kieyhzgi.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dngyqsml.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwgvabp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjqhbbv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2winbkvuf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsinzlc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydqgkoy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2zngonhci.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwthkxkq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhpwzoc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufakncws.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjcqpvq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2snikhwnn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzqmzbf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2grobjtsy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2foarnqyz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxlkywf.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnfceef.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpweurmn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfilgby.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bzakrprj.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2naazngel.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lftrdbsw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzwheld.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhokvwpo.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdlbhnm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2incziqxz.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwzoddv.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcnhodh.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyrzbvd.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjakywd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqsvvty.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqwdsdk.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxutbgx.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhhejnt.html


<!-- 参考信息 -->