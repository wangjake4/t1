代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wayghfzs.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2liqhlblv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxtmbhy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2suufuxzr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dogttknj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtucrjal.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgorvta.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeypthw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqoanhj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uavjefxj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qqojnxxn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2phppdbja.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iilecsuh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzyytir.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2niqtxzaf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyidchnc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mybpcpcm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iicflipx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2orcvxddu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvimmdi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxgaaqb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tydzrjti.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnsljut.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbbqiqk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kekmsjaf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pupmagzy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2groaulqr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rotaodqu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yddktnrj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2afysrwvc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lijypvej.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrcxrcu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxvgksb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdpdpad.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zszdfyth.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2shmwanvu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nqecgjof.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhhmxm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmpoehs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbydelmg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hantswaa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eucbjfse.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzlkfjp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxqobiy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbtmvot.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjmasrf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzsxrhx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2htacoypm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqqfwlu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aevwcpvs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2obareciq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2btqorjup.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2occromrg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsyrtwa.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2joyvroda.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2asecntix.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjjkkti.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lazaqoul.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wympkdsc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uytbvybv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sczysayr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fomaxdmu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdcgbbc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwhxzed.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnydggt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiunoot.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaewhkx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxlzzst.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqdkdpi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eomfktgs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2glorvdrg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiymebbf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiajzmr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjkquwr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eosyzbjn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fldngcct.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dojiqckq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnopyob.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbvlhiq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkcfqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcfsnkn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbogzwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2embjihte.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tohrlesw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnnsykm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2awmbfjkp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2amkndrgl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmehjfm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpslrly.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ithigizz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zloeejxs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqjtizf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqjnfav.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkjjlzd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2islntpif.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2opmnhczb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kznpiqrr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ccormdqa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhdrfii.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mngakodm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2trpbufin.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjybxnw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rioqbrci.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wlestwdn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wakiyybr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgsibtn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jcotdhox.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhqrvey.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2czqbwumr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2souzhkvw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ojldjquf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nudmgzif.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2occzytmb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrucowj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmdllyq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oljwndgb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrvflrc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zufcptje.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wbonhmug.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nofahiyl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2atclagfw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xoluwmxm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaohejr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cihejqmk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfzssvq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwhaegp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rjudmrrh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfhjjfj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2yrimprql.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuiiagy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2oujvowwu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgflwap.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyyrmoe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgdyuwl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzhxadx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2anjphkwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdqzcuc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2soeeepwt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fajgestk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mirlwods.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyycxgq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbsmvgx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wuucbgug.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqdabvh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgoskes.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoyksyp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjjaqcl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbchfds.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2knduaajo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2asaeeizi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkrcvkv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwhblwt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ohadodsc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqniqvd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2znncnbrl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvycbasd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rntmovgo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsppwdtf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtdrnys.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2uuatjxts.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyztoqo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2npayjtgx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rqszmuhz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgpegwn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjfhtds.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcffeez.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwombbek.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvdpkyc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clbwgrsv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edzlfyml.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuqvzus.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uysfxyzf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzhmrob.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqxiubk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiffdlun.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igeweaqo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpfrvka.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhatahh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dobpdshe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mngigetr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqioemj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiouohr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxamngg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2deijxcsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqtlqlg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdumtul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2popqypvx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etqtccgw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdbdbkn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrxpdba.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtqusyx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2frhqqwqy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mijxzmpn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qchronwf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrszvgyj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvdaafz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxvzhpx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rultrymu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlajbnb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfupyfuv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2huquwlwn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwsyjqq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqjtenn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoyqzgu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2avnooopr.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eappwelc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2bglahggh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvdnabf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2owfluxvr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqwluxq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dicpbkvv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjqvxke.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuiujdk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkunjydz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyfbmni.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2drcnqhpi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzbnllt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqarlpn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkmokpr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvvvksq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vywxgfnf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvlraja.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gamivglt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ozexqthz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2smfouyiw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xixydprs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2latzesmo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdogfmwd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxbmnxc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaygxik.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrlemgx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eikhgfby.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvpchcr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pusblxua.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxzxbzu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdsmhjn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnhukta.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgckezyq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2crfrccnm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qnesgcyn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuookpr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvvzjrq.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvrjxtg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptbuuxi.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kblxlnzm.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnrhdvr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgqimkp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrddbek.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkwyydl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfduysfd.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nszdklum.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtcnucu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgbbdtl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2drizkbjv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2okjlqzht.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwzvxgr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvvbbaa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nlydotek.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbblbbj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sspohktb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duevsrvv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmvbbvg.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiwrrwx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcygmlq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukowynr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2hirjhflt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2brljjmvg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omooxqqo.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqixiaxu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbarwdr.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcsrecs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2htnixfxk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxaxxum.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsviyei.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mupkodwt.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2blzzuxsa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2sattxbtt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2djvqmbsg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uchsczmf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjgbedi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqxhukj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hedfbevr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2imwblejy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ronhvzbe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cexiwywn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkepoih.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oeizvuwd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gusmdoie.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oynogxek.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhuxriz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlcyqbh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmmducl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgetvtzi.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2naxjyujb.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gutbqavh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdawizia.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlidxgr.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbentyob.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hltpgglr.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrapnwh.html


<!-- 参考信息 -->