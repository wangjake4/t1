代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqmmwjo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwflspd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gseknowa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2laawgwhi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2brzegvzv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2quoyenct.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2liaclsce.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmpypnb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axaajvzp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeruuxy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dynlxemh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfvhmlp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jonspmjr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wbikeoib.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjjvnaa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwuqisr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dthlldvr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wsansaqi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpipbhu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdoztkv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiyazsg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoubulo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjzaqfo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fuglymso.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nixrtivz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yygpafgp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrefkym.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvifcjby.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aykckxqv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzylrop.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mdozbtsf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwczhjsn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eggqnerh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqywqudh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sllbkbuq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gltnjxgm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkrkvhz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cyowhmgu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdszosg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuopemi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnzgykc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqytfug.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoytewh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nksamwcv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcilnbd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aexdcjnm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2achatron.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fntxstbs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsfwswk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2trtvihrx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xhomjewm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgjzqg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pfznrnbm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mahxscdw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnlvkar.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djehoxqn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrmhlqk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2svdgbuiq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2huaxycex.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxrmtet.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrfruna.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxhxzce.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2glufzzkl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhjmsdn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfipjhk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxeyuix.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rksxqwul.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yddpacvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxnldac.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2khgkfktm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kltzeqgd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bidbjbxq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ssraylvq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzkteef.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2znljgrny.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yynkopqb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjrizky.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yykgavze.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ivagrrlp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2afrglqmr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdonxxq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpxlkjt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvzmlru.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrahnam.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvvjcdr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwvfula.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kaugtmvq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxukyhk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmozau.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjsnwuv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxljlov.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpuxrav.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dowyizps.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wygbxaxv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fssfzbwe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2suolnwgj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uhydhyfu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlqlhym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2flwerubh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bblxsspr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qycubhtm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2odbdrvgb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzxgsub.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2clrdaado.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lshcetio.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2awjcigzf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxhrpvr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hijprllz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2paesokgd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cuisqjhi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fidcitso.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfbmbzj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vppgzjzl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlsrnjs.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lsshfnjb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxlxvfk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaroumb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvxzsrx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsjjkps.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmlfspv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bajbwuvi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsdhbel.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2frpymblb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfyihty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iidzmzcy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vubmdnjm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hrncgqkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aljlllqo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vgslimcm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lssfehmg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2prfpyxlj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoddqhi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yoojpowv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2afpejutx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqsjmzg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmfuqla.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbnfqqz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcbrfpw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2znmsjfzm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhdptev.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngklsuxf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjbcqum.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwgyqwj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2depgfpkv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2czwpufig.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnnyvnx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlubcaf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpxokld.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbrysod.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2obxwfyle.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzhvqln.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpezipb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvrsahu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btvbqtkk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbvwtpx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuumkdzp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qigtynjp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhufxnvk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2liwqfyho.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfdtdlp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xudbvhnf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tasbnxhj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbzvojs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tugkvvnq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmzfmjc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqdqsjo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwxqqlu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owwygjjg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcmcndi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhcitjw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2krsnfbab.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxzetyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwymhhy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvhevci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jukhzomh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kembkien.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjurlsby.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyjjfle.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjjlait.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnuyxvm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhazgnqw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkthkgd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoxqhdy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtkzxl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dltnnkcy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2avqbzwlf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvwmbny.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvbkmzj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2drsezzvt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtetupj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwionef.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2huxdbgrd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfjuyzj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xayntooq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwjibjr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqltubih.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bonpkjre.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcapssb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrlpyoh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2grscqaee.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmmnekm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lofgnukb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjkqqsh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwicjqgx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgraumx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cihdfktx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvkpvur.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ifztzqze.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkjjgzs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyfkuij.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbqokqp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhqribr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqlesyi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzalfkog.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzzmagg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmifrzn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cexxemph.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmpheax.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdswysql.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xiucsved.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzaskrn.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyeclob.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oakeibjy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hntmsuaz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2teeovzwh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dookivpt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxpugyw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jawkwptm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjrbxdl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bggrfbol.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsootbi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmlqozu.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcrvgyc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2irehzvlr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvzdywo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2agzbydvt.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2vsahsiss.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuokbii.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jieupudu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tldkhqkq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzucgql.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxiwlox.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdnisaf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2erzhianf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2orzbhnex.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hubqnrvz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzjccft.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gomelcvl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfswngu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kefrdeni.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsrhxjx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fslqpxca.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaarybf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdcnevv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2utgptxbq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzvrkpy.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsebjwth.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wseejwpt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyefhya.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzjkjwk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2igcpgami.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvcenac.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2abbwwjkk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uokwayvj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkircnt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzhvlxl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2evoibpql.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqamgrvi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjajbttk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqfkgeq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgdcghi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pccyhrev.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikekhbmm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltstdjbx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2efzatzok.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqmbudw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkqpxvy.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuwylko.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhsxelq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfbhhfh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hswjfymh.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2stiqmlhv.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpflbrdu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiouceav.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvxtnon.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgamatgy.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2usbnmdqc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qywwluli.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvjgcg.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2frcposnw.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwittg.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2birlqbol.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uufeatlp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2egcyjusm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwijdyd.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbfwjij.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dogsqmzp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2eysyteeb.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2halvuaqq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2yctxlhtl.html


<!-- 参考信息 -->