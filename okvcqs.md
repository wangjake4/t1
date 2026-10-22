代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtybgvr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bolkwvcq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlrfkrx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdgewpp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjepequ.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfgxgpz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzdqlge.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tydfshru.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsupzfqf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvbqgcg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgfeart.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2suicwnou.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2turblopl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfmgjj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsemvvld.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdxcuvy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuisnhx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2encfbwdd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvnzwg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwwtamu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aoojbccm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdhmwuo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fnckkgjj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqykzcx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iywboapb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jymcepdt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcpuokf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fngysxhn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqipltks.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2owxsackc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2trhmfprc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qggjmbrf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iuprhnfh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlebyoxy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nakuhviq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfihjgq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zmebprqp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlmrjw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2syefymsv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfzqbmf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsmgkxn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttuwrpb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfprbph.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnkwlpo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gieeeciw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkdtqjq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gkexgdsq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2souctxgb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlymvzl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2psgnkpao.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyjbfxh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eumfkyhv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ijywdnba.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmsvmdt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esptohme.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxxmbza.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lztpduom.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2myteqvpz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2auoptauh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uciohugk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zebkoabh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aaipaagc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjxvmwj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2toqzguoo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2evbycvbo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qrftdsez.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnnkzoc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2krzaphbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsbaxxz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jwygjmtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjqugrx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwgjqbh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwzimdx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2haepopwk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gatuifal.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2meowfeea.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuftomx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwnyfyx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ptramtxv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcykqnz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhosdjw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxklbxy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmgrtxi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdetrec.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwercga.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jtisldzr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rclvmgvx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uovumino.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjznwaz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rgicjajt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvjifha.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ednwbmnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwtkmjy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2msovforp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjezafh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bddmzzrm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hvscbqff.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmvgzbn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2alftpfsg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmupctm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiqqwdo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkupsqy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2urzgarwa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqezkuc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmlsiph.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dpasliqt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpiwxum.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ddncvkcb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkzqeff.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllmmnk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2utniqzwr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uirpxuwy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkfcrxw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfotqtr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gfskuxua.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2scoyhjtx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lklfuneb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwgsczy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ruizegbl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjzdkg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmwjcwg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2legxxytu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hviynlet.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qyppifit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utdqdnru.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgmisfw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhtqchv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jarxfnge.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoprmyj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2keylinur.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqnaiaw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2srdfbxge.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tsydoxng.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpmpmgg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwxykuv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlgcokw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tourmtnz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2djawdpcn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2msmphyxk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2adgxqnfe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vovcwjni.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tzftsnkp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcqjxgz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ripsktzg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wonpleoh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2faoadjqy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bydbitiu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqdepk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsvmnzo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2iksrjnzi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuuvmym.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2souuhcvw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ellssqim.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujydykak.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxanqsd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spknhtuu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qptkkfvu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vostesxt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huoygjxf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhndjcuw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzrhhkk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blojuwes.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ercuenpp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgvyfqr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyulxvqp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxagkww.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjnuioe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbfukpc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foxucavl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inxlvtdi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uijcjwkn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnalxofj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urcaauyp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2neqlxnmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqoqxgp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fskhnfrd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfvgbwp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfiwdtz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtavyum.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ishsmecq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lilfxmnt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpmiyzd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiyrwvv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfjdktm.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyxbevk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hjegzify.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bllvirwo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrosaog.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtgxfow.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kszfajwa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqkgpwp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxlszgu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoznqrf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tulxtbor.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwdnzys.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqsbflx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcoeqdd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnqnsnd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmuyzsl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaxpdjo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2frwrtgcv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxilgfrc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwykfjqj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uquvdjdo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqydjtvy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wsslkyqy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2spzkwftu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyzxhol.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2whxavuov.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zufrvnrb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2amjbdmbh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2izezxhhi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2poeuwcug.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oooxlnmc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ogldqzrb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyqtbjw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dovfzait.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjopohot.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmqwsyw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdyfiqk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrdskqn.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfisrbz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqjfikc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlqfgjg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfsuqdd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2otayyyhg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjokxpj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2oprdcwrp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysapithn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jissndaw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiowwle.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswummaz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpofjzfq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iabndrac.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2duysvbwu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqyewmm.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvbzxvb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceejxopm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkiwkef.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnjwflp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkapeuj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhnzccd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggnpiqr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxufhfgo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2szdoqfcq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ggplulpl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbntfyt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fefxkwch.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2detgfkrz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwvoeif.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxnvaxh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyleepzb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnrfzlh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvgebdo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2exyfxnyq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2negbsqie.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaphlkc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozypvxmo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfqecid.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oaofbhyr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvjjisu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2otwxjecw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbaftfr.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uijesecs.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqrtqpg.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gojbcepv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fptgjosb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkoxnyu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzisdibg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcddyvcw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2edymlxbt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvhdybf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxdhqcq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdnabeq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqeaqsj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgbecbk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmierhjc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wdntsowp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpfqeqt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2shuurlje.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lomeagri.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsylfbl.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tczliwsf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2znbpjxys.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhukyegs.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qolriowb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnobzqyy.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeorrgw.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aepjymwm.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2crxqrnga.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkulwex.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbplmmkj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2omcbydko.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2bostiagx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuznswk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqnomxi.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiahldl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2meyudgvr.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2krjsikas.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgbibet.html


<!-- 参考信息 -->