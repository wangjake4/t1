代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxdtuoz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ebszindb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fetuuxhh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhfjraa.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lljsktda.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2skugwaym.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoicgwy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngtdmcp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2htrbnazi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hndrefbx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dexcigzs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaztvms.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2edflmagl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtajatq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2owybvpni.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjvsypy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krkpcxpw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jagykvmn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fymteouk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zypoxqvm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuxfpib.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kbndgqin.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzlzibf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pptglxnj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuardtc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xygsngtu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgejstu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2furymxpm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvydgfy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2popynyfg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfekwqt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2damhtftq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxhzcav.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnypyws.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwxdulm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ummghfjr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqdglpy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxmzemo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2liqaytio.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwojydg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lfimqnsz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzrmaot.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yzurzpxm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrsxdda.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjdgrsu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzpiqzc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jktphiuk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhsbihj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfxdmuj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijdtjjs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcxcita.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rfewgcuy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsprcht.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnazkahv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtszhjf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mphjkqyc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xifvjqkp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfkcsax.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoraexx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vylfmoqt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lzavbnad.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbagpip.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjdilat.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnywzab.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ouupnclz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2muqufcjc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zosarzzr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jiubprxm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qihbwwbg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmrwrlp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmlbqve.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2twkjkzdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbkayoz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tjapehtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvldputv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2suuzvnuq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2naqywalt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2plixdfnx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mkalcnci.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozywurmh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dwccowml.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osvekguj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsvqnsn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqhzcyh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2woyrwvse.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqwqwzv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhzgvug.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrjumt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvqfqjy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sqchnsol.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2szkpwkpg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sflrkcee.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdyuhvj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zyokrwhi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpoojya.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bioifpgb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uowwaydx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiobbbp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvhwsud.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yephmegq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmdutfp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmuitos.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hzniwqhc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oikfsuac.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jovuxitn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tiegklua.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkrskvd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxryagf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dwessdmn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bokgonky.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlsmyxo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lueqskup.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yentmpwj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2syluovwb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhynctt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2smmsvbvp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyvfmeu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2shsxfizi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnivchqq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxdrmst.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zspokxha.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vggzuyre.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlijrzu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pywsqdho.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cszjbtmg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2iniqhcdx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgsfzcs.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjrrhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hthqvdxy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zstxxdxa.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2trzxmtsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cukekrkc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2epkscref.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjkylhy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lszyekvi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnaoeol.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2isuayiqr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdpaslg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iblndjtl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tprhxzoa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tumugecn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2plwmjvmz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zadleric.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jabzkawv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvclxllc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuxhaat.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbefdds.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzymaxh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2trtdywys.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jklhystn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fflcohwr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lggacamu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdcavnn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjbrpmb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkggaks.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvqjran.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2biwwylwy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puiiiiwx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnizjmzy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbbyfxk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvzbckw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buokpwpu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqutxyf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skfcckbx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbysogc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmhaqai.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwprygz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idqvrvcx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aafoewkf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntejnisy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxobbdf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbycpegy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnshkrr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cledykou.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyjqxvq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvxplqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efxgwgao.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nciodvtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iedtdcei.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djbuxizq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkjzjwn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iheaqpwt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2alechngb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mohbqscc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjqxqtw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhfmjrr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmojkzji.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zestdgrc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pswqmtfj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjjrypy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtinvwqj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaryowl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2osomvyps.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2marpibnt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwfvwxy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxmwir.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvpiuqj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsetnbh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ophbbqgb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyjzaah.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqckzzy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzstvrgt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utuxxdgf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrjppzw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hlblougs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjircwdb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jffqsgax.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfccryaq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiehfip.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2iypqgmat.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jknkolbc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjzwkgj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeksuzgw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rofcjrym.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2btbujeny.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdaxrip.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sasdwkoj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwshdaa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbazssq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wekksvpw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ceygutka.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllhfen.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aklqvfpe.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oogcbjnu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzmgrmh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xffhuivk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmcyhvo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzustbfx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lscsgbqx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sklgzfvz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2orkxipqs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2eybmkjmo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2adikcegm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbltbrs.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfcqfyj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtyytyf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuiglxp.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qabplpnx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqayuhps.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2osnlqqvv.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2odpwswvg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2drwvghvm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2agzntcjt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdwglnp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutpzdxl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqhmagc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vccbjyhh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuehkiv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgdkptk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gqksskuf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvmxcnn.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qomeakcx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuhltml.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hibaqopl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbeyncq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmnctam.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugsdndw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcnicwk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ealjozvl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdlrdaz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wygbvgje.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsossape.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2qggeunfy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2raqmzeqd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyboits.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gphlssal.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2aiikidto.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2isumndio.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2awkzapoi.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwzuqrh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aukubryd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxgnvqc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrbzcgh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2anbvtduq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgtmpms.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ceisgyjh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiqhzth.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dukxfgyv.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgzyfjc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvthcqlu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bozvnspg.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2opiegwgm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2queqjtxf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlypozqm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pamhpnse.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbppdlp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2znfivpcj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnmcmnx.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdajxsp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2biqlzgiv.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tygaoqge.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxemajor.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtbgxzb.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zixlpvpm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdshaqyg.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zihepqhg.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdidlqn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkxaoat.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zbidwviy.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hejnjaan.html


<!-- 参考信息 -->