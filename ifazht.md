代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvljdglu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mendjxjm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqrzphb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abkjzrfb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjqbjtw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2crpuyvna.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktehjpoz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2keenihax.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvedmh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2copznvhf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ciailheh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvinape.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcgcynz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uurbbbok.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2federbzy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwlhdvg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2scquxoma.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aauwgmdj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtiodaz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2koeinibv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tgasdihq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aobuawiu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uagiobon.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eefqannc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjmlsgz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rplxgsva.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqhwyfh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxthocks.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoepswe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjmpqcp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuakyiz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeezcoj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2inqtpscn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uovfucnz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2klovkxny.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaofmbb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2axsypyfj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnfatrr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smzxobke.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvgdlcu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiiglqu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2snsvzjyz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfmbzko.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uajndtko.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuerewl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2izbaywii.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhhyjhm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2glpjhubb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dncpoclx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaongnz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvebalv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgunccb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkyzkor.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2thnvukof.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opbseizy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2snabkcip.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaeizjc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2chbukavy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqqpeho.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmyzbyf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwdlnsq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpzgkcr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hawzbflx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nytijwyu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2abksjprs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqgmmkv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2evlmhntv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvwlkdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dghvlebw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtoocaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xiikcsja.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nsueuecz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nbajisct.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wxusfega.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrsoucn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbaehtc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xznwffha.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrcndcw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvitxfq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcboomx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2irekarkl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2arwxckjf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2icdjajfj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2phpvfeju.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gctgjjiy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrwuhxc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zljsypiq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nauonotc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fftgkxph.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqytmhoq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2falwahhe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bagvlbug.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fulbyvhl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnicwxi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqnopyk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mysctdki.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsyapio.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvopvcb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2acuiicvr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qaggyuoi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2shcidedb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mkddstvp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiwhcbm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wszeryhm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnjcpwn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qygbnfuz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wonnhxyi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dflxenro.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmpseju.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfqdgco.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsowgzr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzkkpqg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2babctvrk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyioxlu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2acqcvvas.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgdwong.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkdtxia.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzpbevu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2knmolnaa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2naqbhftw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bokvsrpd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtnaqvo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2grwmvzqh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrumbfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npcuirkv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qiunogqi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjzqidq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhuyazl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2unnwxccp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2csuqepel.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmuvmff.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlvvslf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzzkzqt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2znrhanjl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2njevqfla.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdpyint.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2axddsqfn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdjxxhm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ixltktpt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rzshlyqj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjemyhn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwlhhts.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2swepppcv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrivbusg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqswxlx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnltrfcg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaquemz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmyhoyj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgwgbsk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hmijoklx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ousjkvuz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olyxpiwc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrabuwq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlahlkb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcignibb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhagbxz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqazulfp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pptblumg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqctqtm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2letvkspu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wazdpfou.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcyevv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pabcjlan.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrkthc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhuaxcw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbskmjy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdptdwd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uelmnlcu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqpftpj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khjnetys.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2znikykby.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tafsacjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwzrfkc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lccvxumm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trcalyhj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dsggcdja.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kglqbvut.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekptcnnx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cabinptr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2aekzrzvs.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbfqrwo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikitgnvg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2frmupolt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2umwsaago.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsphpahm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlzoudp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2intftqmn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2idbwnvdv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2okzunxyl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bixtnkmf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gqayougj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dixwnmfl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cytcdfwj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hufhdsvy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgoxuhg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2voxtanwq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvctyxru.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wefhbpeu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tufkgqed.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2esvenfck.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvsdril.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2txovullv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wllqwqua.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2natyaffs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqyrhyi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ufodjmtx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2plspphxu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpoyhdy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpjobc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzseiog.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwvboi.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbhevbu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2saszatbr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uyprodty.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gfafczpu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2refrjvsn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dixghaix.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywdduw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eglwaiqs.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnjkwmx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xytlvjzx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfmahik.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2szhxnziq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpupvrqn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiomsth.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lghxsepj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlparvjm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2akrmrjta.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2varbffxb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkrhogb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhkmqvx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnckwyhe.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdohsibe.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbcxzsb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2frcajito.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptowkfyu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhtjrfk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcmnrsh.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoxjjjk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcmkejh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mscfsske.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjspebic.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2svizgzcp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzroafb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmijtoor.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rogqavob.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrkgyrr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwjveqs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frildzde.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iztfmozk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfokdxra.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvyhcht.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duwgyqkn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dyseiowk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsgdspo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnrkfnz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckivkjsa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2thklhckh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeingps.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rineyaft.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nosulzlm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pcakmcoo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvloxpl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwhgrgb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfpzyfd.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfnfpsy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2djygpdot.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jecalhtt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwhitvq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iezqwmjy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkcxxxx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eicirgvy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qstjjpqm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nefyffni.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2usmusxkm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rncnklwc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xriqhthe.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2twswebnu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaogtok.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttihqqlh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqgwzag.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhygotx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2djpesztf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2eknqekzd.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvbxxip.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nawbxodq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqsmbky.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uelyjqlx.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaitaark.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hidktplq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyhuypx.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyusquv.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkvfzbj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2rigmsokd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiycipx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qsogqncu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2scpxxdge.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ankilbxk.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oqblcpyo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2wylxtegy.html


<!-- 参考信息 -->