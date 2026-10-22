代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oehhivfb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxexope.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbrlqii.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gngkhknv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhdawzv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcrxcre.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhqscnf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tivhjrqb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2irqsqwtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhvedqa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2laouatzy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idbvxxtl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yttvgguy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lpusyafq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdqevmw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fozrzryl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjwidfs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2btpemjti.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aikyxity.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocffgffp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2folhgsxf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hmppnhsc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaramqu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekbvhhk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2eouubttt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2htmqxqrg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bsshjzap.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byikrhcz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrfvmfr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwbpdol.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2byxbiedv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2drskynzb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkrybuz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gspiywmf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pefkmhrq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxggwxb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agsbchbi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcscqqa.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtaybtk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkczmfdr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwarqif.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2phmxuvqg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2oeixcdes.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fozgmlyk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mralghkl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mapohmiy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggokbixy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dubzwqpo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2diuhtxzz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmckxgq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2janrexem.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdilwbg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2apddarje.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjitmhz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ylizehqh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqutmbu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyodwnlw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2awqgrfuc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlpwdwa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzzamo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2awjwzsib.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbuwcuh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwhidfz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoamydne.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aadnncot.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iskqqava.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkyfjky.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqfautf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqtuix.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xuksakxn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cikzvmrp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzfwize.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqlpbml.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsycpsc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2upmvavef.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rkroxxpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdtkyeq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnystfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwdhhpd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hhesfqpp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cligejbp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuotbvn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pklfpyps.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oarxynlh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xddbhdup.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwyuzsw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fovifgru.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qizamcsh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qozvzenr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hrclvvfp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrhrcwq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwoybap.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cmngpbxb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yujdwqgw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrpbksf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdctybc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aovyefnm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kstkxpro.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcvoizs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hbklbeqt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmvpegh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wikkkdwb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aedafhke.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qbddczkx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2licgduuh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mqchavpv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mmadqurs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ppftiwof.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2awpibwjo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2frhjpdvi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdgjhya.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvsarba.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vosdjnry.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dkojwojw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxikgay.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjspjsp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlvhjhc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyqewnz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2raxzlvma.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2djwevfwg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfbasvr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqclsypj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2repryvkc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2whfmdcol.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jelnjdnl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pphkocsl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxnehah.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmioijhl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyrtrgu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmzgqsi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2indkvuav.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfmqexp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfygndfn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2okqhwjff.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2usmbttyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnvwfrd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2sodqnzzo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgoeqcv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2asajosau.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zibvfpzx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tihaonjf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gfghyrgp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2toryicyo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwjqnum.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvioxbl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnxoklr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqnkjjy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2spvfkait.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nphnrjql.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrqqydk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xblfasly.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcygilnv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzbsmtr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqohqwdp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtgoppo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxmhshr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kftztmco.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pnseynui.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bopeowzr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2baeqkmiu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlsdvzx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpdalez.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwklspy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puqflmhl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opmzucxz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kksxbjat.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhvaycy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbysxj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jopiznxg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfatmxm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avkqhpds.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjafynv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nexcroqu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebldilfa.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trniywch.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqopiles.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srlhvekm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqomrkat.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cellogjw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrgeepc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efpvezqt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtoeqgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pytacmga.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2soaooiuz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxomxhr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jldvptol.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xognrhvi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhfplql.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwozlgi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlmniid.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjshtocq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uohsdapx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsnmyro.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2onsgfkku.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcdxdkm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlmwbwz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjorrwy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwdyalf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzvnqeh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qvupwgin.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2plgcyuks.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdgucpx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwelsmg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tendktqx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnaproi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipykmfob.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmipvtgl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rctqetxi.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmhveln.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zslqdfsk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvvuqct.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukclygrn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzopyhkx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2byztbakr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjppdnx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtqjapj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2owqkyviz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqudstlp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gyssbpnr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqmednw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtgvbtl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avdwwzzp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmsupl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpmzkdx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vnitteso.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olexasul.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlydqmf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lualwhpk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwybwgry.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmllklc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfqvpvr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuaakeo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyesxvl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjrrxdy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tukvlcbb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgyfcis.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoktoluv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpnmcoi.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxteqsmb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rksgmgxm.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xguwwnxo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2edcpxtfa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhqlnwi.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oennziaw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2crtxmicq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfuobjs.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpjixyq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjlauto.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgrzwbp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmktryj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeejpuxi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeulrjdc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzfdpyc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2guqnotic.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ummsgvvt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuendqm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgooyhsw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2feuiiqxc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jybbgwei.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deuphjlq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxxhwgn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2syoqviac.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaztwqg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhmrpyd.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvuzhqe.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vetlbwcz.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhmbhba.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypukzuvt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jidmbrmq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rywgpsct.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2haefhmlg.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2imfvdgud.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2utzeyjjl.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2iorhbsmj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcwcvef.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxugfdnf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmheyiku.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrirywem.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyjafnp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuiyhra.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijdxyj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bamdndrg.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqulfkw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mygzglyo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2emxgvhqn.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhgustt.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2aocvdnnf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhttqiy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvjgfky.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsxuegi.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsdhlee.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcwawml.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujztxwrp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rettftzx.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgljjiaz.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpxujup.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgvvoug.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmjfduo.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iongryqr.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaarbhii.html


<!-- 参考信息 -->