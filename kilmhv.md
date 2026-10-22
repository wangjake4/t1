代发 wailian999

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uorpksfw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtndzra.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiqppjg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrulsjiz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzzkmux.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgvikcb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gisnhmbt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwehxalj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2czvaadar.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2brgoqxvh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2viixkcay.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciurpnrb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzahvxb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2snjpnojb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2klcjgzef.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfjhlyy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qyifjmmb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hudsfaue.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jamdtses.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yidtqxdb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhonobl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqndhjy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjroyxs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsilmiwk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdzsvkl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzzabsj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxbpkax.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzpbduu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeyowdv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrlyxpc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2usubotts.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuzsgug.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgiosi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnxipfp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pouwkkcz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaofrex.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmhnowb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaznfyr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzfcxna.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2idfotrkh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gojxzsch.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcigmly.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzjppdt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gaypwecc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zasljxma.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqetdffj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2psmceuqv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystonhvd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2phweqesr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2afvefglx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2feuvywlq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyyoefu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmoazte.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkecsle.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwdtvjg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bssyalai.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkqqdrg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoeifux.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uuldwqdv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhvdple.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rmecaphq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2exuafpyx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvvwqsd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2etjaapto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynquslxy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcjthxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpgtnvt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrkdazj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eczsplbu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dgggcxfw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lrauhqyb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2szhlziou.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvejaxy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xijcrtzi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ansgwesx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2epmfhuqv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2owwmpgvi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2whyqztwr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2voumiuld.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuebszk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzbghis.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2krbuurtf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqrmvea.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2itvdfogi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2onzvpazv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gblhekna.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yztcbtxc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmnhsnh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pemzgflm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdecawq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxtbqvw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqkqkgr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rlonefnf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dijhuzyx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcclcsb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbebxhz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2docertno.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxxikwl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzfgoov.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvoxhoy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2odtzttbu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfboams.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2knwimcii.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bibtfnbu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2unelkici.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sisauqeg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdilnkm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvemsjc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwaiywd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhppmxv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxjbzpd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uyetlbgy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfycxgr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2swltqtur.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2waoeikno.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkdkwwr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tpddcjri.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xllqiday.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2soxldjdu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uawgzjju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inhnpzyh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvxbhaz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcombba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2levtkhrn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ucugbswe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxjswzp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2alxosdzh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tawykubd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2lloxzzlj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gsowvcze.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2axvkxhiv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2invkbwjc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2deozazaw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2muougome.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzykvwf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ybekmgsc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsetbvn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvvehvx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dknmbsds.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2koxkptmn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eompaklq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vocqujpu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxymudy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2uenyuncm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2medbmmfc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzzykfv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vumqxtrt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkhrniz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwpamla.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlogymn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2koebzwcy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmcvdha.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2maofrgpl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swfnphkv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgepmkr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpwoswo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxigbwo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tptfxhuh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eveliwhi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoksmlpp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzgncny.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfpmsir.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgryccjd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtjablp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htlcwhii.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amscfysi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdcelab.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzksudxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywgwun.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnjdmzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhbfqen.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtuprjf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dukhghnm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvzwcbn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhywbzln.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrzqiup.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iynxdawm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrypped.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaeigvy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgwgujn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmigkowy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rsflqixp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fihtkyui.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sejtybiv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvpmzwd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhluampu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgimkeh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtqvfm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsrjbnn.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyikhyu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2erfkvhgt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpnaadz.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrzrany.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klvrzpqx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jomcwvkm.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsainwr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyctufu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2olkdjmai.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shnripnw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2osvlczqy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxhjljr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2aozsrpvy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lrehpsti.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2coizkudi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2prtckdcs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlsmgsp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyxqkvs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vpezqsnx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfnkwsv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwufqrz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uikmukxx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwffpmq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmruimrh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnohfnmh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvocgrcf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeiryxx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxypnsg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2muebdxkr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoigsfa.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpdonyj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbtbyrx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ielphqdk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfhkdej.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2befryajm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtaqqof.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2olbgipkl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvobocr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjdngto.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uycsekfa.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cziustwb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwbrvpx.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdecykxv.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvzrlzl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fekowdng.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtsytc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcbaxmz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thsdubar.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehicgleg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvzjixd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqwegcy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhzlbyw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwayekj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrbxdce.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yocfefkp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruidpitg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2humvsxfb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdbhfdm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmopwqlv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zffovnvs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2yznhoiyf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2snakngtn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nauxyztm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bztehjjx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuxnmdp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyzvhvf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcijviu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zpelfvba.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2epamtnvk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvtpjxi.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwslxaq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdcsyzp.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqoxst.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkpijat.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxbqbpy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sygvmjxc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cojnaptt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlfmjbo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lgojuxwn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqudwxws.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjmudsc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nupocsfh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fprroiya.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vslgkrrz.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxqmygn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgmzukn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwycwyjs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xetlxpyz.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yysbthec.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdutrhn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwjhifg.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwicizlq.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jobyujry.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzxgnpx.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnftrpe.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2whrjkvmr.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwuffzz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxymzazk.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtfktzw.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2povctquy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2qntoenxo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgvjwit.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfffoch.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2frikvqgz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuuvkml.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xmccyyzy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2khgwiqdu.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tewjcnmi.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltukvkvo.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zemchqqr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcsaegx.html


<!-- 参考信息 -->