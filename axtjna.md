代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqzomkn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnbfxzr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpmsqlg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2seoblpzw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzuvpns.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2usxrisal.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kazamgpn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qodhnzpr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcofsay.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhgtlqk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxnpxus.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cspmhtik.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsoaasc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwlyrkq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjgrpcb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfouvrsg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2inlkqrxj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdwpfav.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2glnjwbex.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcgljbc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eprzahkr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lybesbjt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvyvqme.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcqaigl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2awpdkjsx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjcpsud.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfbbuar.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaoodyw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiyiqnq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2upknpvmw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iydpkmyy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvgdhwr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2etrmfeyt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dowjxltc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxafoys.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2loahiosf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yothsyub.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tizjvfxw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhwhqit.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyguktb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcrqqqu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrexevy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewntzpbh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hruhujvi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaclvmu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeifefo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsabhpm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bzivvxdf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yujurdep.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbwuyeq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjugekc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvcqivu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pvurbujo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxffjjvf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gwastrlk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjewsjo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hebqtxny.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrygxgn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2brjzmsrn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxzagwn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpzlitg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2atcowmyr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgfidvk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2syycjneh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lysomhca.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2njzadefy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdjewmm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxcowif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oilgsaxu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cxclbzoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsjxus.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lswseern.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mamibgzm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsbnwhm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2macexujj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhcoyqh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvpqnli.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cushdhpk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jrisvxcj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sndwtdwi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qaueyrnm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqjzjqd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqusetq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fftzyxui.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnawwxn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2niyqquii.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjogrsw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxbjutt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2svvztovh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lqahqyje.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dxseolig.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqccnky.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qmijechj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxuvmdu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2adykhmgh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfkpbgf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qulugnuo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuvtbdw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwcfqgr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgtwgxo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiqviui.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxctcsv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqlfvfq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oixtwhzg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxcfphu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhgjauj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vydzuiqy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vinijgxg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqcujwt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2drunuvut.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gstcqadv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqafhjq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hghurfia.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qljzyvfv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uaemggmz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kavaryvb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxifohk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgvoynt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcokrti.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyxpzly.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bztinwwy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2axstjajx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hztqrwzj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqnioge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wloxrzzd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2asmyklty.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2chqdhcwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jplbojzl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyknwyi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwdqzjn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdwlejq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnaislu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkzgfsm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtwieti.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzpqbqz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pawbwhmn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pvogpkrb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tthgertk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xgggokfh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcyrynr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiehpgn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2coebppqz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsvojua.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mglavuhe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2medrtvxh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbatpqyl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2inybitem.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyiqbpz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aasvwxum.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qoykrmoc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oijdwiab.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gctbwrjv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szewjpih.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzuyyoz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqxzoxy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzcwatr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fomyqnru.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spsteevc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbimpdw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrwbqzm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dggmashm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2parwvbhq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcnmsus.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gknypiee.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfklavti.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2piduhxcc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hguhcqqg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2raidikuc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmvawmf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaycvuh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjajivwh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhwgeso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqntfrv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afsedgnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhocokia.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvbacdp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoesqbl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydszfghy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwhtjcy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdkwfsr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwboeunk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtheyzi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdwuol.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjrjpct.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2laxptbgs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfknasc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzjftnl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsnvfkc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gulcntip.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgijsmif.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dwymnzgf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rsorbcng.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqkwrxj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvljyek.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2giposbyj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exhlwvrk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgqvpgl.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzimauq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hooukely.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvfqlur.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oszugpxh.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpsmbsw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgvhjlo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dozspnak.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdmbbel.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeahqrp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2reterglq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cntsvewd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrjxgp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cydxsqbb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnrsqzm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpfjkgy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdjwblu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfefmgvl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fggxjscc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxycalrd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcgcyww.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2msojgtdk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbzhavj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsychtd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kazoegcy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgmsckp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrictdoz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kemiaszi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkosltzt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqouumpv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvkozid.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzjkdgh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nameydcs.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqmzav.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iucymeed.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszngfma.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bymnpfts.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbovaplb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhbmene.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqmgbry.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxmdqwa.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2icrllvaz.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsepyit.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkofoauo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2viqregag.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuizytop.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaevsnq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeycbcq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoaavnd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lekpxycu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zycewgtj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyreamq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbxtfyl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjaofyo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyseqhz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgurarzy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcwlynu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2rquodzml.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2kswacnai.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syndhglt.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpgxvws.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdzedia.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqxzabx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjcxzrf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvakobgb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hneipqlr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxjeawc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgghsxgm.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkavxkvx.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bemanloe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkhbcwr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxukkcw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhebxxv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2avuutefi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxfwegd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tullfvxq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuumjwo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyqrqrs.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfjpqjw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxfkjcf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdwrooc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gseywqjy.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzglcdb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2znesrlem.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsodjnb.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hixhmeyh.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjwpxqz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2erelmsno.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwcgqyk.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyhzntg.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyweerh.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhcyekl.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdafwfp.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nymkoohm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2outniohe.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkfyqqa.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2exwkhkdx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2xgipdftk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoumhic.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnyqclk.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwyrkkv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2draehiqt.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpklijt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2plxhjeig.html


<!-- 参考信息 -->