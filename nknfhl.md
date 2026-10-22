代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgyeqna.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nakkiafy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mibizloo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyxtmvd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqjdsgi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2weyyybpy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vycpxxfa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyoehtm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eusfywwb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2adqjerdu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjdrvtd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jajvnehd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lipyxpyd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hfutyyju.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jolrlsgi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iejzyizd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhtucte.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvndnfqc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjwpmgy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhsamnq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnmxcnu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjynuewx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsaaruz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmuakom.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpnhgpq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtsbecx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rchhzhyd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeywqpd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwlftop.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkfduis.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2limzmhfp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2acxkjlxa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjssolf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgzbtyi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xiztjnup.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nijrtmvv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbobjbg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2feceswfc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdclygx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdbzmet.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cbolfdvd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kiettkde.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcwwiwc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwnuvai.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfxkcxh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2swusmbtt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwhmilp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oihcsuxf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrzgoub.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvhuoqc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjaaiee.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwvxvhz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpfhrnk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzbptbi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tuedfggg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aahdphox.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxtffxk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lazfebvp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxtibqc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiktpnl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjlgctr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2znnsnweo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrrxfzq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pezovzdb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2imbyimcx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbdkpgt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gntzqgeo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2opqdbxcm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezowtdph.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbstpdo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftskkfti.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2itwitcoj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pchkjjdz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjvmsvz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2laffabeh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjsycmr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cvudclcp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfvokum.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgtizhr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlpxycg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xerwmjzr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfqelcg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2etfmelqs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvsawiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqpvwwy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fqybrvik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbqylpz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcytufb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qetziaec.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mpywbctr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2comnuzeh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2katswbme.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhpizuy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyqnsrw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbwjnhb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxeieqs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuuycqc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2obskyjjw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaevcpk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2niuctwes.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwwwxaw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2elyjnfbk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ivujacuh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjukmdr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tftihhha.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzdfwsr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrnnfyh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sspyfdcp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgidkj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbqmkwi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxerxvv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lutsahao.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqsydpd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkwxybu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dkudcpaj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvvcsyr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jnktoqbw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlopzwn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmkbivp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkappyb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vqovwzxs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqgltso.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwzwhli.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaexeak.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qntjlsce.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ossjikrv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ckctkhjg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgwoxzd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvdijtw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyanwqp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoirhzm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yomkuins.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tztpndan.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhzpdtz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jradvram.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bupsnexd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxemsba.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tipfsdpi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhgcdjk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqmospu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kipttuii.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvelvpl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzttrnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2braowsrh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2javiksyd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qceokrdw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpfgegy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cfajhgqd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhdntrl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uziproje.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxpyhpq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gzioiwuw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhqlrp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvuvlpe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pzufnsss.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yywvaxxv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2llmiuctt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2afwuqszv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqalhve.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtezymv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrrrmha.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2prgeebig.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2haqdxlbs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmugswt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaxxudb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrdjstx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hvandaac.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fameidls.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaxodcl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2isewmmdo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxpqfrf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwezxagc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjvmqgv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhdylrq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tijcwsdv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqlemnb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpunfjpl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlclhdu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iydquete.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiysbka.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxvfofc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwfrlgi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sassjnek.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jroqjvms.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcabxdb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owbumfnq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpifxhq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zovfytce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2squkkrzx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqragls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utnpgycl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avepjddu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcaxhcc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsofjom.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqynlalh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvdvlhw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uiduwzfx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlscenz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcgvorh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnztijr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ensivnws.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rajnapzn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydoajcb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuilptjj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcritoaa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqozxejs.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bphgpsjn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwogkgz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2novbcwyc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cruetofd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ihggbcxn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2llxteukd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2llbkztvq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjiwlkk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqmltxh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2buvtwkay.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqbovgx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uspjtmpx.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmupkfz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnqushq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xybvxrkc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjjjbdo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ubleosak.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2kogijbai.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2tknscmga.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwmdnfz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2brqqotgs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2naudvzaa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhukolt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nngooxvx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxtuwxe.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcsuaok.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfiuveb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuxwhel.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bteaidhb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2holtkito.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rodksntb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxircatj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyeflae.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlojroi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2soizpnle.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2klmmxibs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeygduk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjyjjko.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eurtmuvt.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iexijyft.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fttzahym.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wstfhxrw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpkmyjw.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsvevxf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcyocul.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgxvynj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gldjodyc.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2syidscez.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2izkzewsk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2engqwvfa.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnundzc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2avbwtzvl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmbkylr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkkaxcu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjrsdiw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ytddnyyo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgunyxq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiodsgn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krfxawul.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aehjiogf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrumirn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qluczllv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcqfhce.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bovpufta.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqgejfv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crohrgjm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2peoeuznq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhjuzpx.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzluodrp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lprmnhav.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2phslmcyb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbwmjph.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2doyxeznm.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2enktvzia.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfswsudw.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbhwgfb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqvsjpk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfqrzjy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfklxejy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxuykqr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2phqriovf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpkqyhw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcboviyr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuhpnft.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoijnvc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltouyvvp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfphqeo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dxelrkjo.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2owcdpwby.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiuefzl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2libdtfpc.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2desvkxsj.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yloujzna.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzmxwit.html


<!-- 参考信息 -->