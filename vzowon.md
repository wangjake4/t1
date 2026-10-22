代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbfoshk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjrwcdj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxfziga.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsawgqfv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kcesiisd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eoniaqsw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktswqknr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wugkeyqr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uszzspik.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfrsyke.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lrefaoqz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfgugom.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyufatqa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxhcgiu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrfxtwf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2upgccsvr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuilavt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcoccsg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gngupitd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwobfnfs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbckkcv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfgaczb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hamtztvx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afifffyp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrjysyr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eibuaucb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjdvygn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvollew.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ymneikjj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkdcmrc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2igjdddan.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjfwjxt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvwjccj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2upgkmuuh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tltiqsxu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjubcqgk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wohoeiul.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zvllckia.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fkujddtc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmligots.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqvhisk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvxuyzm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fctstnde.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kegemqwe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zadcvboz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsvtjka.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpzzfsl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xflsiuyv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlcpukb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnviwqu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxobdlhp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfmekoy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xyohwgcs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2addksfgl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ercbmjvt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhgfjzv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmrwbyf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbiszv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wihmaofi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuotgrm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ruilwrym.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmumwfp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzbcgwn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nupqknht.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2whsijjxh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyzkqbf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxysdkk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkutsejx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tacfcapw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwmuzjx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcinrvqp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxibiic.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2magstdhn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnywsai.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2egbtfrxv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhnrspv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pckjesgu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qvphllfo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2siomahuz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kagzfvdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omqsagsi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mplbgamb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnzjdjl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuzeupy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2epkytcyk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2loprkyqv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kchevvho.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgshdvx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xjymtgkc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2etweeell.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbgdqpz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2icmopghq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmtfaxb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtznjej.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2srsitnnv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhglumg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrlkvne.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tswspjme.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoayavy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2blfrhohr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsbmzio.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tndajepe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpliva.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqaxjzt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvdpjet.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rrykmcub.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bqocvscu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2itkjsfqd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eosukpwd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mecvdesi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gfarsrsq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrvfovl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yenjramz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xltsgijb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtsytwa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqueoxb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bfubwhua.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzmaqqu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbzzxck.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihknac.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2muwjgyuz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2riodgetj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkjfowl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gqamzqzb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpzmfme.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2psrhlddn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lddhkapk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nypocpeh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyumhiq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgbzhcd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfftbkc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uimvnpuw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2pknxltzg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fadqeker.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbtlbch.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnierki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbksexl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpljjry.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfopekk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbydsbg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqvksqh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vatrjwyv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsbvthd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jrixuyuu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2erffrkdl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ksexcozn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fsymhmtd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfhaxcb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaapzju.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlgktpj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2usldtvhg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rngmkspm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdixblz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2foqbueby.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gguldydz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcqqqnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcipkzpy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2duyrzpcf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2khcyrkzi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqaijrr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwidwyun.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fgezwekk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sblnlphq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpocuqw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyphdotb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2linnyxyl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwscvdp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epoegviq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2regcobtr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrqsfif.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntraeywp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoobxbs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnunehmi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llabpwgx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pisdkdgr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpxkxln.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luevhdxz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzfmdfb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tszvuuqr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyihzrad.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlsrcri.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2apgstscv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmgtole.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbjjakt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdttmgio.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zafratsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gicpgfad.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsupyglb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkyzsep.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iayoirth.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqidqea.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvdwwqk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqfziuq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfemauhf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cledfnbc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcrfyqt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwdgbjm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkeivwx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpoysyb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeimdiue.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaxpyjn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjzcdem.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpywbdc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2acdamxts.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpzmyuj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpjbuub.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fekqcvou.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzrfaze.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gllwgefi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcclxcp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvuwhbq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vqccynyq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gktuazch.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2urnszwvl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mamicbmv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvdrobx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmjviat.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxjxppv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2emslmsll.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gnskzoei.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2boysqaop.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2auogixqj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2whxlbsyq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2dsajqbiw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whsakosw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scffbmgb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hidkiqiy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuurnlf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdbiftf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsenjsn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbzngkq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvtfnoe.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yecbzsxb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpwhqyw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvocpxw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jltuookn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2swyyolua.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zicmtaxg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbvlchn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbarczb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjojixj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyrdlgb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhztbfc.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqyucgt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yowyouyb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2potvnjrw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwvitwq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxotqgr.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjtdkor.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2grdnhoyt.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkjbwyt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsssojld.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsdozgu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltzhxzk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fruqjbrv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbylqee.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxilchz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2wivjzxrk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmjanlk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgroqbua.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmxqsc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btclqfmi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2trczgrhg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlvkzxi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjxkypj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzveja.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2llufcwve.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwnfray.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkykqkfn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nabxssba.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhmcyuz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2prawazqf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhckrgc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgafiifi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuenckx.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmoaenc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmyvbva.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmqubnr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhemohuy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vggqkppa.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zojewyiv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitnsgp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgqdvjc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yhczwgit.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdodiqu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuugfelc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbumssb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcodswoe.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmbiypo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfpesyh.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2icnqcnon.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxybnwck.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uogtwrxh.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fygqawmp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wncukmas.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgilqyo.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkodzxow.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2elmcrkbo.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdfwcta.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kokrvogw.html


<!-- 参考信息 -->