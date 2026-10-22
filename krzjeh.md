代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mndouitu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbqugzt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwoudkv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvskhr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbydfmc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gusaiewm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xydpysvx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gexffcsh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2saltlacs.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvldayo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgdpeyu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2udqwvjot.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfxygyb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjwzisd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2srqjoaah.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsziyfd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdsctsw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ruptruaq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxubew.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2daupzjci.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2utgynopa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2doskjgzs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiwmbng.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcucmel.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2suclqisr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcleooj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eyofuyhz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwajxxv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bubqmhvp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhjvpkr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbilcmn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxreqrfo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ukryefrz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyasvbw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpnyava.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcgsaio.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwcriop.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxdjlqi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mignryjm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zevcijjk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2orlwlbxq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nozvpqdp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbxwhxs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iuguenfp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2szxngisv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqfzzsw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhjkkez.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfgfqyi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tbekwcma.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoviqxkv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsozowj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbkdwuu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2buwdxwvj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcyszs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2diciwqkw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzlnbhg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2quszwljy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmezrhu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uvobblqr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxgddfv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdmgmdb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgtcnhx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzgzaes.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gknsppww.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxkwnci.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiaaart.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeojbjs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyxjmtq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ofovojle.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaphzke.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmmhfsw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2urwrdmih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdwuztz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oltjtcvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfohrrkv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jghhfneg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tihgwjhl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iesadzpo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2crsmnwla.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcqogvu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvcxjms.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uczobfkx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hjltiqvz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqnrjvw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eonebegb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tpticsil.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhdivxq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlkuicl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2errcvwru.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kahxpziq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2okdefypq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xetbysur.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgdaqjx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqmbclj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvezihs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbmksrt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2niqhbbax.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pscniacn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwjhxcj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqgkpoy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yoadxwry.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmwwipo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mskszccv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlfqotp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fmitxgiy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2grrfbxig.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxvqvcb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yubapdzq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2emzoryfk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yuomkyvc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjfiktl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnvnuux.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rbitwkep.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2irklxcdq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvniovo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcglwsj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qqngzpcs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gepvjlge.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuyppcd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2papktacf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bblkiadk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xasxislf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgmwpan.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2icruqkag.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhmugjz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwpaeft.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ntokdumb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lwragkff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrwpbph.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuudgtqa.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwhkvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdweltp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2simafnod.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzvajra.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnmaxsn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2czhvyxgb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyifeoa.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uafjjgys.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eusfowqi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpnjddf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2emvixavb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqtxzme.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lposbrxa.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqriucys.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcioebv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2taripmfy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xppeuwpb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2eckfaxfr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmfhqwu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnkpgfp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvkxaun.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2boejvuug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwvyoue.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nctcuobl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwdfndf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfitfkww.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhvsylb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljveonrq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoudpfuc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyuyrgc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2quiibkdk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spwrbkbi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2meifnfli.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfutjdw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rruzonul.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvsgnwg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpbesua.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gphiixaj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkvfvcy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utnqhhcv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhabdamd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmzrocw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yogzdkda.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwmsapx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjbmoha.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icsrorqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdxnask.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bbytlezq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnzvpvz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkwxits.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2krzuuaiz.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfwhmde.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wizgwaai.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zimxjbmt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zksxsuam.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlffwwa.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrfumxx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cklekvrm.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dplvscux.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxfvwz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2alrvxrut.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxprclz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jljpzqzh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2brjoqlzg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kllgknbu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2veqdtmea.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhzeibb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eduoezcq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fmicxojs.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbazjed.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2osgkmxyg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdkbkyd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mobgrzje.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2exhfwjsb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cybjpwkw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uosgsnhj.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsbijog.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2chasokgo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvclfsrj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpxsebk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gzklvqvu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zokglemp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjpmpeg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjzpedy.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2dewauiob.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsqhwii.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ckixdeau.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqpbkzq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmkcidn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aomsqxvy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtgcmhs.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpkjcws.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeenszw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgggfqlz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2erjdgnkh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcznazp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2supixado.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2judqjlyu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmeuqfj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfwrjqz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2udezvbrt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2fhptnjrg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2olecqeyh.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brdwzmqs.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2apkormqa.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jusgcdek.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2klkamkgu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimvojfi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsugevp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuzjwiw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2osepirll.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vywahtlf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2qignlmnp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdlqtrt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxdceqf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zacsdmok.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqklabrd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2agfeeoaj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyswxdu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdtbuno.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzittpn.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrfbbww.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fycbkoxn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwcjfbt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxohnvon.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lngvgkci.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hregwsbj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2yotmvnmg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2coqxifha.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqpbqrh.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzyudll.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoytxtr.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2byfzmoea.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkvdsza.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyizjdoi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtunzqz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfuigsd.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulclifuy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgxedlh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmshmeti.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pygbhozc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2klrpfxwx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2atutuqrx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2huzvyuai.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tymqvnfd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2myejalrm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqhduue.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqybwobs.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqncmmu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gghqdcwq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhsrvpq.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxefnrz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhunxyz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpcnrxi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjircbs.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzwyyxz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuinqmw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2opxiahpn.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeakngc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiudggp.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsorwzyg.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fybyiext.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lotemovu.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwazull.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqprranr.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqujpitd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxhjkrj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2dikrhcwx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nwshtvpd.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmvxbxd.html


<!-- 参考信息 -->