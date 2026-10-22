代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdjsodo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgrhdbx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uzalleey.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2slshskae.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqslagw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2krajbqrt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yguhqohf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2radrnrri.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2blerugnb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqolpxi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pducocdt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2awhzdwag.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjutdu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxcygec.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuphqeo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgtywpx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nkicqhas.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjdusex.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2deyrhora.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxetllol.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2luwraagu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2btufcixj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xedzwxdx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2axqetjmi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsjusln.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbyzzio.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzhfdsx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmjxvay.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tioyckmk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2amjolcpy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeaqaay.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcygdmu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2akrcnnrf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2exdvvdlu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjwhdmu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ktybqpik.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwamqer.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpjkarc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaqbsmh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2izreiloy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rznfggfb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bksyowor.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjiedet.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbgzhfp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxfvij.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2twhxpijf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xihqbybl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tucqzogq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeydjtt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cecgrvjo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmkobpy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eoveqqre.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fthvjaxu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgnvetc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2abuplrar.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qaazpepr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jndkaeyp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojxgwtv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ogosugxg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpyxgxx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rniznagm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtktrge.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpawfpq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2okkuimkk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpvlukh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoznhmi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnmlvmn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzhywal.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2trlcjqqu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgknnbhu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsgfrmh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkextid.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kacyabme.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xfakxshq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2febdgtow.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvrwhwg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sznctbhu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gwglhrsz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtwqwgq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2etmlpuvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwyuess.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdjatkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giocrsrb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvoafxh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgbzvru.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwxwvxe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxmket.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwwlfhg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlfbttm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsewkmu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2accwumwa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2widgfbpc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyrsfvf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dpruxuth.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vulpnshe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxvajne.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxowias.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxnkuqb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgkhfyl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nimkbeia.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjoznwf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2trrihpks.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmqhzds.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgplsbd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzlckbq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tjysjuqs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsxhfgt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2djqgmfnw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lznqvddn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzezvlw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hefclaus.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ieilwcoe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqixhox.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2turkjxct.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dswixbve.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbhhnw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kudcrivl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yikfcing.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lkteezzv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkzvuuu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2babtjtlj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sgejkhaj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaupkfo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbrimkq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvobugt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ftymgzwb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpxbmxh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwctbnky.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsvmaea.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2otuibcwf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsbkbgu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nexiiiit.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmtpuew.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzssdcxp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2txqkzctv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiznplc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyiuzig.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mupikuur.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcaqzcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaeaefo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdayruy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrexewq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2chxwbrna.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvbcgvx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdrmsna.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fsweiian.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2newckxym.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgpllnr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cbafbalm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2soonczjw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgugkxw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gaccpsro.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wbecgswk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcdudqc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfebhcyf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2obiaufpw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2epiyaniz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wapwyxlk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzmggyt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkhlcgc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgjvtmp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzmqjci.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwirmxm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxaqgjt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edlhztcp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sohmcqgs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pazibkxh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lngrdnmj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbharqn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lycoryoy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agffmqra.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flifytre.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2loajzjaa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmukxxul.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2voeasonr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqptwirs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkpfcgg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayltajht.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmlfxpc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cavbbygm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2haspcmfq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwfmjdj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtipukag.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpzwqdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiylaxb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdbmtha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bibkislu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuiltiq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2euidjetb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcggswfe.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxcbbaz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyflggbd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeesmwz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjxtntu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhpijta.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ombrfgny.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2inisymrb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2txxotyup.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnffzby.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iprngdfx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwekkbh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpicnlih.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsekowb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnsxbvn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqctwih.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcwurgs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwpwuge.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbemrpco.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzlqdow.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuoqkwr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2majpyatu.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yulgtxgl.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrddfxc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxarmxvj.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2veobucpo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsnpdss.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghiptqmw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjksakk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiuqhnp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2czhxxhcm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnzkuy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2conetzai.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zttmjahy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbsuxsd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2asimiqlb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqayysnz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxapiid.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kukjjbak.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bburiueo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiyaynf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oowjkadt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hpntxoft.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwrnvvq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfldgov.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2twcjkpnt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcnvngg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqnnqao.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyywozah.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2drajxcev.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2nviudbmn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgcylcv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvrjeme.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2stnmhnxm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyvlcxw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmiyhua.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkutggqy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqeuyyi.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixghvlr.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tmreixpc.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpwxrfy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zlolkjjl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivqhmvj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouckhcno.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjcfnyr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlhyize.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uylzgzxd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjvwopj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqicsek.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2opbkhrpz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2csyqyobz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbvdtjq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeoydai.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyagvpv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwoqgkk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcqnrwr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2vjssbdaw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfolusr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwarikcm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dntmnwqb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwuesnv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasbbryg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lftmafow.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wagtlrwf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojblqsnw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2auceyfjm.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiibjov.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhupxnk.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqdlcuu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmamimex.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuupdea.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2paomemdz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvchvau.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgsrejd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwllqsg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lftyngfj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjqgfng.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjtkrqo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjictvlu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiuiwph.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2etwcoqky.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2etsadvbl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wamqcnir.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpetycjt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2anbkysem.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfctpka.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2whweswtg.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdhkhhy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnufxue.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpoayvv.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2haouxtbd.html


<!-- 参考信息 -->