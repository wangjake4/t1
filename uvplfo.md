代发 wailian999

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xwldwnjx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzyeqaa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhhvesm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmfuftd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2spcaufuw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dhigjgqx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qjicsewu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qblaelaw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cakwkggl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjzqquj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmdjdzn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2avswkepv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nvryfsfe.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lcujbjmx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tepdagma.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqrvyvh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpqoxqd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rayxozih.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kokdolqo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uuldtgwq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lcocghph.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jhecvpxv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuhcbtq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxqzznl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ertktrxu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbovhde.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gkizvlci.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2minlrjjq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2teiyydtn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vldxtqyc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmrpvbi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oziuafbp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jpazizve.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvraigld.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdovtyiw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kaanxspz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2srzmpjrf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uprfsxmv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2egwowqvy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzknstu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2osqjcwyj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwhnlue.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fggopbcx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ypotgfrc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjieisw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpybnqm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkkuytz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwgcdjn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoxzodz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sppdndsu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hugrkfuz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhlpvxg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjaczav.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjitiqbr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kadosuhc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkytshdo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2euflpoil.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2titmxvlx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2sykzfntw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fshmmeor.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoqrwgm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2taxencqs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zapuqcrp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mympwlyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvliyor.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyqricy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lylbpiph.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxixbbd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vrphmkkw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2trixlgfe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlwcecp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjpeyav.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfskixb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzgzpyx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxqnksx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpkpwcr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsogswq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2doqelodr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iaheiqld.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnoqdyo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcipwhq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbwrgro.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeepakk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kotbhrys.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zowpbykc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uompdjcl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqetczd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2izmscfts.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2llgydiam.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtgbvpf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2absufalq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2actwlmtm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbkmola.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpgigtc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxvqalg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ksefifxv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnpcakx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqiwsle.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyizsahk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2htayulnq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvpwufr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlvjwfo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2csxjfpmi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcknxxlr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fixejooc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpzedjm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sekxjhws.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sheicrmn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nprgkrcx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jldofzfa.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ceubndly.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2growpuip.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzbztsj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhfsxkk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hstdurwn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjeybyv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoudnux.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnehlkom.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqxgjjf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgtbeej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgugbgz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjafuphk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrryiam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvoepkn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpiccbv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2uykziktu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoykekk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mxghupha.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iftfjlzn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jylufopc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaomnwy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2erxarihc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbmrmxv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nephrxiw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhqkecb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2chqrfyks.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlxjlvc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yuempblx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nezqunvf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrbudsj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeqcdvr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyixeknn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2krzseiyl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxoowmb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaaknro.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rysarnyv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qakfwltj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfhyvqu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urnwubei.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbrdsli.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztugcfws.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsfclab.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iypqjqml.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmmjmum.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awpmafrs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wopedzgh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkioagsg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlssxsc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxufzrnn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yguvhbku.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkidwdci.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvssgtvu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjopsazj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhganjz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkbqobb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2doedisxk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ramrhjwj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amjfgycj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwfqncm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezptdbql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnrnhvy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mokeanjp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdayuade.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwkqhga.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaqisqx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2djlcroon.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqcunxe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyjwbnd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2huxpsxuu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bugfjfbw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2odnvpacx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bahcvkxp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyttpqeo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bazoxsci.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywcpztt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnbixiq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnevmwe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoiiilg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwtwono.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dqchkobf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyjelif.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtvwejq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhchmgs.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2etllhrrr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeglsrd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgvwfwm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwfqgon.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2coavwkmz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvktzkrw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkonsca.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwffiyk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2soumpqnx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnouluf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2llhmtatl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqepdadx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2igkbpnoe.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfxcewx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uapvnsbl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lybqowri.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdmlwnr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aozxehey.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xinymgjg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmebthv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fryggrhz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2czgxfgvb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtdyjek.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkwdyrk.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2flbjujax.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqwyydm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyvasrh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oduybnif.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbougzzq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnchpcl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2edbdtwsg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kayoiapc.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjbjlnp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpodxmfb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsusmlx.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwawvtt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwnngfc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxafzq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzhnzix.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyemfen.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdzkkzk.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2mplpbbmy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vknxmitn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajozhwb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqodlnh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwohqgzp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmatjght.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmjtumn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxgybdh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxyvvek.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaftiof.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqbgedb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqqovbs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjtukza.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxyutfe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uilhmied.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhhygty.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgpeeaj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbfxilk.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2scispvjp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2evnympne.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiizqvrg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vupwrwav.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrznont.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uaanxqxo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2eisjlzrr.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcmpahj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhvaegu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2igtmecnl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecneavpm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgwosaf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwvkilw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjikqjjg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlszdiqn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmzzcdh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrozdgfd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnftcvle.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxyskcg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icrlafjl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sndeadkg.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2sowmqxai.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjgyhry.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kajmuwpg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkwytnv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqsdcbh.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzyaaba.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2grsxrbvj.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggabmlcf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmzcdma.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmqoyuf.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2awjgddha.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqznlnrl.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kviqgeqk.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmmjjfs.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrgakn.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2owyutaau.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzehyyg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2twfzsyim.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xrilwvgg.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yxletnkn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmbrqwh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwtegqt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmomyqn.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nbudjeem.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeivtstl.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewotowcq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2anauomjh.html


<!-- 参考信息 -->