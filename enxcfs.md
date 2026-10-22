代发 wailian999

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qipjegqb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bqifcffo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkcmkgs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2icymtzwu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjezwpe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2aguigiid.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiihgnf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkixiluz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lhltzcxp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eeulyqae.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xawsqeon.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxarpoib.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcaeapv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoqfary.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtaldtm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlquoxq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kyohahib.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqumxeck.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqmnkff.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2grlroozj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2spjuhfdp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mymzmglx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2spezgvxd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwwttkh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtvxaul.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2avhngcyf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxpnjzh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2panbdqly.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2serepsfx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixshoqos.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoadsaf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxtcydh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuaizdo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2suvsnghj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkdjlda.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfudqqon.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kodyytwu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gphthlkr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2huwtbhtq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtxdyyd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzoxdzc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxxkste.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeptwfz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2psazcpyc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wytzxqjk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2prrxttud.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjolhrz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaupsghe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lcttqwpw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgbeykz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sasyrgwr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfybjza.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hbifemvb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvjfjqf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxlefdk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tucmmblp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ipacxzij.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eafaqbzn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pquoirbs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdwbakj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2obkwbfpo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sezclgvb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfvrhut.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tqchadve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcopputp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uuibrnmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnrbqmj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxcmgbw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyfpcdl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqocohk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xppxnqoy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urzydgcr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2npnmjgys.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cntrybzt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpfsayh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrrmlsx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuzgpaf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgikmhj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jitgrxbk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrnvptb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tsikwlyz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2psxztzdr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cwticpia.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2epniygif.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrvbhij.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mexrjxwe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2efocbecb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qefuobem.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2raxlbxae.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2buezvrqb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxmtpgz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2juxktfwi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxspxvn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbakcfn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbtzqrq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qzohqcrp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqerxvh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpuzpzq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcqdwcm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmibdam.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrcofte.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tgumidxp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2slmgzbil.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2llzhgxsd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bzioutgq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nxalkdjr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhyhkcp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bljgumwh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qahsyehg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bjngilxh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vgssnuzt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2goubtwxk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqsawnc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2spvzgjqj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sexfjgcs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uswpzdrr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuofzru.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsvpgnd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtzsqmp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rntbxlrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omfqbvwg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzthawu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bryqshfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxupdrld.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsfvugm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yduqlzvn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxaglak.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eadjinzm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsjirrt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbjkekk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwvjpdm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jyikhhhv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiorcab.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qspbpinh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2teqehvqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsdkdre.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqszalv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2adtygodi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhhwqyt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdqohzv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nyprgwvk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pzymjbxu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2utjtdwdk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxutrfyf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zeynumwc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfgutlj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyufwmd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iecvjumg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mggqajbd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xidptkna.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evjxflbd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfkayyf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2loipmhbh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twojpytb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdujsgdl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gypxlhws.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpxdqud.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwpezeo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvictwdx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlgvbpx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyzqqwn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sarnouiv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyqqlxl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekueutln.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2snvosuth.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bultqglf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2huciznkd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlldtrew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgllbomg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvorvwne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbgyiyz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnbhgwz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2svikeksv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxtldti.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzisweb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbxdezi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2huvjievz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rflaiyng.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaxmyax.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mejfzizp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2hijwwrzr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvwgtfq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctzfypd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlnrvci.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfimwsyp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqfmkgd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjkrmlu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bexbwokx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpstrkpu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuqgoek.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmaqshj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2szdlgjxc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mldzxppu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkknbtgo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsjgyoj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfzvzbc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqnsbcv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exddawgs.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owrobjsp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdwxdet.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfbkpyl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfwyxno.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ebidlqqt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fslrknvn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxsqphy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jclaahfg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2enxnmjjs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rhipyiht.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxvwgtn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opumpksa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvscnzar.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdkmtks.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sapixvbb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrnvkrc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoetudt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjxcdtt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqtuqyd.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsuvpwv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzingtrt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwrbzee.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqildgwa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkrgxzh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2trezpwlu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvcugui.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejncinpn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaijare.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjhonoy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkxhnwi.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxyglfp.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiyozux.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuwtryy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vssuarlt.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2qbejdboh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpodmjfs.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2fvytqsog.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiwhfkw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drtxzjtl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcunnkm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfslwavz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgrrgxi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlkmosl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfowyfc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2plludzzm.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxzipeh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwyvyyi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgnnrms.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnnbdaf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csuqbicj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsffdkug.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzfllld.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2otdcwebd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvvbqdt.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuhshqr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjculubf.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzkvlvq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqapash.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dymvwqut.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvujwjeg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2edlmvniz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcvfeew.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivusdsh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwertiv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fexxiuif.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsyzwxk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyobupf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbzqex.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbqpdjj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2emfcmnmv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpxqvgs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjxbkvo.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqllfxxc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fftpzqbh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovllbmb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uytvfuyf.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtxlmbq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlantjxn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgfvty.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tevfqlhr.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgurrjpo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2owbzaocd.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ribcunwy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2foqmfffk.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjwmhys.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dupydsjw.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrgvpnf.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2baquwuqt.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtutbym.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqhklzo.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eafndlnz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsezjrw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2viqtchus.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ldysfqkw.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuagsgj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnzyaia.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpyuzqc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyodheb.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzqwvtb.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdbovxe.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2afyuvvow.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsojzbot.html


<!-- 参考信息 -->