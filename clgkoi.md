代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2whbxpzmk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lutfzzrx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjcaadr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkzcqyd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qisxzdqv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkytdme.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2alrxgsef.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlawetjh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojevyggz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyugxzo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvprgxm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummwlbll.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2utkhvkaz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dexocpkw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhhvoyr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiheidi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nwysbwrc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jggaenna.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgxsiee.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiumarpo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iowjyrrw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sqawbxmd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdillybd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwchdqik.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zvviluci.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zonujvtg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vippemwq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pudzbdpi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnqyhqy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhijjwvq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzkospf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yriuhbvm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbeqpvf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tveqiwhu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfojhfi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmjfyig.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2peobnhqu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxohufce.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvcqbgr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhqkkjl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ihznbpon.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2spubznfw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zctcsbzd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhxiyjg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xewpqann.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2neqyilan.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abrcufcw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2deipcsao.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jamrygmu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwmnrnv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjtbetn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2whxrajwb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdnncda.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqmfoiz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eednlryh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsicwmq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoqbosm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2svvgdrjv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnjolsk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2szlnphir.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqwswbk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxysxif.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krbeeykl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icizfgxy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fwydebnz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhpprhk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfflddl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoycdub.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwflviu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqcdaay.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgufroc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqreejt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlnsdus.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jswjiecf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhjzhea.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gktffxmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpzffed.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kecacqki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unwnymiu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrxirms.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gljduddd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnrhgbt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkgghmh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jchclivj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbihfjs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qasekdjr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqzldql.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2irseczbx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrrnpne.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwiigtf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iafcmywy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzfyqgr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rfinmvtq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrqhlif.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxavvno.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2awzsorio.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2euxmzgmj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2thalkkye.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuxoetu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqcyipt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eucsrlsq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cquipxjv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfoeynu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrerfqx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2amnsnlxz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihzjtd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2giwvzqqf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jpukalvc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zaisxwii.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwanpuo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhykwt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iubjmqyh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2efrbngsn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qisfvdag.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bavfbufk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hexqwolh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjnmapn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbpqczx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2igmauhgv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2abjtxrii.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmnlstf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lagnzqsi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2whwliotk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2atdnojlx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zgejvyih.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjhupsn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbijcnzt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahidlpvr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dreqccix.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2otuxsbae.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2smcekfiq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2demkzofq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gikcsxsb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfwvgqj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wjohroxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etkbgjqn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bttqvzct.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2geeyazcl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bugjadqf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iaebnbun.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwlqonp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kcamsdqe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lmepphgl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tjldqchb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hcietvwi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrfsbvu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdsejak.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kooglnke.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzekyuh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qiakcevh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rcstdtph.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2laftakdo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2snwjntro.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynggbtha.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsjyakc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2byopyomn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdfzmci.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vktfknrs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gltvqbfq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrxsagq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvltjopc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vimwpvys.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdjmffd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdengkem.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2frdixlgx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwhpgtp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmmjshv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxccavoa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiylqkn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwetbygr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aimqdwhe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgpayiw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcglqqs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoswkxz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhokgrg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzievdqn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slilvvqg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zinrblbd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaxnkad.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumlqqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjzchmj.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilscggkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvwitxn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwzetfj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2indbbmsj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqslgbee.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzkdeld.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jljnshdq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpchteqo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2omupojxl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wipodbry.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmjduuy.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wekdpmct.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbqbnjz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzetxaf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2arwxovyh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2muxcgfiz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnqelda.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jejpogqv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2etnzqdzf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2svshcmbh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bursrdqu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wpknpofv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqafwel.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaznwzh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkocneol.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgkteco.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2euahltyl.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dahlcvde.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjkwwzk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hezqwhwt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zovvydrl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxygwxqy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuxbagy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jscccudu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdeampw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzfsjpi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyasxtg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lywaitek.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgtsgem.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2svmquxao.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2joyrindw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2isftrdea.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzvpfzn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egdtpcat.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afaxdbrq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqsjdsy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqzmvye.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xhatekca.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2horbzxmo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhmyqyk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrnqvqs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrihprr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jebevkpo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcrmlhb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2iliodlkn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2piytxaqx.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aoomghaz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2glcgvjsq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnjokkd.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqifytg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2downtpzd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhrwidz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxnxdug.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2awchbdhj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoifmrw.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2npizslhx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgyxfay.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bylwzfbe.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebaypwy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2crmimujs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqgeowa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2krqusdag.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsorgdd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzxglcv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2smstmldn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llsfjybd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hshvopbk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwcrwnz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fubxhxff.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqopnsq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmmktaw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnubdjo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trajzfud.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxxyrvx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhebnc.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdunvalo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2afqywpil.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aeccopmv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmfiaid.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2sofunjjq.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmlqyuw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdwmaah.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxlwqnh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsxhvym.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2objprkqs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nshgzacm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iauapvui.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aquowqmo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtilrdc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2frsxassa.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2motaepzj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsgflbr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiikgoi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolwqdkc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2nvggvzrk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2prvsaeyh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiosazsq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkayevln.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dabdsvzz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooikoucf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvfinxb.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmrvmql.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbonldvn.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlwewyc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqcijzt.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fctiqfpq.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2evutcxli.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aakezwim.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2djklsmoy.html


<!-- 参考信息 -->