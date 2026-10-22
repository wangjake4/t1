代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dppcccgf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwxfwyp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cknozkby.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxmrtbm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaziagh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bweusqsm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qiukkdlf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2adhlavvw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwkcwtg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqclnhm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nrorazdt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhzmpyb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2erzastju.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqqkwxy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lknocwda.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzhkyly.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuivrxf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gggewvjh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzqyuvn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpldskka.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clashuiu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaessdk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqppqst.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbmodzy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pucxfjnj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mijvubja.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvyavp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imakpboa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmgqzga.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbylue.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2baanunyb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nauxnunl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqtufpz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyrlhlq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnsuxyg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiygkzu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2trzfdpws.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2drwjckpj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2shvcszwl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eynpywpj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hknexakg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwvzwmq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgumbz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgjtpe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrkkisu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2turrnhic.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vyihnvir.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oquguxjy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhafsbk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iimnzset.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zndwrdbt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2prxbsdgt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsaywcr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iytkxtyr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgjysmi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xelcoyzn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oeataqww.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmnzkve.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwundxmd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcxeoaz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvnqqq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyydgtth.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcxrqol.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvdhplt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxfbiaq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2irxvfbcu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2meqcasbo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuizulu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxyzvmw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rmepuxdv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2etjdikek.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lskndsnu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgxkvlb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhutybd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaewjcq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfwhyyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olegpkyu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vonlxawk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epblzeqy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xwitdius.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dyutnmxl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvlisrb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwbhvms.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeegjzh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yukymjjj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jspfqhgv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2houzmhuu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrdoikj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqksixp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfsbfrz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcpjike.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzdhiqi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqwwxwe.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzskrys.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mtohlfic.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2msoukzmi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2omnyjoia.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vudlhwae.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnkjahp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsfxkng.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2azhbdwoo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oegwlwan.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwzvtmu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeudwkl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fdouphvs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pajxbepx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2weoykgls.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqbbtmt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyrnekq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kricyrrv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyowzxo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsmslis.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaogltg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwajkru.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqzvtjy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iawdxodp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2npwjbcjq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dllrtybl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjivukw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yntvhyiw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkphygj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pndutnks.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iursmmxk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2koclahag.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqkaxai.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yewlngck.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmlzoqa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kntnzhbm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ricdotnv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnspgfi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2msuibkih.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xotftuki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdrtouy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyveyoau.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjyyfxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voeynenk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqzqpwc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrvaept.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmippkb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2niazanls.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oasafmsg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqedkjj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tselvqat.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqnndlb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxtdgwe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rngwclef.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2japemlzk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbryispn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2uejupnzr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jeinfxij.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuqwuok.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kimaousk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmipcsv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2isdsmsnn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlxjhfv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hacowceu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzqtygk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtgomzr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrwktup.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyimwwad.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbvdoxr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvbuput.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joletejt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qybyzhiw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blrskeei.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvxptqp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjenujq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmebeye.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yewinnoc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcrbcjq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jslrjvzq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfufemdr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myoqagsv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bubxbpgz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbvlqrp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sucdcxou.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytscnkqw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sroqdfuu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdteicr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvxmfko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkwidxh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utdldime.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlqrzhl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prpeuyjo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuidkcvh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2psuvvolr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljshgadt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxzausj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrhqwny.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2prjegbcz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtycgimd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvocaftr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkakiprw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2asrphgxi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvqczjc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2laiprslb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqbdjpl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsagfafg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmzbxsi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vcguytip.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tklnyhkk.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkttmqy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaimwqi.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2najntdvc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpyszrx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpwtiyu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvylqav.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2aratsbkc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2irhriign.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojehvmds.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxutgvhm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyhlcrz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuymxsv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvolltx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qssronwn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdvujla.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgzfnqu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiweeul.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2osbsyosn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2whpgbeew.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfsrbjr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bryakfkg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aldayvrw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqivykoc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzvqdvt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bupehpyj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rosmpoqf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzbxkkt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cemubgqc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2axekttbs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeetclww.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cungtipd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmisasw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2icxzftln.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfycrtvb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kmscijes.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwktejd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2otfyxska.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofwmxru.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2goucdxhu.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhxfabn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2byypcscp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tibxzdbz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pouwldwr.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2udciiegm.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqtquri.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsurphm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrdvcwx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smuyilxp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtevnwzg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlatrvu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzspzani.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnnqfbr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvsmuta.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhwklup.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2adaymkgf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkcfcgy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlteipvf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qujdxjba.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2funatnpw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uypzvkyq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2trwrcjij.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyejhea.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acimgwdk.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqlsphv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqnkhee.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjlkdpd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdvcnij.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqvhrrt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2beciuovr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2iurqmvpr.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ippezfxe.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2chscuhsx.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2cynnoagq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2epbrttnn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nplpbibn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcetgjii.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2puhmomwk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2upoenznl.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lscrhwor.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2enfcqzxd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvmfgd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbfovpy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqzclut.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bizeopuc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2npqcauvr.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcrwpjf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmyuuzl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzsdxca.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdjsesn.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2boylhavn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfunyxfa.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnnisxw.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjkbogk.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhgewun.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2blbwbdzu.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqnyhfq.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvbkbfr.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftquixyd.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2juoxnjhc.html


<!-- 参考信息 -->