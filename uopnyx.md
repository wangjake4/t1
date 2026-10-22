代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvyfuig.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jxodqjsi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yecengoi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dqearwsr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeehdpr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkeyago.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gmemeufj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqaloio.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2szbhzevb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lssjtlvl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsucsjj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrbleas.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fmptofzk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dnilhfvd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbpenqk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2eixninqz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qepwobum.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqslztbo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiypzvp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2krlqupgm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgmjdou.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcpfhll.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtlgowl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2memigtvu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvydill.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2riwztmrh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xecmxmru.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2blthwxml.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyzwofc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoypksv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2coavwavg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeiridw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2daskncia.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaybxwd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gswwasuj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqleqphe.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bqugztzt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcoequr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jokqegxl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aosgggif.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ljggbwye.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xvykqbjc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtvkhuz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhqoddo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbklfbz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjprnwoh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2szihbowe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjaklld.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2elrrgbyg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiisrpao.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sdedravl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fizharle.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gatfrqll.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uiayxopw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2arptaugi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzxtizi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2howjxzir.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoweqec.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tawzsrma.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ujydqopq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dobmdahg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsxnwsr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gstmgsvf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oewgmjld.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjsiymn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjazwbnr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbialst.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeedkbp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mpckszey.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cintckco.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfimdna.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdoxabe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mualudbu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uymdahik.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2krwkcoan.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hofodcxr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxtjsoh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjumfhr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2atitpwvg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2thfffbwz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yrriqjqb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgojuku.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpnfsnl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hanlrwgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdwecrv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zuntugke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxghxqp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rmydbopt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bspvkssi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvlhimt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2duatjtcz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pznmvkuo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpiaedd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oijotulp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mpttiutl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2htxjquzf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfhiano.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmvjtar.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnhcpyk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrgctkf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2brkhryfb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzgkmop.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gaprmgch.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rwldhlal.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfwnzwr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jammqiln.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwyopby.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mfidhfjc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jsivaxjw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2brclnxhj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcdjmgn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrzsxxw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmvmswd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cztjpjmh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lafqslkd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtglbke.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2udmlfpgk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfefgci.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrvilrt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnwvude.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpwjbbo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qferbjgu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2egtthcdd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlvusll.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sysruzby.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlcqwrb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcpjyvi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtbuafp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2crdqoikh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcookth.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wgghtrkh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ztquznlm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uafdycxy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tujmjcky.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgqdxef.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtftzfj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2pctpnlqw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbckxvr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsicggw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaxawyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuikitex.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkeuxmh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cavmylxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dywevvxd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bhttkyqo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bovrbtyl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hcosbjax.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bborigwv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqoowgl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfdjjk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzqgrb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldnkll.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cmguleiw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaommtt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rygpalql.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2sumlxehj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvdjosk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaifnfs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdegqsy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhqlisk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvngpiob.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iygxvurf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2brjktxyv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkqdkxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2abvmwdpk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxdtimv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnkjgpm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fprecfpu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrxnaml.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aldhgebf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyseils.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sshrhgto.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgapuzis.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxuulqp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nthxpfmh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbccnoet.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgwghpg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdnqiuw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgprvkpu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrbjecf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbcxhkc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xksuafwe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fujsnnjh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dncwtggh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qazenpsb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2maamqozz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxrtbac.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzgxfdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhwpsvv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djzcxhic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvnbnkr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdfvnea.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxuiixa.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uegaojru.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vocwchiz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeplmgrs.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdixdqx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrssdub.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtfasji.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpfsjbl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmhlzkf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2snyoczrq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaovijmy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffphgmiq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2riquptea.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2diztbvxa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdtemrt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgwodwt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qorwyowv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnigqxq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zeswxcfr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2getbpxhh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxudctn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsfjpbb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoahopl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vodouhop.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2haktuqgx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lclxwjnz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbbhefw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pauqapfc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oigqsznh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ldovnklm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2arasahpt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2amtuourg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmakshg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2crzlfdvj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jblylsua.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhyetos.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkvbntt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfcohgc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgqqchm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2shotupeh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2newixwxq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbihhek.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqibswp.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csawacrp.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gqskpycf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkxeduy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwysbsc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdsszib.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvxmoxc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xueloghy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqriuvv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdpejmp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iklulmrt.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2esvctlan.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgsdvgm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxobklhr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdmaonc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2noroxnrf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatardk.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssodigez.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mqofptea.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yopedwxp.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xuebjtcm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2toranmth.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2naywdvcx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnmczhl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjteejb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2waloujll.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbrvzaq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2grevbsni.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2inepotnl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dufmoktb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpmqljl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2roliowea.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prmymprx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxflgxz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhmtaus.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmdzfln.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsgkwaw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2artqxlow.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzbfrnp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwrmlpo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2tecajifv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubopjfhm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dygjkqhv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oznsyqka.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnyvyvz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gffwrlqd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxbjoet.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ondrfyrp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumtpre.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlwxcgs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtwrseh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2shzgfswa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtdssmw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kennuqme.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvyszyz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmvrqyu.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpeisto.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2saphnolm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkzejcv.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbhpwyg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2trxbolim.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hykppvjy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjgztpd.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2urtfkdbt.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgsshkl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzvsswg.html


<!-- 参考信息 -->